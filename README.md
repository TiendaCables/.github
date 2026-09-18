<div align="center">
  <img src="https://avatars.githubusercontent.com/u/184380236?v=4" width="120" alt="TiendaCables logo">

# TiendaCables

**Cables, connectivity and the software we build to run the business better.**

[Website](https://www.tiendacables.com/) · [Open source](https://github.com/orgs/TiendaCables/repositories) · [Contact](mailto:info@tiendacables.com)
</div>

We are a Spanish B2B and B2C retailer with an online store, a physical shop and our own warehouse. Our catalogue covers cables, adapters, networking, security systems, smart home products, power supplies and the less obvious connections that are usually difficult to find.

Behind the shop, we build the tools and integrations needed to keep a real catalogue, stock, sales and operations in sync. Some are internal. When a tool can be useful outside TiendaCables, we try to publish it.

## What we work with

- **Commerce:** Shopify for the storefront, catalogue and online sales; Holded for finance and back-office workflows.
- **Internal applications:** TanStack, TypeScript, Clerk and Meilisearch.
- **Integrations and automation:** Shopify APIs, Holded, Google, Semrush, Firecrawl and our own internal services.
- **Infrastructure:** Rust, Docker, Coolify, Cloudflare Workers, Zero Trust, Tunnels and R2.
- **Operations:** catalogue quality, inventory flows, supplier data, analytics, technical SEO and B2B tooling.

We keep customer-facing systems easy to use and operational systems boring on purpose: explicit ownership, auditable data and as little unnecessary public exposure as possible.

## Open source

### [Crawlytic](https://github.com/TiendaCables/crawlytic)

A self-hosted technical SEO auditor written in Rust. Crawlytic discovers URLs, stores crawl evidence in SQLite, evaluates versioned rules and exposes the results through a terminal UI or a headless audit command.

It started as an internal need: inspect a large Shopify catalogue without turning every audit into another SaaS subscription or losing the evidence between runs.

```sh
cargo install --git https://github.com/TiendaCables/crawlytic.git --locked crawlytic
```

Crawlytic is available under the MIT License.

## How we build

Our repositories favour small, inspectable systems over opaque automation. Secrets stay out of source control, integrations receive the minimum access they need, and self-hosted services remain private unless there is a reason to expose them.

Most of our business platform is private because it contains company workflows and commercial data. Public repositories contain the parts we can share cleanly.

## Find us

- Store: [tiendacables.com](https://www.tiendacables.com/)
- GitHub: [github.com/TiendaCables](https://github.com/TiendaCables)
- Email: [info@tiendacables.com](mailto:info@tiendacables.com)
- Location: Spain
