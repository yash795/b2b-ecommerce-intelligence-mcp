# B2B Company, ATS Jobs & Shopify Intelligence MCP Server

An all-in-one **Model Context Protocol (MCP)** server powered by Apify that gives **Claude Desktop**, **Cursor**, **Windsurf**, and autonomous AI agents real-time access to:

1. **B2B Domain & Company Intelligence (`b2b-domain-intelligence-extractor`):** Extract verified public emails, social links, SaaS tech stack (HubSpot, Stripe, Salesforce, Next.js, Shopify), pricing pages, and hiring signals from any company domain.
2. **Unified ATS Jobs & Hiring Signals (`ats-jobs-hiring-signals-scraper`):** Auto-detect and extract live job openings, salary bands, remote status, and department headcount growth across **Greenhouse**, **Ashby**, and **Lever**.
3. **Shopify Catalog, Pricing & Inventory (`shopify-product-pricing-inventory-scraper`):** Extract live products, variant prices, sale discounts (`compare_at_price`), SKUs, and stock availability from any Shopify store.

## Quick Setup (Claude Desktop / Cursor / Windsurf)

Add the following to your `claude_desktop_config.json` or `.cursor/mcp.json` (get a free API token at [Apify Integrations](https://console.apify.com/settings/integrations)):

```json
{
  "mcpServers": {
    "b2b-ecommerce-intelligence": {
      "url": "[https://mcp.apify.com/?actors=](https://mcp.apify.com/?actors=)goku79/b2b-domain-intelligence-extractor,goku79/ats-jobs-hiring-signals-scraper,goku79/shopify-product-pricing-inventory-scraper",
      "headers": {
        "Authorization": "Bearer YOUR_APIFY_API_TOKEN"
      }
    }
  }
}
```

##Direct Apify Store Links

* [B2B Domain & Company Intelligence Extractor](https://www.google.com/search?q=https://apify.com/goku79/b2b-domain-intelligence-extractor)
* [ATS Jobs & Hiring Signals Scraper (Greenhouse, Lever, Ashby)](https://www.google.com/search?q=https://apify.com/goku79/ats-jobs-hiring-signals-scraper)
* [Shopify Product, Pricing & Inventory Scraper](https://www.google.com/search?q=https://apify.com/goku79/shopify-product-pricing-inventory-scraper)

