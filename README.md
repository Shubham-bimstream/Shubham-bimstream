# Shubham Pandey

**Staff Engineer · Spatial Computing & Applied AI**

Sole architect of [CERQA](https://cerqa.cloud) at BIMstream — a 10-module digital-twin SaaS for owners, operators, and AEC teams of the built environment. Now serving **30+ named enterprise customers** including Gensler, Sasaki, Payette, Stantec, Suffolk, HNTB, Harvard, MIT, Broad Institute, BXP, SL Green, RXR, Manulife, Boston Logan, and the Boston Red Sox — with *hundreds of millions of square feet* captured across the platform.

~390K LOC across React 18 / .NET 8 and a 5-service AWS polyrepo, running at **99.9% uptime with 500+ concurrent users**. Production AI on AWS Bedrock with a 5-model fallback chain, self-hosted vector RAG over MongoDB, and a custom **51-tool Model Context Protocol server**.

### Background

Civil engineer → MBA (RICS School of Built Environment) → Scan-to-BIM delivery for Harvard, MIT, Boston Logan, Fenway Park → built CERQA from greenfield as the only engineer. Frequent travel to US client sites (B1/B2 valid through 2033).

### Selected open-source extracts (in progress)

Most of my code lives in private repos at BIMstream. These are extracts from CERQA learnings that are useful as standalone tools:

- **[`cloudfront-aes-gcm-token`](https://github.com/Shubham-bimstream/cloudfront-aes-gcm-token)** — stateless AES-GCM signed asset tokens; CERQA's `AssetTokenService` minus the platform-specific bits. Zero runtime deps, 28 tests, key rotation, AAD-bound version byte.
- **`e57-streaming-reader`** — pure-Python scan-by-scan E57 reader. Peak RAM 12–15 GB vs PDAL's 150–250 GB on the same input. *(Coming soon.)*
- **`mcp-server-template`** — Zod-validated, output-sanitised MCP server scaffold for production use. *(Coming soon.)*

### Connect

[LinkedIn](https://www.linkedin.com/in/shubhamald/) · [Portfolio](https://shubhampandey.dev) · [cerqa.cloud](https://cerqa.cloud) · shubham.rics@gmail.com
