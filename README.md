# rozum

**Permission-aware memory for AI in multi-tenant products.**

## What is it

A standalone service that runs the whole data pipeline behind your AI. It takes in your customers' data, turns it into text, extracts entities and facts, and indexes everything for fast search. Every part is a plugin you can swap.

## How it works

1. **Upload** through the API: files, chats, or what your agents write back.
2. **Parse**: text from PDF, Office and plain files; scans, images and recordings with plugins.
3. **Clean**: keys and personal data are removed before anything is stored or sent to a model.
4. **Understand**: people, companies, facts and dates, each linked to its source.
5. **Index**: embeddings and full-text, for search by meaning and by words.
6. **Answer**: your AI asks over the API or MCP and gets the latest facts, only what that user may see, with their sources.

## Who it's for

Teams building AI into products used by many companies.

## Status

⭐ Star or watch this repository to hear when it lands.

## Links

- [rozum.dev](https://rozum.dev)
- [hello@rozum.dev](mailto:hello@rozum.dev)
- [Security](SECURITY.md)

## License

[Apache-2.0](LICENSE)
