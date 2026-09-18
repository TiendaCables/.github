<div align="center">
  <img src="https://avatars.githubusercontent.com/u/184380236?v=4" width="120" alt="TiendaCables logo">

# TiendaCables

**Cables, connectivity and the software we build to run the business better.**

[Website](https://www.tiendacables.com/) · [Open source](https://github.com/orgs/TiendaCables/repositories) · [Contact](mailto:info@tiendacables.com)
</div>

We are a Spanish B2B and B2C retailer with an online store, a physical shop and our own warehouse. Our catalogue covers cables, adapters, networking, security systems, smart home products, power supplies and the less obvious connections that are usually difficult to find.

Behind the shop, we build the tools and integrations needed to keep a real catalogue, stock, sales and operations in sync. Some are internal. When a tool can be useful outside TiendaCables, we try to publish it.

## What we build

Our software work grows out of day-to-day commerce: catalogue quality, inventory workflows, operational reporting, technical SEO and tools for handling product data at scale.

The public repositories here contain projects that are useful beyond our own store and can be documented and maintained in the open.

## Open source

### [Crawlytic](https://github.com/TiendaCables/crawlytic)

A self-hosted technical SEO auditor written in Rust. Crawlytic discovers URLs, stores crawl evidence in SQLite, evaluates versioned rules and exposes the results through a terminal UI or a headless audit command.

It started as an internal need: inspect a large ecommerce catalogue without turning every audit into another SaaS subscription or losing the evidence between runs.

```sh
cargo install --git https://github.com/TiendaCables/crawlytic.git --locked crawlytic
```

Crawlytic is available under the MIT License.

## How we build

We favour focused tools with clear behaviour, useful documentation and evidence that can be inspected later. Public releases are deliberately separated from company data and store-specific workflows.

## Find us

- Store: [tiendacables.com](https://www.tiendacables.com/)
- GitHub: [github.com/TiendaCables](https://github.com/TiendaCables)
- Email: [info@tiendacables.com](mailto:info@tiendacables.com)
- Location: Spain
