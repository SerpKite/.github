# SerpKite

**[SerpKite](https://serpkite.com) is a Google search API built for AI agents.** Results come back as clean JSON, token-lean compact JSON or LLM-ready Markdown, with official SDKs, framework integrations and a remote MCP server.

- **Search verticals:** web, news, images, videos, maps, places, reviews, shopping, scholar, patents and autocomplete, all under `https://api.serpkite.com/v1`
- **Web content:** any public page as Markdown (`/v1/webpage`), HTML/PDF extraction, site maps and async crawls
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
| Remote MCP server | `https://api.serpkite.com/v1/mcp` | [serpkite-mcp](https://github.com/SerpKite/serpkite-mcp) |
| SearXNG engine | | [searxng-serpkite](https://github.com/SerpKite/searxng-serpkite) |
| GPT Researcher retriever | | [gpt-researcher-serpkite](https://github.com/SerpKite/gpt-researcher-serpkite) |

## Links

[Website](https://serpkite.com) · [Docs](https://serpkite.com/docs) · [llms.txt](https://serpkite.com/llms.txt) · [OpenAPI](https://serpkite.com/openapi/serp-api.yaml) · [Status](https://status.serpkite.com) · [X](https://x.com/SerpKite) · [Bluesky](https://bsky.app/profile/serpkite.com) · support@serpkite.com
