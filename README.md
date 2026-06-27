# Awesome MCP Servers for Sales Automation

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A curated list of Model Context Protocol (MCP) servers specifically designed for sales automation, LinkedIn outreach, lead generation, and B2B growth.

---

## 📖 Contents

- [Why This List?](#-why-this-list)
- [Categories](#-categories)
  - [LinkedIn & Social Outreach](#1-linkedin--social-outreach)
  - [Email Automation](#2-email-automation)
  - [Lead Generation & Enrichment](#3-lead-generation--enrichment)
  - [CRM Integrations](#4-crm-integrations-hubspot-salesforce-etc)
  - [Web Scraping & Prospecting](#5-web-scraping--prospecting)
  - [Workflow Automation](#6-workflow-automation-n8n-make-zapier-mcps)
  - [AI Sales Agents & Copilots](#7-ai-sales-agents--copilots)
  - [WhatsApp & Messaging Automation](#8-whatsapp--messaging-automation)
  - [Data Analytics & Reporting for Sales](#9-data-analytics--reporting-for-sales)
  - [Calendar & Meeting Scheduling](#10-calendar--meeting-scheduling)
- [🔁 Loop Engineering for Sales Automation](#-loop-engineering-for-sales-automation)
- [🤝 Contribution Welcome](#-contribution-welcome)
- [📄 License](#-license)

---

## 💡 Why This List?

Sales stacks are traditionally fragmented, requiring custom scripts, heavy APIs, and complex integration platforms (like iPaaS) to keep systems in sync. 

**Model Context Protocol (MCP)** is a game-changer. Developed by Anthropic, MCP is an open standard that allows Large Language Models (LLMs) and AI agents (like Claude Desktop, Cursor, and Windsurf) to securely connect directly to external tools, databases, and APIs. 

Instead of writing custom code for every combination of AI agent and sales tool, MCP servers act as reusable, standardized adapters. By pointing an AI agent to an MCP server, you instantly grant it the ability to search CRMs, enrich leads, scrap prospects, send emails, and run automated workflows. This curated list gathers the best MCP servers to help you build autonomous, high-performing AI sales agents.

---

## 🗂️ Categories

### 1. LinkedIn & Social Outreach

- [linkedin-mcp (southleft)](https://github.com/southleft/linkedin-mcp) - Focuses on AI-powered analytics, content creation, and engagement automation. ⭐
- [linkedin-mcp-server (stickerdaniel)](https://github.com/stickerdaniel/linkedin-mcp-server) - Open-source server that allows AI assistants to read LinkedIn data through a logged-in browser session.
- [linkedin-mcp-server (eliasbiondo)](https://github.com/eliasbiondo/linkedin-mcp-server) - FastMCP-based server designed for searching people, companies, and jobs.
- [twitter-mcp (EnesCinr)](https://github.com/EnesCinr/twitter-mcp) - MCP server for posting tweets and searching Twitter (X).
- [x-mcp-server (DataWhisker)](https://github.com/DataWhisker/x-mcp-server) - Exposes 16+ tools including media uploads, engagement actions, and profile lookups on X.
- [Xquik MCP Server](https://github.com/Xquik-dev/x-twitter-scraper) - Authenticated remote MCP server for X search, profile lookup, media downloads, webhooks, and write actions.
- [reddit-mcp-server (jordanburke)](https://github.com/jordanburke/reddit-mcp-server) - Full Read/Write Reddit integration with spam protection and anonymous browsing mode.
- [reddit-mcp (Arindam200)](https://github.com/Arindam200/reddit-mcp) - Focuses on Reddit engagement metrics, subreddit statistics, and growth pattern analysis.
- [linkedin-mcp-server (Dishant27)](https://github.com/Dishant27/linkedin-mcp-server) - Integrates LinkedIn's API for profile data fetching and sharing updates.
- [linkedin_mcp (Rayyan9477)](https://github.com/Rayyan9477/linkedin_mcp) - Focused on job searching, resume/cover letter generation, and job application management.

### 2. Email Automation

- [gmail-mcp (shinzo-labs)](https://github.com/shinzo-labs/gmail-mcp) - Offers comprehensive Gmail API coverage, including settings management and labels.
- [resend-mcp (resend)](https://github.com/resend/resend-mcp) - Official Resend MCP server for sending emails and managing domains/contacts. ⭐
- [outlook-mcp (ryaker)](https://github.com/ryaker/outlook-mcp) - Connects AI agents to Microsoft 365 Outlook using the Microsoft Graph API.
- [outlook-desktop-mcp (Aanerud)](https://github.com/Aanerud/outlook-desktop-mcp) - Local MCP server interacting directly with Outlook Desktop app via COM or AppleScript.
- [outlook-assistant (littlebearapps)](https://github.com/littlebearapps/outlook-assistant) - Managing email, calendar, and contacts directly from AI conversations.
- [email-mcp (codefuturist)](https://github.com/codefuturist/email-mcp) - IMAP/SMTP email server supporting multi-account management, scheduling, and AI triage. ⭐
- [Gmail-MCP-Server (GongRzhe)](https://github.com/GongRzhe/Gmail-MCP-Server) - Lightweight Gmail server featuring automatic authentication for Claude Desktop.
- [better-email-mcp (n24q02m)](https://github.com/n24q02m/better-email-mcp) - Node.js-based IMAP/SMTP server supporting App Passwords and auto-discovery for major email providers.
- [inbox-zero (elie222)](https://github.com/elie222/inbox-zero) - Gmail integration adding inbox categorization, response suggestions, and follow-up tracking.
- [google_workspace_mcp (taylorwilsdon)](https://github.com/taylorwilsdon/google_workspace_mcp) - Comprehensive Google Workspace integration with support for Calendar, Drive, Gmail, Docs, Sheets, and Chats.
### 3. Lead Generation & Enrichment

- [vibeprospecting-mcp (explorium-ai)](https://github.com/explorium-ai/vibeprospecting-mcp) - Remote B2B data access server for compiling lists, researching companies, and enriching contacts.

### 4. CRM Integrations (HubSpot, Salesforce, etc.)

- [mcp-server-salesforce (tsmztech)](https://github.com/tsmztech/mcp-server-salesforce) - Focuses on integrating Claude with Salesforce for querying and managing records.
- [odoo-mcp-pro (pantalytics)](https://github.com/pantalytics/odoo-mcp-pro) - Highly active repository designed as an AI connector for Odoo ERP data.
- [MCP-Salesforce (smn2gnt)](https://github.com/smn2gnt/MCP-Salesforce) - Connector allowing LLMs to interact with Salesforce via SOQL and SOSL queries.
- [twenty-crm-mcp-server (mhenry3164)](https://github.com/mhenry3164/twenty-crm-mcp-server) - Open-source Twenty CRM client featuring CRUD operations, search, and schema discovery.
- [salesforce-mcp-server (kablewy)](https://github.com/kablewy/salesforce-mcp-server) - TypeScript implementation using jsforce for CRM record search, queries, and metadata retrieval.
- [hubspot-mcp (shinzo-labs)](https://github.com/shinzo-labs/hubspot-mcp) - Access and manage HubSpot CRM contacts, companies, deals, and associations.
- [pipedrive-mcp-server (WillDent)](https://github.com/WillDent/pipedrive-mcp-server) - Connects to Pipedrive API v2 to expose CRM pipelines, deals, and filters.
- [Skill_Seekers (yusufkaraaslan)](https://github.com/yusufkaraaslan/Skill_Seekers) - Transforms 17 source types (docs, repos, PDFs, Slack/Discord) into AI skills and RAG knowledge with 35 MCP tools.
### 5. Web Scraping & Prospecting

- [firecrawl-mcp-server (firecrawl)](https://github.com/firecrawl/firecrawl-mcp-server) - Official Firecrawl MCP server for web scraping, crawling, and search. ⭐
- [playwright-mcp (microsoft)](https://github.com/microsoft/playwright-mcp) - Official Playwright MCP server for browser automation and scraping. ⭐
- [exa-mcp-server (exa-labs)](https://github.com/exa-labs/exa-mcp-server) - Official Exa MCP server for advanced AI-native web search, crawls, and LinkedIn/company search. ⭐
- [tavily-mcp (tavily-ai)](https://github.com/tavily-ai/tavily-mcp) - Official Tavily MCP server for real-time web search and LLM-optimized scraping. ⭐
- [scrapegraph-mcp (ScrapeGraphAI)](https://github.com/ScrapeGraphAI/scrapegraph-mcp) - Integrates ScrapeGraphAI's API, offering enterprise-grade AI-powered scraping capabilities. ⭐
- [real-browser-mcp (ofershap)](https://github.com/ofershap/real-browser-mcp) - Controls users' active Chrome/Firefox sessions to preserve cookies, sessions, and logins.
- [auth-fetch-mcp (ymw0407)](https://github.com/ymw0407/auth-fetch-mcp) - Opens local browser instances to capture and cache sessions for login-protected pages.
- [scrapeless-mcp-server (scrapeless-ai)](https://github.com/scrapeless-ai/scrapeless-mcp-server) - Official Scrapeless MCP server for browser automation, dynamic site scraping, and Google Trend/SERP searches.
- [mcp-playwright (executeautomation)](https://github.com/executeautomation/mcp-playwright) - Playwright-based browser automation server for web navigation and data extraction.
- [mobile-mcp (mobile-next)](https://github.com/mobile-next/mobile-mcp) - MCP server for iOS and Android application/device automation, emulator control, and mobile app scraping.
- [mcp-server-browserbase (browserbase)](https://github.com/browserbase/mcp-server-browserbase) - Automate web navigation, cloud browser control, data extraction, and form filling.
- [webclaw (0xMassi)](https://github.com/0xMassi/webclaw) - Optimized web extraction and scraper client designed to bypass bot protection and reduce token usage.
- [terminator (mediar-ai)](https://github.com/mediar-ai/terminator) - Desktop GUI automation server using accessibility APIs to control native desktop applications.
### 6. Workflow Automation (n8n, Make, Zapier MCPs)

- [zapier-mcp (zapier)](https://github.com/zapier/zapier-mcp) - Official Zapier MCP server to connect AI agents to 9,000+ apps. ⭐
- [n8n-mcp (czlonkowski)](https://github.com/czlonkowski/n8n-mcp) - n8n integration for accessing node docs, properties, and workflow building.
- [n8n-mcp-server (leonardsellem)](https://github.com/leonardsellem/n8n-mcp-server) - Community-maintained MCP server designed to manage and control n8n workflows and executions.
- [activepieces (activepieces)](https://github.com/activepieces/activepieces) - Turn Activepieces automated workflows into MCP-compatible tools for AI agents.
- [n8n-nodes-mcp (nerding-io)](https://github.com/nerding-io/n8n-nodes-mcp) - Community node enabling n8n workflows to act as an MCP client connecting to external tools.
- [mcp-n8n-builder (spences10)](https://github.com/spences10/mcp-n8n-builder) - Specialized builder for programmatic n8n workflow construction and deployment.
- [pipedream (PipedreamHQ)](https://github.com/PipedreamHQ/pipedream/tree/master/modelcontextprotocol) - Seamless bridge to Pipedream's 2,500+ prebuilt APIs and 8,000+ developer actions. ⭐
- [workflows-mcp-server (cyanheads)](https://github.com/cyanheads/workflows-mcp-server) - YAML-based workflow playbook storage and query server.
- [agent-device (callstackincubator)](https://github.com/callstackincubator/agent-device) - Discovery router and installer CLI for running mobile and desktop automation workflows.
### 7. AI Sales Agents & Copilots

- [mcp-agent (lastmile-ai)](https://github.com/lastmile-ai/mcp-agent) - Python framework for building AI agents with Model Context Protocol using composable workflows. ⭐
- [b2b-sdr-agent-template (iPythoning)](https://github.com/iPythoning/b2b-sdr-agent-template) - Open-source AI SDR template for multi-channel lead generation workflows.
- [gtm-engineer-playbook (Othmane-Khadri)](https://github.com/Othmane-Khadri/gtm-engineer-playbook) - Various Claude Code skills for ICP building, signal scanning, and lead scoring.
- [langsmith-mcp-server (langchain-ai)](https://github.com/langchain-ai/langsmith-mcp-server) - Integrates LangSmith tracing and observability tools into MCP-compliant workflows.
- [amazon_sp_mcp (jay-trivedi)](https://github.com/jay-trivedi/amazon_sp_mcp) - Exposes Amazon Selling Partner API to query product listings, sales, orders, and inventory data.

### 8. WhatsApp & Messaging Automation

- [whatsapp-mcp (lharries)](https://github.com/lharries/whatsapp-mcp) - Go-based bridge connecting to WhatsApp Web with a Python MCP server. ⭐
- [mac_messages_mcp (carterlasalle)](https://github.com/carterlasalle/mac_messages_mcp) - Accesses local macOS iMessage databases for analyzing history, managing contacts, and sending messages. ⭐
- [telegram-mcp (chaindead)](https://github.com/chaindead/telegram-mcp) - Telegram MTProto API client for reading chats, managing groups, and retrieving histories.
- [discord-mcp (SaseQ)](https://github.com/SaseQ/discord-mcp) - Connects AI agents to Discord channels, servers, and messaging using the Java Discord API.
- [slack-mcp-server (korotovsky)](https://github.com/korotovsky/slack-mcp-server) - Integrates Slack direct messages, channels, and apps with smart history retrieval.
- [whatsapp-mcp (felipeadeildo)](https://github.com/felipeadeildo/whatsapp-mcp) - SQLite-backed WhatsApp bridge allowing AI assistants to read, search, and send messages.

### 9. Data Analytics & Reporting for Sales

- [server-postgres (modelcontextprotocol)](https://github.com/modelcontextprotocol/servers) - Standard PostgreSQL MCP server for executing queries and schema discovery. ⭐
- [mcp-sqlite (jparkerweb)](https://github.com/jparkerweb/mcp-sqlite) - Comprehensive MCP server designed for SQLite database interaction.
- [mcp-clickhouse (ClickHouse)](https://github.com/ClickHouse/mcp-clickhouse) - Official ClickHouse database connector for querying enterprise analytics warehouses.
- [mcp-bigquery-server (ergut)](https://github.com/ergut/mcp-bigquery-server) - Google BigQuery server providing database schemas and querying capabilities.
- [mcp-gsheets (freema)](https://github.com/freema/mcp-gsheets) - Comprehensive Google Sheets API server for cell formatting, editing, and workbook management.
- [netdata (netdata)](https://github.com/netdata/netdata) - Performance tracking and system metrics analytics for observability, logs, and processes.
### 10. Calendar & Meeting Scheduling

- [mcp-google-workspace (j3k0)](https://github.com/j3k0/mcp-google-workspace) - Exposes Google Workspace APIs including Google Calendar and Gmail to AI agents.
- [ms-365-mcp-server (softeria)](https://github.com/softeria/ms-365-mcp-server) - Microsoft 365 Graph client managing Outlook Calendar bookings and Exchange mails.

---
## 🔁 Loop Engineering for Sales Automation

Instead of manually running MCP tools one by one, you can design a "loop" — an automated, scheduled system where an AI agent repeatedly triages leads, sends outreach, and escalates only when human judgment is needed. This approach shifts AI from a reactive helper to an active, continuous assistant. It ensures your pipeline stays full and active without requiring constant manual triggers.

| Loop Pattern | What It Automates | Suggested Cadence |
| :--- | :--- | :--- |
| Daily Lead Triage | Scrapes and scores new leads using MCP scraping + CRM servers | Daily |
| Outreach Sweeper | Sends connection requests and follow-ups via LinkedIn/Email MCP servers | Every 6-8 hours |
| Reply Watcher | Monitors chat threads, flags hot leads for human review | Continuous |
| Weekly Reporting | Pulls analytics from CRM/Sheets MCP servers into a summary | Weekly |

Inspired by loop engineering principles — see [Loop Engineering by Cobus Greyling](https://github.com/cobusgreyling/loop-engineering) for the general pattern.

---
## 🤝 Contribution Welcome

Contributions are welcome! Please read the [Contribution Guidelines](CONTRIBUTING.md) first.

If you know of any other MCP servers that fit well into any of these categories, please submit a Pull Request.

---

## 📄 License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
