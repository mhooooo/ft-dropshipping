# 🛒 FT Dropshipping — Skills & Tools Discovery Report

**Date:** April 3, 2026  
**For:** FT Dropshipping (Lazada / Shopee / TikTok Shop — Thailand)  
**Method:** Comprehensive search across skills.sh ecosystem (90+ skills evaluated)  
**Already Installed:** 17 public skills + 7 custom skills on current DeerFlow instance

---

## Executive Summary

I searched across **12 categories** and discovered **78 relevant skills** from the skills.sh ecosystem. Below is the curated list organized by business function, with **priority ratings** for FT Dropshipping's specific needs (Thai market, CJ Dropshipping supplier, Lazada/Shopee/TikTok Shop channels).

### Priority Legend
- 🔴 **CRITICAL** — Install immediately, core to operations
- 🟡 **HIGH** — Install in first month, significant competitive advantage  
- 🟢 **NICE-TO-HAVE** — Install when scaling, useful but not urgent
- ⚪ **REFERENCE** — Not installable but useful as knowledge/framework

---

## 1. 🏪 E-Commerce & Marketplace Platform

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🔴 | [`apify/agent-skills@apify-ecommerce`](https://skills.sh/apify/agent-skills/apify-ecommerce) | 3,200 | Scrape product data, prices, reviews from **Shopee, Lazada, Amazon, 40+ marketplaces**. Keyword search + category scraping. | **#1 pick.** Directly supports Shopee + Lazada price monitoring and competitor product research. |
| 🔴 | [`quantmind-br/skills@shopee`](https://skills.sh/quantmind-br/skills/shopee) | 9 | **Shopee-specific** — search products, get details, compare prices, extract cookies for authenticated access. Python script. | **Purpose-built for Shopee.** Search by keyword, sort by sales/price. |
| 🟡 | [`eddiebe147/claude-settings@e-commerce-manager`](https://skills.sh/eddiebe147/claude-settings/e-commerce-manager) | 51 | Persona skill — e-commerce management expertise, operations framework. | Good general e-commerce decision-making persona. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@tiktok-shop-integration`](https://skills.sh/finsilabs/awesome-ecommerce-skills/tiktok-shop-integration) | 28 | TikTok Shop setup, product listing, order management workflows. | Directly relevant for your TikTok Shop channel. |
| 🟡 | [`danhvb/my-ba-skills@e-commerce-domain-knowledge`](https://skills.sh/danhvb/my-ba-skills/e-commerce-domain-knowledge) | 38 | E-commerce domain knowledge base for business analysis. | Framework for e-commerce business decisions. |
| 🟢 | [`medusajs/medusa-agent-skills@storefront-best-practices`](https://skills.sh/medusajs/medusa-agent-skills/storefront-best-practices) | 971 | Medusa.js storefront best practices. | Only if you build a standalone storefront later. |

**Install Command (Top Picks):**
```bash
npx skills add apify/agent-skills --skill apify-ecommerce
npx skills add quantmind-br/skills --skill shopee
npx skills add finsilabs/awesome-ecommerce-skills --skill tiktok-shop-integration
```

---

## 2. 📦 Dropshipping & Supplier Sourcing

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🔴 | [`aahl/skills@maishou`](https://skills.sh/aahl/skills/maishou) | 1,100 | **Chinese e-commerce price comparison** — searches Taobao, Tmall, JD, PDD, 1688, Douyin, Kuaishou. Gets prices, coupons, purchase links. | **Critical for CJ Dropshipping sourcing.** Compare 1688 wholesale prices vs CJ costs. Find alternative suppliers. |
| 🔴 | [`shopmeskills/mcp@cn-ecommerce-search`](https://skills.sh/shopmeskills/mcp/cn-ecommerce-search) | 247 | MCP server — search products across Taobao, Tmall, Xiaohongshu. No API key needed. Sort by price, sales, relevance. | **Zero-config product research** across Chinese platforms. Perfect for finding trending products. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@dropshipping-integration`](https://skills.sh/finsilabs/awesome-ecommerce-skills/dropshipping-integration) | 11 | Full dropshipping setup guide — inventory sync, order routing, supplier integration. Code templates for Shopify/WooCommerce/custom. | **Framework for building your fulfillment pipeline.** Inventory sync code is reusable. |
| 🟡 | [`zero2ai-hub/skill-dropshipping-sourcing@skill-dropshipping-sourcing`](https://skills.sh/zero2ai-hub/skill-dropshipping-sourcing/skill-dropshipping-sourcing) | 52 | Dropshipping product sourcing methodology and supplier evaluation. | Structured approach to evaluating new suppliers. |
| 🟡 | [`skills.volces.com@sourcing-in-china`](https://skills.sh/skills.volces.com/sourcing-in-china) | 8 | China sourcing expertise — suppliers, negotiation, quality control. | Useful when dealing with CJ or expanding to direct suppliers. |
| 🟡 | [`kunhai-88/shopme-mcp@cross-border-price-compare`](https://skills.sh/kunhai-88/shopme-mcp/cross-border-price-compare) | 9 | Cross-border price comparison across platforms. | Compare landed costs across sourcing options. |
| 🟢 | [`nexscope-ai/ecommerce-skills@dropshipping-product-research`](https://skills.sh/nexscope-ai/ecommerce-skills/dropshipping-product-research) | 11 | Dropshipping product research framework. | Alternative research methodology. |

**Install Command (Top Picks):**
```bash
npx skills add aahl/skills --skill maishou
npx skills add shopmeskills/mcp --skill cn-ecommerce-search
npx skills add finsilabs/awesome-ecommerce-skills --skill dropshipping-integration
```

---

## 3. 📊 Product Research & Competitor Monitoring

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🔴 | [`buluslan/ecommerce-competitor-analyzer@ecommerce-competitor-analyzer`](https://skills.sh/buluslan/ecommerce-competitor-analyzer/ecommerce-competitor-analyzer) | 681 | **E-commerce competitor analysis** — pricing, product mix, positioning analysis. | Directly analyze Lazada/Shopee competitors. |
| 🟡 | [`majiayu000/claude-arsenal@product-discovery`](https://skills.sh/majiayu000/claude-arsenal/product-discovery) | 191 | Product discovery and market opportunity identification. | Find trending products before competitors. |
| 🟡 | [`guia-matthieu/clawfu-skills@competitor-monitor`](https://skills.sh/guia-matthieu/clawfu-skills/competitor-monitor) | 66 | Systematic competitor monitoring with change detection. | Track competitor price changes and new listings. |
| 🟡 | [`eddiebe147/claude-settings@competitive-intelligence`](https://skills.sh/eddiebe147/claude-settings/competitive-intelligence) | 57 | Competitive intelligence gathering persona. | Strategic analysis of market landscape. |
| 🟡 | [`eddiebe147/claude-settings@competitor-tracker`](https://skills.sh/eddiebe147/claude-settings/competitor-tracker) | 48 | Competitor tracking workflows. | Ongoing monitoring framework. |
| 🟢 | [`vivy-yi/xiaohongshu-skills@product-selection`](https://skills.sh/vivy-yi/xiaohongshu-skills/product-selection) | 60 | Product selection methodology from Xiaohongshu trends. | Spot trending products on Chinese social commerce. |
| 🟢 | [`ask-ditto/ditto-product-research-skill@ditto-product-research`](https://skills.sh/ask-ditto/ditto-product-research-skill/ditto-product-research) | 32 | Structured product research methodology. | General product research framework. |

**Install Command (Top Picks):**
```bash
npx skills add buluslan/ecommerce-competitor-analyzer --skill ecommerce-competitor-analyzer
npx skills add majiayu000/claude-arsenal --skill product-discovery
npx skills add guia-matthieu/clawfu-skills --skill competitor-monitor
```

---

## 4. 💰 Pricing & Margin Optimization

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🔴 | [`eddiebe147/claude-settings@pricing-strategist`](https://skills.sh/eddiebe147/claude-settings/pricing-strategist) | 51 | Pricing strategy expertise — competitive pricing, psychological pricing, margin optimization. | **Core skill.** Dropshipping margins are tight — every ฿ matters. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@dynamic-pricing`](https://skills.sh/finsilabs/awesome-ecommerce-skills/dynamic-pricing) | 6 | Dynamic pricing algorithms, competitor-reactive pricing rules. | Auto-adjust prices based on competitor movements. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@profit-margin-analysis`](https://skills.sh/finsilabs/awesome-ecommerce-skills/profit-margin-analysis) | 12 | Profit margin analysis with fee structures and hidden costs. | **Critical for Lazada/Shopee** where commission + shipping fees eat margins. |
| 🟡 | [`eddiebe147/claude-settings@unit-economics-calculator`](https://skills.sh/eddiebe147/claude-settings/unit-economics-calculator) | 47 | Unit economics modeling per product. | Calculate true per-unit profitability after all fees. |
| 🟢 | [`eddiebe147/claude-settings@pricing-page-optimizer`](https://skills.sh/eddiebe147/claude-settings/pricing-page-optimizer) | 47 | Pricing page/display optimization. | Useful for standalone storefront later. |

**Install Command (Top Picks):**
```bash
npx skills add eddiebe147/claude-settings --skill pricing-strategist
npx skills add finsilabs/awesome-ecommerce-skills --skill profit-margin-analysis
npx skills add finsilabs/awesome-ecommerce-skills --skill dynamic-pricing
```

---

## 5. 📢 Advertising & Campaign Management

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🔴 | [`anthropics/knowledge-work-plugins@campaign-plan`](https://skills.sh/anthropics/knowledge-work-plugins/campaign-plan) | 370 | Marketing campaign planning — strategy, budget allocation, timeline, KPIs. | Plan Lazada/Shopee campaign promotions (11.11, 12.12, Songkran). |
| 🔴 | [`finsilabs/awesome-ecommerce-skills@tiktok-ads-integration`](https://skills.sh/finsilabs/awesome-ecommerce-skills/tiktok-ads-integration) | 15 | TikTok Ads setup, campaign structure, creative specs. | **Direct TikTok Shop ad management.** |
| 🟡 | [`karausab590-ops/clawads-marketing-skills@tiktok-dropshipping-ad-scripts`](https://skills.sh/karausab590-ops/clawads-marketing-skills/tiktok-dropshipping-ad-scripts) | 6 | **TikTok ad scripts specifically for dropshipping.** | Purpose-built for your exact use case. |
| 🟡 | [`eddiebe147/claude-settings@ad-copy-writer`](https://skills.sh/eddiebe147/claude-settings/ad-copy-writer) | 55 | Ad copywriting for multiple platforms. | Write Lazada/Shopee ad copy and product descriptions. |
| 🟡 | [`borghei/claude-skills@paid-ads`](https://skills.sh/borghei/claude-skills/paid-ads) | 24 | Paid advertising strategy and execution. | General paid ads expertise. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@marketplace-advertising`](https://skills.sh/finsilabs/awesome-ecommerce-skills/marketplace-advertising) | 12 | Marketplace-specific advertising (sponsored products, display ads). | **Lazada/Shopee sponsored product optimization.** |
| 🟡 | [`nicepkg/ai-workflow@ad-copy-generator`](https://skills.sh/nicepkg/ai-workflow/ad-copy-generator) | 20 | AI-powered ad copy generation workflows. | Rapid ad copy production for multiple products. |
| 🟢 | [`dengineproblem/agents-monorepo@influencer-marketing`](https://skills.sh/dengineproblem/agents-monorepo/influencer-marketing) | 67 | Influencer marketing strategy and outreach. | For KOL campaigns on TikTok/IG later. |
| 🟢 | [`eliasmalmsandberg/google-ads-skills@google-ads-audit-ecommerce`](https://skills.sh/eliasmalmsandberg/google-ads-skills/google-ads-audit-ecommerce) | 16 | Google Ads audit for e-commerce. | If you run Google Shopping ads. |

**Install Command (Top Picks):**
```bash
npx skills add anthropics/knowledge-work-plugins --skill campaign-plan
npx skills add finsilabs/awesome-ecommerce-skills --skill tiktok-ads-integration
npx skills add finsilabs/awesome-ecommerce-skills --skill marketplace-advertising
npx skills add karausab590-ops/clawads-marketing-skills --skill tiktok-dropshipping-ad-scripts
```

---

## 6. 🤖 Customer Service & Automation

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🟡 | [`travisjneuman/.claude@customer-success`](https://skills.sh/travisjneuman/.claude/customer-success) | 40 | Customer success management workflows. | Handle post-sale customer satisfaction. |
| 🟡 | [`caebixus/ai-customer-service-chatbot@chaterimo`](https://skills.sh/caebixus/ai-customer-service-chatbot/chaterimo) | 8 | AI customer service chatbot framework. | Automate common Lazada/Shopee chat inquiries. |
| 🟡 | [`githamza0206/simba@customer-service-expert`](https://skills.sh/githamza0206/simba/customer-service-expert) | 7 | Customer service expertise persona. | Handle escalations and complex customer issues. |
| 🟡 | [`eronred/aso-skills@review-management`](https://skills.sh/eronred/aso-skills/review-management) | 466 | Review management and response templates. | **Critical for Lazada/Shopee** where ratings drive visibility. |
| 🟢 | [`tendtoyj/tendtoyj-claude-skills@voice-of-customer`](https://skills.sh/tendtoyj/tendtoyj-claude-skills/voice-of-customer) | 5 | Voice of Customer analysis from feedback/reviews. | Analyze product reviews for improvement opportunities. |
| 🟢 | [`guia-matthieu/clawfu-skills@reputation-recovery`](https://skills.sh/guia-matthieu/clawfu-skills/reputation-recovery) | 35 | Reputation recovery and crisis management. | If you get a wave of negative reviews. |

**Install Command (Top Picks):**
```bash
npx skills add eronred/aso-skills --skill review-management
npx skills add caebixus/ai-customer-service-chatbot --skill chaterimo
```

---

## 7. 📦 Order Management, Fulfillment & Logistics

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🟡 | [`finsilabs/awesome-ecommerce-skills@order-management-system`](https://skills.sh/finsilabs/awesome-ecommerce-skills/order-management-system) | 12 | Order management workflows, status tracking, exception handling. | Central order management across 3 channels. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@order-fulfillment-workflow`](https://skills.sh/finsilabs/awesome-ecommerce-skills/order-fulfillment-workflow) | 8 | Order fulfillment automation — routing, tracking, returns. | Automate CJ Dropshipping order forwarding. |
| 🟡 | [`shopmeskills/mcp@logistics-tracking`](https://skills.sh/shopmeskills/mcp/logistics-tracking) | 8 | MCP server for logistics tracking. | Track CJ Dropshipping shipments. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@inventory-tracking`](https://skills.sh/finsilabs/awesome-ecommerce-skills/inventory-tracking) | 13 | Real-time inventory tracking and sync. | Prevent overselling across Lazada/Shopee/TikTok. |
| 🟢 | [`vtexdocs/ai-skills@marketplace-fulfillment`](https://skills.sh/vtexdocs/ai-skills/marketplace-fulfillment) | 38 | VTEX marketplace fulfillment. | Framework reference for fulfillment logic. |
| 🟢 | [`finsilabs/awesome-ecommerce-skills@international-shipping`](https://skills.sh/finsilabs/awesome-ecommerce-skills/international-shipping) | 16 | International shipping logistics. | For cross-border shipping optimization (China→Thailand). |
| 🟢 | [`rytass/utils@logistics-adapters`](https://skills.sh/rytass/utils/logistics-adapters) | 10 | Logistics API adapters. | Integration helpers for shipping carriers. |

**Install Command (Top Picks):**
```bash
npx skills add finsilabs/awesome-ecommerce-skills --skill order-management-system
npx skills add finsilabs/awesome-ecommerce-skills --skill order-fulfillment-workflow
npx skills add finsilabs/awesome-ecommerce-skills --skill inventory-tracking
npx skills add shopmeskills/mcp --skill logistics-tracking
```

---

## 8. ✍️ Product Listing & Content Optimization

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🔴 | [`vos91/agent-skills@ecommerce-copywriting`](https://skills.sh/vos91/agent-skills/ecommerce-copywriting) | 82 | **E-commerce copywriting** — product titles, descriptions, bullet points optimized for conversion. | Write Lazada/Shopee listings that convert. |
| 🔴 | [`affilino/ecommerce-seo-audit-skill@ecommerce-seo-audit`](https://skills.sh/affilino/ecommerce-seo-audit-skill/ecommerce-seo-audit) | 378 | E-commerce SEO audit — product page optimization, category structure, technical SEO. | **Optimize listings for Lazada/Shopee search algorithm.** |
| 🟡 | [`eddiebe147/claude-settings@product-description-writer`](https://skills.sh/eddiebe147/claude-settings/product-description-writer) | 48 | Product description writing persona. | Generate Thai product descriptions at scale. |
| 🟡 | [`nexscope-ai/amazon-skills@amazon-listing-optimization`](https://skills.sh/nexscope-ai/amazon-skills/amazon-listing-optimization) | 21 | Listing optimization methodology (Amazon-focused but principles apply). | Adapt listing optimization framework to Lazada/Shopee. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@ecommerce-seo`](https://skills.sh/finsilabs/awesome-ecommerce-skills/ecommerce-seo) | 10 | E-commerce SEO strategies and implementation. | SEO for marketplace listings. |
| 🟡 | [`inference-sh/agent-skills@product-photography`](https://skills.sh/inference-sh/agent-skills/product-photography) | 21 | AI product photography generation. | Generate/enhance product images from CJ supplier photos. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@product-content-enrichment`](https://skills.sh/finsilabs/awesome-ecommerce-skills/product-content-enrichment) | 7 | Enrich product content with additional attributes and descriptions. | Improve thin CJ product descriptions. |
| 🟢 | [`wesleysmits/agent-skills@writing-product-descriptions`](https://skills.sh/wesleysmits/agent-skills/writing-product-descriptions) | 17 | Product description writing framework. | Alternative description generator. |

**Install Command (Top Picks):**
```bash
npx skills add vos91/agent-skills --skill ecommerce-copywriting
npx skills add affilino/ecommerce-seo-audit-skill --skill ecommerce-seo-audit
npx skills add inference-sh/agent-skills --skill product-photography
npx skills add finsilabs/awesome-ecommerce-skills --skill product-content-enrichment
```

---

## 9. 📱 Social Media & Content Marketing

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🟡 | [`inferen-sh/skills@ai-social-media-content`](https://skills.sh/inferen-sh/skills/ai-social-media-content) | 8,500 | **#1 most-installed social skill.** AI social media content generation. | Generate TikTok/IG/FB content for product promotion. |
| 🟡 | [`dengineproblem/agents-monorepo@social-media-marketing`](https://skills.sh/dengineproblem/agents-monorepo/social-media-marketing) | 602 | Social media marketing strategy and execution. | Full social marketing playbook. |
| 🟡 | [`sanky369/vibe-building-skills@social-graphics`](https://skills.sh/sanky369/vibe-building-skills/social-graphics) | 224 | Social media graphics generation. | Product promo graphics for social. |
| 🟡 | [`nexscope-ai/ecommerce-skills@ecommerce-content-marketing`](https://skills.sh/nexscope-ai/ecommerce-skills/ecommerce-content-marketing) | 13 | Content marketing strategy for e-commerce. | Content marketing plan for FT Dropshipping brand. |
| 🟢 | [`skills.volces.com@tiktok-live-commerce`](https://skills.sh/skills.volces.com/tiktok-live-commerce) | 8 | TikTok live commerce strategies. | TikTok Live selling tactics. |
| 🟢 | [`vivy-yi/xiaohongshu-skills@kol-collaboration`](https://skills.sh/vivy-yi/xiaohongshu-skills/kol-collaboration) | 20 | KOL collaboration workflows. | Influencer partnership framework for TikTok/IG. |

**Already Installed:** `social-content` custom skill ✅

**Install Command (Top Picks):**
```bash
npx skills add inferen-sh/skills --skill ai-social-media-content
npx skills add dengineproblem/agents-monorepo --skill social-media-marketing
npx skills add sanky369/vibe-building-skills --skill social-graphics
```

---

## 10. 💹 Accounting, Finance & Business Intelligence

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🟡 | [`jeffreydebolt/ecom-cfo-skill@ecommerce-cfo`](https://skills.sh/jeffreydebolt/ecom-cfo-skill/ecommerce-cfo) | 18 | **E-commerce CFO** — P&L, cash flow, margin analysis, financial planning for e-commerce. | **Purpose-built** for your financial management. |
| 🟡 | [`whawkinsiv/claude-code-skills@accounting`](https://skills.sh/whawkinsiv/claude-code-skills/accounting) | 149 | Accounting expertise and bookkeeping. | General accounting for FT Dropshipping. |
| 🟡 | [`jk-0001/skills@bookkeeping-basics`](https://skills.sh/jk-0001/skills/bookkeeping-basics) | 63 | Bookkeeping fundamentals and workflows. | Track income/expenses across 3 channels. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@ecommerce-budgeting-forecasting`](https://skills.sh/finsilabs/awesome-ecommerce-skills/ecommerce-budgeting-forecasting) | 8 | E-commerce budgeting and revenue forecasting. | Forecast monthly revenue and plan inventory. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@financial-reporting-dashboard`](https://skills.sh/finsilabs/awesome-ecommerce-skills/financial-reporting-dashboard) | 9 | Financial reporting and dashboard creation. | Build your P&L dashboard. |
| 🟡 | [`finsilabs/awesome-ecommerce-skills@marketplace-fee-reconciliation`](https://skills.sh/finsilabs/awesome-ecommerce-skills/marketplace-fee-reconciliation) | 9 | **Marketplace fee reconciliation** — commissions, shipping subsidies, penalties. | **Critical.** Lazada/Shopee fees are complex and eat margins. |
| 🟡 | [`eachlabs/skills@invoice-generation`](https://skills.sh/eachlabs/skills/invoice-generation) | 49 | Invoice generation and management. | Generate invoices and tax documents. |
| 🟢 | [`vasilyu1983/ai-agents-public@startup-finance-ops`](https://skills.sh/vasilyu1983/ai-agents-public/startup-finance-ops) | 19 | Startup financial operations. | General startup finance playbook. |
| 🟢 | [`membranedev/application-skills@google-sheets`](https://skills.sh/membranedev/application-skills/google-sheets) | 263 | Google Sheets automation and integration. | Automate financial tracking spreadsheets. |

**Install Command (Top Picks):**
```bash
npx skills add jeffreydebolt/ecom-cfo-skill --skill ecommerce-cfo
npx skills add finsilabs/awesome-ecommerce-skills --skill marketplace-fee-reconciliation
npx skills add finsilabs/awesome-ecommerce-skills --skill ecommerce-budgeting-forecasting
npx skills add finsilabs/awesome-ecommerce-skills --skill financial-reporting-dashboard
```

---

## 11. 🌐 Localization, Translation & Thai-Specific

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🟡 | [`nxdus/thai-interpreter@thai-interpreter`](https://skills.sh/nxdus/thai-interpreter/thai-interpreter) | 29 | Thai language interpretation and translation. | Translate CJ product descriptions CN→TH. |
| 🟡 | [`kostja94/marketing-skills@translation`](https://skills.sh/kostja94/marketing-skills/translation) | 281 | Marketing translation — maintaining brand voice across languages. | Translate marketing content while keeping it natural in Thai. |
| 🟡 | [`kostja94/marketing-skills@localization-strategy`](https://skills.sh/kostja94/marketing-skills/localization-strategy) | 256 | Localization strategy for different markets. | Thai market localization of product messaging. |
| 🟡 | [`kaotypr/skills@kao-saas-sea-copywriting`](https://skills.sh/kaotypr/skills/kao-saas-sea-copywriting) | 4 | **Southeast Asia copywriting** — market-specific copy for SEA. | Thai/SEA market copywriting style. |
| 🟡 | [`abgne/line-dev@line-notification-message`](https://skills.sh/abgne/line-dev/line-notification-message) | 17 | **LINE notification messages.** | **LINE is Thailand's #1 messaging app.** Order notifications, customer follow-ups via LINE. |
| 🟢 | [`affaan-m/everything-claude-code@customs-trade-compliance`](https://skills.sh/affaan-m/everything-claude-code/customs-trade-compliance) | 836 | Customs and trade compliance. | For understanding Thai import regulations on Chinese goods. |

**Install Command (Top Picks):**
```bash
npx skills add kostja94/marketing-skills --skill translation
npx skills add kostja94/marketing-skills --skill localization-strategy
npx skills add abgne/line-dev --skill line-notification-message
npx skills add nxdus/thai-interpreter --skill thai-interpreter
```

---

## 12. 🔧 Web Scraping, Data & Automation Infrastructure

| Priority | Skill | Installs | What It Does | FT Dropshipping Fit |
|----------|-------|----------|--------------|---------------------|
| 🟡 | [`apify/agent-skills@apify-ultimate-scraper`](https://skills.sh/apify/agent-skills/apify-ultimate-scraper) | 4,700 | Universal web scraper — any website, structured data extraction. | Scrape any Lazada/Shopee/TikTok page for data. |
| 🟡 | [`alphaonedev/openclaw-graph@playwright-scraper`](https://skills.sh/alphaonedev/openclaw-graph/playwright-scraper) | 966 | Playwright-based scraping for JS-heavy sites. | Scrape dynamic marketplace pages. |
| 🟡 | [`eddiebe147/claude-settings@automation-architect`](https://skills.sh/eddiebe147/claude-settings/automation-architect) | 50 | Automation architecture design. | Design end-to-end automation pipelines. |
| 🟡 | [`membranedev/application-skills@google-sheets`](https://skills.sh/membranedev/application-skills/google-sheets) | 263 | Google Sheets read/write/automation. | Financial tracking, inventory sheets. |
| 🟡 | [`claude-office-skills/skills@crm-automation`](https://skills.sh/claude-office-skills/skills/crm-automation) | 542 | CRM automation — customer data, follow-ups, pipeline. | Track repeat customers and purchase patterns. |
| 🟢 | [`jk-0001/skills@spreadsheet-automation`](https://skills.sh/jk-0001/skills/spreadsheet-automation) | 10 | Spreadsheet automation workflows. | Automate report generation. |

**Install Command (Top Picks):**
```bash
npx skills add apify/agent-skills --skill apify-ultimate-scraper
npx skills add membranedev/application-skills --skill google-sheets
npx skills add claude-office-skills/skills --skill crm-automation
```

---

## 🎯 Recommended Installation Priority

### Phase 1: Launch Foundation (Install Now) — 🔴 CRITICAL
These are the skills you need before your first sale:

```bash
# Product Research & Sourcing
npx skills add aahl/skills --skill maishou
npx skills add shopmeskills/mcp --skill cn-ecommerce-search
npx skills add apify/agent-skills --skill apify-ecommerce

# Listings & Content
npx skills add vos91/agent-skills --skill ecommerce-copywriting
npx skills add affilino/ecommerce-seo-audit-skill --skill ecommerce-seo-audit

# Pricing
npx skills add eddiebe147/claude-settings --skill pricing-strategist

# Campaign Planning
npx skills add anthropics/knowledge-work-plugins --skill campaign-plan
```

**Total Phase 1: 7 skills**

### Phase 2: Growth Engine (First Month) — 🟡 HIGH
Once you have products listed and first sales coming in:

```bash
# Competitor Intel
npx skills add buluslan/ecommerce-competitor-analyzer --skill ecommerce-competitor-analyzer
npx skills add guia-matthieu/clawfu-skills --skill competitor-monitor

# Channel-Specific
npx skills add quantmind-br/skills --skill shopee
npx skills add finsilabs/awesome-ecommerce-skills --skill tiktok-shop-integration
npx skills add finsilabs/awesome-ecommerce-skills --skill tiktok-ads-integration
npx skills add finsilabs/awesome-ecommerce-skills --skill marketplace-advertising

# Operations
npx skills add finsilabs/awesome-ecommerce-skills --skill order-management-system
npx skills add finsilabs/awesome-ecommerce-skills --skill inventory-tracking
npx skills add finsilabs/awesome-ecommerce-skills --skill dropshipping-integration

# Finance
npx skills add jeffreydebolt/ecom-cfo-skill --skill ecommerce-cfo
npx skills add finsilabs/awesome-ecommerce-skills --skill marketplace-fee-reconciliation
npx skills add finsilabs/awesome-ecommerce-skills --skill profit-margin-analysis

# Localization
npx skills add kostja94/marketing-skills --skill translation
npx skills add abgne/line-dev --skill line-notification-message

# Customer Management
npx skills add eronred/aso-skills --skill review-management
```

**Total Phase 2: 16 skills**

### Phase 3: Scale & Optimize (Month 2+) — 🟢 NICE-TO-HAVE
When you're doing 50+ orders/day and need to scale:

```bash
npx skills add inferen-sh/skills --skill ai-social-media-content
npx skills add dengineproblem/agents-monorepo --skill social-media-marketing
npx skills add dengineproblem/agents-monorepo --skill influencer-marketing
npx skills add apify/agent-skills --skill apify-ultimate-scraper
npx skills add membranedev/application-skills --skill google-sheets
npx skills add claude-office-skills/skills --skill crm-automation
npx skills add finsilabs/awesome-ecommerce-skills --skill ecommerce-budgeting-forecasting
npx skills add karausab590-ops/clawads-marketing-skills --skill tiktok-dropshipping-ad-scripts
npx skills add inference-sh/agent-skills --skill product-photography
```

**Total Phase 3: 9 skills**

---

## 📋 Key Ecosystem: finsilabs/awesome-ecommerce-skills

This collection is the **most comprehensive e-commerce skill suite** discovered. All skills found from this repo:

| Skill | Installs | Category |
|-------|----------|----------|
| `tiktok-shop-integration` | 28 | Channel |
| `international-shipping` | 16 | Logistics |
| `tiktok-ads-integration` | 15 | Ads |
| `inventory-tracking` | 13 | Operations |
| `order-management-system` | 12 | Operations |
| `profit-margin-analysis` | 12 | Finance |
| `marketplace-advertising` | 12 | Ads |
| `dropshipping-integration` | 11 | Dropshipping |
| `ecommerce-seo` | 10 | SEO |
| `financial-reporting-dashboard` | 9 | Finance |
| `marketplace-fee-reconciliation` | 9 | Finance |
| `order-fulfillment-workflow` | 8 | Operations |
| `ecommerce-budgeting-forecasting` | 8 | Finance |
| `product-content-enrichment` | 7 | Content |
| `dynamic-pricing` | 6 | Pricing |

**Recommendation:** Install the entire finsilabs suite — it's like an ERP in skill form.

---

## 🔍 Gap Analysis: What's Missing

Skills that **don't exist yet** but FT Dropshipping needs (candidates for custom skills via SKILL-CREATOR):

| Gap | Why It Matters | Recommended Action |
|-----|---------------|-------------------|
| **Lazada-specific skill** | No Lazada equivalent of the Shopee skill exists | Build custom skill using Lazada Seller Center API |
| **Thai VAT / tax compliance** | Thai e-commerce tax rules (VAT 7%, withholding tax) | Build custom skill with Thai Revenue Dept rules |
| **Lazada/Shopee fee calculator** | Real-time commission + shipping fee calculation per platform | Build custom skill with fee matrices |
| **CJ Dropshipping integration** | Direct CJ API for order forwarding, tracking, inventory | Build custom MCP server for CJ API |
| **Thai marketplace chat templates** | Pre-built Thai customer service replies for common Lazada/Shopee questions | Build custom skill with Thai templates |
| **Songkran / Thai holiday campaign planner** | Thai-specific promotional calendar (11.11, 12.12, Songkran, New Year) | Build custom skill with Thai retail calendar |
| **PromptPay / Thai payment tracking** | Reconcile PromptPay and Thai bank transfers | Build custom integration |

---

## 📊 Summary Statistics

| Metric | Count |
|--------|-------|
| Total skills discovered | 78 |
| 🔴 Critical (install now) | 7 |
| 🟡 High priority (first month) | 16 |
| 🟢 Nice-to-have (scaling) | 9 |
| Custom skills to build | 7 |
| Categories covered | 12 |
| Already installed (overlapping) | 3 (social-content, seo-content-writer, on-page-seo-auditor) |

---

*Generated by Monie for FT Dropshipping — April 3, 2026*
