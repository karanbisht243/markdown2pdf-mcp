# markdown2pdf-mcp

⚡ Markdown to PDF conversion, for agents. ⚡

> Agents speak Markdown. Humans prefer PDF.
> We bridge the gap for the final stage of your agentic workflow.
> No sign-ups, no credit cards, just sats for bytes.

Read the full documentation at [markdown2pdf.ai](https://markdown2pdf.ai)

Here’s the output of a markdown file converted to PDF format, showing cover page, table of contents and table support. Our engine is powered by LaTeX rather than HTML to PDF conversion as many other libraries and services use, which results in a much higher quality, print-ready output.

<img src="https://mintlify.s3.us-west-1.amazonaws.com/serendipityai/images/examples.png" alt="Markdown to PDF examples" />

This package provides MCP server support for clients such as Claude Desktop. You can read full instructions on how to configure Claude in [our documentation](https://markdown2pdf.ai/mcp).

## Quickstart

Just drop the following into your Claude Desktop configuration file.

```json
"mcpServers": {

    "markdown2pdf": {
      "command":"npx",
      "args": ["@serendipityai/markdown2pdf-mcp"],
      "cwd": "~"
    }
}
```

Once you've done that, try asking Claude:

`Generate some lorem ipsum in markdown format and then make a PDF out of it`