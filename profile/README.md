# SerpKite

**[SerpKite](https://serpkite.com) is a Google search API built for AI agents.** Results come back as clean JSON, token-lean compact JSON or LLM-ready Markdown, with official SDKs, framework integrations and a remote MCP server.

- **Search verticals:** web, news, images, videos, maps, places, reviews, shopping, scholar, patents and autocomplete, all under `https://api.serpkite.com/v1`
- **Web content:** any public page as Markdown (`/v1/webpage`), HTML/PDF extraction, site maps and async crawls
- **AI layer:** cited answers from live Google results (`/v1/answer` with SSE streaming, or `include_answer` on search and news), JSON-schema extraction and page summaries on `/v1/extract`, and async deep research with cited reports (`/v1/research`). Failed AI steps are free
- **AI assistant answers:** ask ChatGPT, Gemini, Copilot Search, Google AI Mode or Brave as a logged-out user (`/v1/chatgpt`, `/v1/gemini`, `/v1/copilot`, `/v1/ai_mode`, `/v1/brave_ai`) and get the answer with the sources it cited and mentions of the brands you track; `/v1/search` returns Google's AI Overview as `ai_overview`. Failed answers are free
- **Scheduled monitors and batches** with signed webhooks
- **Pricing:** prepaid credits that never expire; failed, empty and blocked requests are free. Free tier: 1,000 credits on signup, +1,500 for linking GitHub or Google, 1,000 every month. See [pricing](https://serpkite.com/pricing).

## Get started

```bash
curl "https://api.serpkite.com/v1/search?q=best+serp+api&format=markdown" \
  -H "Authorization: Bearer $SERPKITE_API_KEY"
```

Get a key at [app.serpkite.com](https://app.serpkite.com), then read the [quickstart](https://serpkite.com/docs/quickstart).

## Official SDKs and integrations

| | Install | Repo |
| --- | --- | --- |
| TypeScript / JavaScript | `npm install serpkite` | [serpkite-js](https://github.com/SerpKite/serpkite-js) |
| Python (sync + async, CrewAI tool) | `pip install serpkite` | [serpkite-python](https://github.com/SerpKite/serpkite-python) |
| Go | `go get github.com/serpkite/serpkite-go` | [serpkite-go](https://github.com/SerpKite/serpkite-go) |
| LangChain | `pip install langchain-serpkite` | [langchain-serpkite](https://github.com/SerpKite/langchain-serpkite) |
| Vercel AI SDK | `npm install @serpkite/ai-sdk` | [serpkite-ai-sdk](https://github.com/SerpKite/serpkite-ai-sdk) |
| n8n | `n8n-nodes-serpkite` | [n8n-nodes-serpkite](https://github.com/SerpKite/n8n-nodes-serpkite) |
| Dify | Dify Marketplace | [dify-serpkite](https://github.com/SerpKite/dify-serpkite) |
| Remote MCP server (23 tools, incl. `answer`, `research` and `chatgpt`/`gemini`/`copilot`/`ai_mode`/`brave_ai`) | `https://api.serpkite.com/v1/mcp` | [serpkite-mcp](https://github.com/SerpKite/serpkite-mcp) |
| SearXNG engine | | [searxng-serpkite](https://github.com/SerpKite/searxng-serpkite) |
| GPT Researcher retriever | | [gpt-researcher-serpkite](https://github.com/SerpKite/gpt-researcher-serpkite) |

## Links

[Website](https://serpkite.com) · [Docs](https://serpkite.com/docs) · [llms.txt](https://serpkite.com/llms.txt) · [OpenAPI](https://serpkite.com/openapi/serp-api.yaml) · [Status](https://status.serpkite.com) · [X](https://x.com/SerpKite) · [Bluesky](https://bsky.app/profile/serpkite.com) · support@serpkite.com
