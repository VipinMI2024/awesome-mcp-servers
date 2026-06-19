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
- [linkedin-mcp (FilippTrigub)](https://github.com/FilippTrigub/linkedin-mcp) - Python-based server for posting to LinkedIn with media attachments using official API.
- [linkedin-mcp-server (eliasbiondo)](https://github.com/eliasbiondo/linkedin-mcp-server) - FastMCP-based server designed for searching people, companies, and jobs.
- [twitter-mcp (EnesCinr)](https://github.com/EnesCinr/twitter-mcp) - MCP server for posting tweets and searching Twitter (X).
- [x-mcp-server (DataWhisker)](https://github.com/DataWhisker/x-mcp-server) - Exposes 16+ tools including media uploads, engagement actions, and profile lookups on X.
- [Xquik MCP Server](https://github.com/Xquik-dev/x-twitter-scraper) - Authenticated remote MCP server for X search, profile lookup, media downloads, webhooks, and write actions.
- [twitter-mcp-server (taazkareem)](https://github.com/taazkareem/twitter-mcp-server) - Built on the agent-twitter-client library, focusing on robust error handling and rate-limiting.
- [bsky-mcp-server (brianellin)](https://github.com/brianellin/bsky-mcp-server) - Connects to Bluesky and interacts with the AT Protocol for posting and fetching content.
- [bluesky-social-mcp (gwbischof)](https://github.com/gwbischof/bluesky-social-mcp) - Social interactions on Bluesky including following, muting, and timeline retrieval.
- [mcp-bluesky (pipeworx-io)](https://github.com/pipeworx-io/mcp-bluesky) - Searching posts, retrieving user profiles, and browsing feeds on Bluesky.
- [BlueSky-MCP (berlinbra)](https://github.com/berlinbra/BlueSky-MCP) - Implements a standardized interface for retrieving Bluesky profiles and social graph data.
- [bluesky-daily-mcp (briangershon)](https://github.com/briangershon/bluesky-daily-mcp) - Surfaces and summarizes daily topics and updates from Bluesky follows.

### 2. Email Automation

- [gmail-mcp (theposch)](https://github.com/theposch/gmail-mcp) - Feature-rich Python-based server for Gmail integration. ⭐
- [gmail-mcp (bastienchabal)](https://github.com/bastienchabal/gmail-mcp) - Supports both Gmail and Google Calendar workflows.
- [gmail-mcp (shinzo-labs)](https://github.com/shinzo-labs/gmail-mcp) - Offers comprehensive Gmail API coverage, including settings management and labels.
- [mcp-google-gmail (cablate)](https://github.com/cablate/mcp-google-gmail) - Focused on robust email management and search capabilities.
- [resend-mcp (resend)](https://github.com/resend/resend-mcp) - Official Resend MCP server for sending emails and managing domains/contacts. ⭐
- [outlook-mcp (ryaker)](https://github.com/ryaker/outlook-mcp) - Connects AI agents to Microsoft 365 Outlook using the Microsoft Graph API.
- [outlook-desktop-mcp (Aanerud)](https://github.com/Aanerud/outlook-desktop-mcp) - Local MCP server interacting directly with Outlook Desktop app via COM or AppleScript.
- [outlook-assistant (littlebearapps)](https://github.com/littlebearapps/outlook-assistant) - Managing email, calendar, and contacts directly from AI conversations.
- [office-365-mcp-server (hvkshetry)](https://github.com/hvkshetry/office-365-mcp-server) - Office 365 MCP server covering Outlook, Teams, OneDrive, and SharePoint.
- [sendgrid-mcp-server (recepyavuz0)](https://github.com/recepyavuz0/sendgrid-mcp-server) - Node.js-based MCP server to send transactional emails, manage templates, and fetch statistics.

### 3. Lead Generation & Enrichment

- [apollo-mcp (aisacAdmin)](https://github.com/aisacAdmin/apollo-mcp) - Comprehensive Apollo.io MCP server with contact management, enrichment, sequences, and deals. ⭐
- [apollo-mcp-server (BlockchainRev)](https://github.com/BlockchainRev/apollo-mcp-server) - Python implementation exposing 34+ tools for sales outreach and pipeline management.
- [linkedin-email-finder-bash (tomba-io)](https://github.com/tomba-io/linkedin-email-finder-bash) - Tool for finding verified business emails from LinkedIn profiles.
- [apollo-io-mcp-server (lkm1developer)](https://github.com/lkm1developer/apollo-io-mcp-server) - Focused on exposing Apollo.io API functionalities as MCP tools.
- [crunchbase-mcp-server (Cyreslab-AI)](https://github.com/Cyreslab-AI/crunchbase-mcp-server) - Crunchbase MCP server to search companies, funding information, and acquisitions. ⭐
- [mcp (datalayer-sh)](https://github.com/datalayer-sh/mcp) - B2B data enrichment MCP server for finding work emails, phone numbers, and buying intent signals. ⭐
- [linkedin_mcp_python (narayanmishra1873)](https://github.com/narayanmishra1873/linkedin_mcp_python) - LinkedIn automation suite designed for profile data extraction and lead generation.
- [leadmagic-openapi (LeadMagic)](https://github.com/LeadMagic/leadmagic-openapi) - OpenAPI/MCP compatible interface for B2B enrichment, email validation, and company intelligence.
- [hunter-mcp (hunter-io)](https://github.com/hunter-io/hunter-mcp) - Deprecated repository for Hunter.io, now migrated to their remote MCP server for email verification and lead intelligence.

### 4. CRM Integrations (HubSpot, Salesforce, etc.)

- [mcp (salesforcecli)](https://github.com/salesforcecli/mcp) - Official Salesforce DX MCP server for Salesforce development and DevOps workflows. ⭐
- [pipedrive-mcp-server (ckalima)](https://github.com/ckalima/pipedrive-mcp-server) - Exposes 150+ tools covering deals, persons, and activities in Pipedrive. ⭐
- [mcp-server-salesforce (tsmztech)](https://github.com/tsmztech/mcp-server-salesforce) - Focuses on integrating Claude with Salesforce for querying and managing records.
- [notion-mcp-server (makenotion)](https://github.com/makenotion/notion-mcp-server) - Official Notion MCP server to read, search, and update databases and workspaces. ⭐
- [airtable-mcp (rashidazarang)](https://github.com/rashidazarang/airtable-mcp) - Community-built Airtable MCP server supporting full CRUD, schema management, and analytics. ⭐
- [odoo-mcp-pro (pantalytics)](https://github.com/pantalytics/odoo-mcp-pro) - Highly active repository designed as an AI connector for Odoo ERP data.
- [mcp-odoo (tuanle96)](https://github.com/tuanle96/mcp-odoo) - Connects Odoo 16+ databases to AI clients using XML-RPC/JSON-RPC without server-side modifications.
- [odoo-mcp-improved (hachecito)](https://github.com/hachecito/odoo-mcp-improved) - Extended Odoo MCP implementation with advanced tools for sales and inventory.
- [salesforce-mcp (jpmonette)](https://github.com/jpmonette/salesforce-mcp) - Minimal Salesforce integration using jsforce for API interactions.
- [MCP-Salesforce (smn2gnt)](https://github.com/smn2gnt/MCP-Salesforce) - Connector allowing LLMs to interact with Salesforce via SOQL and SOSL queries.
- [airtable-mcp (felores)](https://github.com/felores/airtable-mcp) - Programmatic management of Airtable bases, tables, and records for AI agents.

### 5. Web Scraping & Prospecting

- [firecrawl-mcp-server (firecrawl)](https://github.com/firecrawl/firecrawl-mcp-server) - Official Firecrawl MCP server for web scraping, crawling, and search. ⭐
- [playwright-mcp (microsoft)](https://github.com/microsoft/playwright-mcp) - Official Playwright MCP server for browser automation and scraping. ⭐
- [mcp-puppeteer (ratiofu)](https://github.com/ratiofu/mcp-puppeteer) - Puppeteer-based MCP server for browser automation, screenshotting, and content extraction.
- [puppeteer-mcp-server (merajmehrabi)](https://github.com/merajmehrabi/puppeteer-mcp-server) - Controls web browsers using Puppeteer for automated web page interaction.
- [exa-mcp-server (exa-labs)](https://github.com/exa-labs/exa-mcp-server) - Official Exa MCP server for advanced AI-native web search, crawls, and LinkedIn/company search. ⭐
- [tavily-mcp (tavily-ai)](https://github.com/tavily-ai/tavily-mcp) - Official Tavily MCP server for real-time web search and LLM-optimized scraping. ⭐
- [MCP (jina-ai)](https://github.com/jina-ai/MCP) - Official Jina AI MCP server converting web pages to markdown and offering grounding tools. ⭐
- [scrapegraph-mcp (ScrapeGraphAI)](https://github.com/ScrapeGraphAI/scrapegraph-mcp) - Integrates ScrapeGraphAI's API, offering enterprise-grade AI-powered scraping capabilities. ⭐
- [scrap-mcp (sigmaSd)](https://github.com/sigmaSd/scrap-mcp) - Lightweight server built with deno-dom for fast HTML parsing and CSS-based extraction.
- [crawl4ai (unclecode)](https://github.com/unclecode/crawl4ai) - Open-source intelligent content extraction optimized for AI-driven scraping tasks.

### 6. Workflow Automation (n8n, Make, Zapier MCPs)

- [zapier-mcp (zapier)](https://github.com/zapier/zapier-mcp) - Official Zapier MCP server to connect AI agents to 9,000+ apps. ⭐
- [make-mcp-server (integromat)](https://github.com/integromat/make-mcp-server) - Official Make.com server to trigger on-demand scenarios from AI agents. ⭐
- [n8n-mcp (czlonkowski)](https://github.com/czlonkowski/n8n-mcp) - n8n integration for accessing node docs, properties, and workflow building.
- [make-mcp (danishashko)](https://github.com/danishashko/make-mcp) - Community server for searching modules, validating blueprints, and deploying scenarios.
- [n8n-mcp-server (leonardsellem)](https://github.com/leonardsellem/n8n-mcp-server) - Community-maintained MCP server designed to manage and control n8n workflows and executions.
- [n8n-mcp-server (illuminaresolutions)](https://github.com/illuminaresolutions/n8n-mcp-server) - Exposes n8n workflows, credentials, and executions to LLMs.
- [n8n-mcp-server (kingler)](https://github.com/kingler/n8n-mcp-server) - Comprehensive option for managing n8n resources through the MCP interface.
- [activepieces (activepieces)](https://github.com/activepieces/activepieces) - Turn Activepieces automated workflows into MCP-compatible tools for AI agents.
- [mcp-flowise (matthewhand)](https://github.com/matthewhand/mcp-flowise) - Exposes Flowise chatflows and assistants as tools or context providers to MCP clients.

### 7. AI Sales Agents & Copilots

- [mcp-agent (lastmile-ai)](https://github.com/lastmile-ai/mcp-agent) - Python framework for building AI agents with Model Context Protocol using composable workflows. ⭐
- [b2b-sdr-agent-template (iPythoning)](https://github.com/iPythoning/b2b-sdr-agent-template) - Open-source AI SDR template for multi-channel lead generation workflows.
- [gtm-engineer-playbook (Othmane-Khadri)](https://github.com/Othmane-Khadri/gtm-engineer-playbook) - Various Claude Code skills for ICP building, signal scanning, and lead scoring.
- [openai-agents-mcp (lastmile-ai)](https://github.com/lastmile-ai/openai-agents-mcp) - Adds Model Context Protocol support to the OpenAI Agents SDK.
- [enterprise-mcp-server (crewAIInc)](https://github.com/crewAIInc/enterprise-mcp-server) - Official CrewAI MCP server to trigger and monitor CrewAI agent workflows. ⭐
- [open-sdr (MatthewDailey)](https://github.com/MatthewDailey/open-sdr) - Command-line tool and MCP server designed to automate research and outbound lead generation. ⭐
- [langsmith-mcp-server (langchain-ai)](https://github.com/langchain-ai/langsmith-mcp-server) - Integrates LangSmith tracing and observability tools into MCP-compliant workflows.
- [mcp-llamaindex-ai (run-llama)](https://github.com/run-llama/mcp-llamaindex-ai) - Official LlamaIndex MCP server exposing LlamaParse capabilities to AI clients.
- [mcp_autogen_sse_stdio (SaM-92)](https://github.com/SaM-92/mcp_autogen_sse_stdio) - Demonstration of connecting different types of MCP servers to Microsoft AutoGen workflows.

### 8. WhatsApp & Messaging Automation

- [whatsapp-mcp (lharries)](https://github.com/lharries/whatsapp-mcp) - Go-based bridge connecting to WhatsApp Web with a Python MCP server. ⭐
- [whatsapp-mcp-ts (jlucaso1)](https://github.com/jlucaso1/whatsapp-mcp-ts) - TypeScript-based WhatsApp MCP server using the Baileys library.
- [wweb-mcp (pnizer)](https://github.com/pnizer/wweb-mcp) - Node.js bridge to interact with WhatsApp Web via the MCP standard.
- [whatsapp-mcp-server (msaelices)](https://github.com/msaelices/whatsapp-mcp-server) - Python-based WhatsApp server using the GreenAPI interface.
- [telegram-mcp (chigwell)](https://github.com/chigwell/telegram-mcp) - Exposes Telethon-based MTProto API tools to read chats, manage groups, and send messages on Telegram. ⭐
- [fast-mcp-telegram (leshchenko1979)](https://github.com/leshchenko1979/fast-mcp-telegram) - Multi-tenant Telegram MCP server with stdio/HTTP transport and QR code login.
- [mcp-telegram (dryeab)](https://github.com/dryeab/mcp-telegram) - Interacting with Telegram for messaging, searching, and draft management.

### 9. Data Analytics & Reporting for Sales

- [server-postgres (modelcontextprotocol)](https://github.com/modelcontextprotocol/servers) - Standard PostgreSQL MCP server for executing queries and schema discovery. ⭐
- [mcp-sqlite (jparkerweb)](https://github.com/jparkerweb/mcp-sqlite) - Comprehensive MCP server designed for SQLite database interaction.
- [sqlite-mcp-server (arun-gupta)](https://github.com/arun-gupta/sqlite-mcp-server) - Feature-rich SQLite implementation with an optional HTTP wrapper and Docker support.
- [mcp-snowflake-server (isaacwasserman)](https://github.com/isaacwasserman/mcp-snowflake-server) - Enables database interaction, running SQL queries, and exposing schema context in Snowflake.
- [snowflake-mcp (davidamom)](https://github.com/davidamom/snowflake-mcp) - Connects to Snowflake environments for data management and MCP integration.
- [simple_snowflake_mcp (YannBrrd)](https://github.com/YannBrrd/simple_snowflake_mcp) - A lightweight Python-based MCP server for connecting to Snowflake.
- [google-sheets-mcp (mkummer225)](https://github.com/mkummer225/google-sheets-mcp) - Node.js-based Google Sheets MCP server supporting cells, columns, and rows management.
- [google-sheets-mcp (domdomegg)](https://github.com/domdomegg/google-sheets-mcp) - Manage Google Sheets dynamically using OAuth credentials.

### 10. Calendar & Meeting Scheduling

- [cal-mcp (calcom)](https://github.com/calcom/cal-mcp) - Official Cal.com MCP server for managing bookings, event types, and schedules. ⭐
- [calendar-mcp (MarimerLLC)](https://github.com/MarimerLLC/calendar-mcp) - Unified MCP server supporting Microsoft 365, Outlook.com, and Google Workspace accounts simultaneously. ⭐
- [google-calendar-mcp (surana-mudit)](https://github.com/surana-mudit/google-calendar-mcp) - Google Calendar integration for setting up calendar tools in AI editors.
- [Calendar-Autoauth-MCP-Server (GongRzhe)](https://github.com/GongRzhe/Calendar-Autoauth-MCP-Server) - Google Calendar integration for Claude Desktop with auto-authentication support.
- [mcp-google-workspace (j3k0)](https://github.com/j3k0/mcp-google-workspace) - Exposes Google Workspace APIs including Google Calendar and Gmail to AI agents.
- [calcom-mcp-server (mnicole-dev)](https://github.com/mnicole-dev/calcom-mcp-server) - Community-developed MCP server for Cal.com scheduling.
- [calcom-mcp (Danielpeter-99)](https://github.com/Danielpeter-99/calcom-mcp) - FastMCP-based community integration for Cal.com.

---
## 🤝 Contribution Welcome

Contributions are welcome! Please read the [Contribution Guidelines](CONTRIBUTING.md) first.

If you know of any other MCP servers that fit well into any of these categories, please submit a Pull Request.

---

## 📄 License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
