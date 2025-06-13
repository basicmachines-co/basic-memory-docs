# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## About this Repository

This is the documentation repository for Basic Memory, a local-first knowledge management system built with the Model Context Protocol (MCP). The documentation is built using Mintlify and contains guides, integrations, technical references, and how-to content.

## Development Commands

### Local Preview
```bash
# Install Mintlify CLI (required)
npm i -g mintlify

# Start local development server
mintlify dev

# Re-install dependencies if needed
mintlify install
```

### Troubleshooting
- If `mintlify dev` fails, run `mintlify install` first
- Ensure you're in the directory with `docs.json`
- Check that file paths in content match those defined in `docs.json`

## Architecture

### Documentation Structure
- `docs.json` - Mintlify configuration defining navigation and structure
- `*.mdx` files - Documentation content written in MDX (Markdown + JSX)
- `attachments/` - Images, videos, and assets referenced in documentation
- `guides/` - Technical guides and references
- `integrations/` - Setup guides for different tools
- `how-to/` - Use case examples and tutorials
- `technical/` - Architecture and implementation details

### Content Organization
The documentation follows a structured hierarchy defined in `docs.json`:
- Get Started: Basic setup and user guide
- Guides: Technical references (CLI, MCP tools, knowledge format)
- Integrations: Platform-specific setup (Claude Desktop, VSCode, Obsidian)
- How-to: Use case examples
- Technical: Implementation details and architecture

### Key Content Areas
- **CLI Reference** (`guides/cli-reference.mdx`): Complete command documentation for basic-memory CLI
- **MCP Tools Reference** (`guides/mcp-tools-reference.mdx`): Model Context Protocol integration details
- **Knowledge Format** (`guides/knowledge-format.mdx`): How Basic Memory structures knowledge
- **Technical Information** (`technical/technical-information.mdx`): Architecture and implementation details

## Deployment

Changes are automatically deployed to production when pushed to the main branch via GitHub integration. No manual deployment steps required.

## Content Guidelines

When editing documentation:
- Use MDX format with Mintlify components (Card, CardGroup, Info, Warning, etc.)
- Reference file paths in `docs.json` for navigation structure
- Keep technical accuracy aligned with the actual Basic Memory implementation
- Images and assets go in `attachments/` directory
- Use consistent formatting and component patterns from existing content