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

### 2. Email Automation

- [gmail-mcp (theposch)](https://github.com/theposch/gmail-mcp) - Feature-rich Python-based server for Gmail integration. ⭐
- [gmail-mcp (bastienchabal)](https://github.com/bastienchabal/gmail-mcp) - Supports both Gmail and Google Calendar workflows.
- [gmail-mcp (shinzo-labs)](https://github.com/shinzo-labs/gmail-mcp) - Offers comprehensive Gmail API coverage, including settings management and labels.
- [mcp-google-gmail (cablate)](https://github.com/cablate/mcp-google-gmail) - Focused on robust email management and search capabilities.

### 3. Lead Generation & Enrichment

- [apollo-mcp (aisacAdmin)](https://github.com/aisacAdmin/apollo-mcp) - Comprehensive Apollo.io MCP server with contact management, enrichment, sequences, and deals. ⭐
- [apollo-mcp-server (BlockchainRev)](https://github.com/BlockchainRev/apollo-mcp-server) - Python implementation exposing 34+ tools for sales outreach and pipeline management.
- [linkedin-email-finder-bash (tomba-io)](https://github.com/tomba-io/linkedin-email-finder-bash) - Tool for finding verified business emails from LinkedIn profiles.
- [apollo-io-mcp-server (lkm1developer)](https://github.com/lkm1developer/apollo-io-mcp-server) - Focused on exposing Apollo.io API functionalities as MCP tools.

### 4. CRM Integrations (HubSpot, Salesforce, etc.)

- [mcp (salesforcecli)](https://github.com/salesforcecli/mcp) - Official Salesforce DX MCP server for Salesforce development and DevOps workflows. ⭐
- [pipedrive-mcp-server (ckalima)](https://github.com/ckalima/pipedrive-mcp-server) - Exposes 150+ tools covering deals, persons, and activities in Pipedrive. ⭐
- [hubspot-mcp (pratikm19)](https://github.com/pratikm19/hubspot-mcp) - A HubSpot MCP server extending the official integration with RevOps utilities.
- [mcp-server-salesforce (tsmztech)](https://github.com/tsmztech/mcp-server-salesforce) - Focuses on integrating Claude with Salesforce for querying and managing records.

### 5. Web Scraping & Prospecting

- [firecrawl-mcp-server (firecrawl)](https://github.com/firecrawl/firecrawl-mcp-server) - Official Firecrawl MCP server for web scraping, crawling, and search. ⭐
- [playwright-mcp (microsoft)](https://github.com/microsoft/playwright-mcp) - Official Playwright MCP server for browser automation and scraping. ⭐
- [mcp-puppeteer (ratiofu)](https://github.com/ratiofu/mcp-puppeteer) - Puppeteer-based MCP server for browser automation, screenshotting, and content extraction.
- [puppeteer-mcp-server (merajmehrabi)](https://github.com/merajmehrabi/puppeteer-mcp-server) - Controls web browsers using Puppeteer for automated web page interaction.

### 6. Workflow Automation (n8n, Make, Zapier MCPs)

- [zapier-mcp (zapier)](https://github.com/zapier/zapier-mcp) - Official Zapier MCP server to connect AI agents to 9,000+ apps. ⭐
- [make-mcp-server (integromat)](https://github.com/integromat/make-mcp-server) - Official Make.com server to trigger on-demand scenarios from AI agents. ⭐
- [n8n-mcp (czlonkowski)](https://github.com/czlonkowski/n8n-mcp) - n8n integration for accessing node docs, properties, and workflow building.
- [make-mcp (danishashko)](https://github.com/danishashko/make-mcp) - Community server for searching modules, validating blueprints, and deploying scenarios.

### 7. AI Sales Agents & Copilots

- [mcp-agent (lastmile-ai)](https://github.com/lastmile-ai/mcp-agent) - Python framework for building AI agents with Model Context Protocol using composable workflows. ⭐
- [b2b-sdr-agent-template (iPythoning)](https://github.com/iPythoning/b2b-sdr-agent-template) - Open-source AI SDR template for multi-channel lead generation workflows.
- [gtm-engineer-playbook (Othmane-Khadri)](https://github.com/Othmane-Khadri/gtm-engineer-playbook) - Various Claude Code skills for ICP building, signal scanning, and lead scoring.
- [openai-agents-mcp (lastmile-ai)](https://github.com/lastmile-ai/openai-agents-mcp) - Adds Model Context Protocol support to the OpenAI Agents SDK.

---

## 🤝 Contribution Welcome

Contributions are welcome! Please read the [Contribution Guidelines](CONTRIBUTING.md) (coming soon) first.

If you know of any other MCP servers that fit well into any of these categories, please submit a Pull Request.

---

## 📄 License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
