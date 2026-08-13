# Shimmy for LazyCat

LazyCat LPK packaging for [Shimmy](https://github.com/Michael-A-Kuykendall/shimmy), a lightweight local AI inference server with an OpenAI-compatible API.

The application provides two launcher entries on the same domain:

- `API` opens the Shimmy API root.
- `API Help` opens `/help` with the current instance API base URL and endpoint list.

Image updates follow Vulkan release tags such as `2.5.0-vulkan` from `ghcr.io/dockers-x/shimmy`, mapping them to the application version `2.5.0`. GitHub Actions builds a versioned LPK Release asset and publishes it to both the official LazyCat Store and the MiaoMiao private store.
