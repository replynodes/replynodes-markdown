# ReplyNodes Markdown

## Turn any public URL into clean Markdown for AI agents.

[ReplyNodes Markdown](https://md.replynodes.com) is a free, public URL-to-Markdown endpoint. No signup and no API key are required.

### Quick start

Put the URL after the production endpoint prefix:

- Full URL: `https://md.replynodes.com/https://example.com`
- Bare host, path, and query: `https://md.replynodes.com/example.com/?foo=bar`

The prefix accepts either a complete URL or a bare host followed by its path and query string. Quote URLs in shell commands when they contain `?` or `&`.

```bash
curl 'https://md.replynodes.com/example.com/?foo=bar'
```

Example response:

```markdown
# Example Domain

This domain is for use in documentation examples without needing permission. Avoid use in operations.

[Learn more](https://iana.org/domains/example)
```

### Useful for

- LLM context and agent inputs
- Research workflows
- Retrieval-augmented generation (RAG)
- Converting public documentation and articles into clean Markdown

Try the [live endpoint](https://md.replynodes.com). **OpenClaw/ClawHub skill: [url-to-markdown](https://clawhub.ai/replynodes-ai/skills/url-to-markdown)**.

Powered by [ReplyNodes](https://replynodes.com). Found a problem or have an idea? [Open an issue](https://github.com/replynodes/replynodes-markdown/issues).
