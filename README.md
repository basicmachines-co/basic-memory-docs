# Basic Memory Documentation

This repository contains the official documentation for [Basic Memory](https://memory.basicmachines.co), a local-first knowledge management system that enables persistent semantic graphs through AI conversations.

## About Basic Memory

Basic Memory allows you to build a knowledge graph from natural conversations with AI assistants like Claude. All knowledge is stored in standard Markdown files on your computer, giving you complete control and ownership of your data.

**Key Features:**
- 🏠 **Local-first** - All data stored in plain text files you control
- 🤖 **AI Integration** - Seamless integration with Claude Desktop via MCP
- 🔗 **Knowledge Graph** - Automatic semantic connections between notes  
- 📝 **Standard Markdown** - Compatible with any text editor or Obsidian
- 🔄 **Real-time Sync** - Changes appear immediately across conversations
- 📂 **Multi-Project** - Organize knowledge across different contexts

## Documentation Structure

- **Get Started** - Installation, setup, and first use
- **Guides** - In-depth technical guides and references
- **Integrations** - Setup guides for Claude, Obsidian, and authentication
- **Technical** - Architecture and implementation details

## Links

- **Website**: [basicmachines.co](https://basicmachines.co)
- **Documentation**: [docs.memory.basicmachines.co](https://docs.memory.basicmachines.co)
- **GitHub**: [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory)
- **PyPI**: [basic-memory](https://pypi.org/project/basic-memory/)
- **Discord**: [Join our community](https://discord.gg/tyvKNccgqN)
- **Reddit**: [r/basicmemory](https://www.reddit.com/r/basicmemory)

## Development

This documentation is built with [Mintlify](https://mintlify.com). To preview changes locally:

### Setup

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

### Preview

Run the following command at the root of your documentation (where docs.json is):

```bash
mintlify dev
```

### Publishing

Changes are automatically deployed to production when pushed to the main branch via GitHub integration.

## Contributing

We welcome contributions to improve the documentation! Please:

1. Fork this repository
2. Make your changes
3. Test locally with `mintlify dev`
4. Submit a pull request

## Troubleshooting

- **Mintlify dev isn't running** - Run `mintlify install` to re-install dependencies
- **Page loads as a 404** - Make sure you are running in a folder with `docs.json`
- **Changes not appearing** - Check that your file paths match those in `docs.json`

## License

This documentation is part of the Basic Memory project. See the main repository for license information.

---

Built with ❤️ by [Basic Machines](https://basicmachines.co)