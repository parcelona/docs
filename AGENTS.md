# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- These are user docs for Parcelona, the Mac app. Write for people selling their stuff, not developers.
- "Listing" is one item. "Draft" is a listing that hasn't posted. "Post" is publishing it to a marketplace.
- "Claude" is what researches and drafts. "Parcelona's server" is where drafting runs.
- Name UI exactly as the app does, in bold: **Settings › eBay**, **Connect eBay…**, **Use phone**.

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Base every claim on the app's code in parcelona/inertia (`desktop/Sources/Parcelona`). Don't invent features.
- Don't document developer tools: terminal tabs, the eBay sandbox, Facebook proxy and CapSolver settings.
