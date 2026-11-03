# Marvyn for Claude

Your AI marketing team, inside Claude. Marvyn connects your ad accounts, Google Search Console, Google Analytics, your Shopify store, social accounts and site behaviour data, keeps them in sync, watches them around the clock, and lets Claude read them and act on them.

## Ads (Meta, Google, Reddit, X)

- Campaign, ad set, ad and creative performance, spend pacing, search terms, audiences, placements
- Build campaigns on Meta, Google and Reddit: objective, budget, audiences, placements, creative and copy
- Build custom audiences; pause or resume campaigns and ads; apply Marvyn's recommendations
- Creative fatigue, budget allocation, bid strategy and account audits

## SEO and AI search

- Search Console clicks, impressions, queries and pages; indexing, sitemaps and branded vs non-branded traffic
- Keyword research, rankings, competitors, backlinks and domain authority
- Site audits and on-page issues; local SEO rank grids
- AI visibility: whether ChatGPT and other AI answers mention and cite your brand
- Draft SEO articles into Marvyn for you to review and publish

## Store and analytics

- Shopify orders, revenue, products, customers, checkouts, refunds and returns
- Google Analytics traffic, channels, landing pages, events, funnels, devices and countries
- Microsoft Clarity site behaviour; Marvyn pixel conversions and tracking health

## Social

- Instagram and Facebook account growth, posts and engagement

## Thinking and watching

- Investigates "why did this change?" across every source at once
- 24/7 watch: spend runaways, ads that stopped, conversions that dropped, disabled accounts
- Ranked recommendations and a marketing strategy grounded in your own numbers
- 40+ expert playbooks (account audits, creative testing, CRO, attribution, launch checklists and more)

## You stay in control

Nothing goes live, changes or spends money until you approve it. Every campaign, pause, audience, article or tracking change Claude prepares becomes a card in Marvyn, and you approve it either way:

- **In the chat:** Claude shows you exactly what will happen (daily budget, audience, every ad's text and links, and whether it goes live) and asks. Say yes and Marvyn makes the change, with the same checks as the Approve button.
- **In Marvyn:** open the card and click Approve.

## Setup

You need a Marvyn account (https://www.marvyn.io).

**claude.ai and Cowork**

1. Add the Marvyn plugin from the Claude directory.
2. On the plugin's **Connectors** tab, connect Marvyn, sign in and click **Allow**.

**Claude Code**

1. Run `/plugin install marvyn --marketplace elevensquarelabs-prog/marvyn-claude-plugin`.
2. Run `/mcp`, pick Marvyn, sign in and click **Allow**.

Then try: "Why did sales drop last week?", "Which search queries should we write about next?" or "Launch a Meta campaign for our new product, $30 a day, US" (Claude shows you everything, then launches when you say yes).

What Claude can read follows your Marvyn plan and the sources you connected. Disconnect any time in Marvyn under **Settings → Account → Connected AI assistants**.

## What the plugin contains and what data it sends

- One skill (`marvyn-marketing`) that tells Claude which Marvyn tools to use and how to ask for your approval. It runs no code.
- One connector: Marvyn's remote server at `https://www.marvyn.io/mcp`, signed in with your own Marvyn account (OAuth). The plugin talks to no other service.
- Claude sends Marvyn only what each tool needs: what to look up (dates, metrics, campaigns) and the details of changes you ask for (budgets, audiences, ad text, article drafts). Marvyn returns figures from the accounts you connected to Marvyn. Marvyn logs which tool was called and when, not your prompts or Claude's answers.
- The plugin stores nothing on your computer and holds no keys or passwords.

## Links

- Website: https://www.marvyn.io
- Privacy: https://www.marvyn.io/privacy-policy#ai-assistants
- Support: dev@marvyn.io
