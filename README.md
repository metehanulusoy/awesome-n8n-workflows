# 🚀 Awesome n8n Workflows

> A curated collection of **2,055 production-ready n8n automation workflows** covering AI agents, CRM, e-commerce, communication, and more.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Workflows](https://img.shields.io/badge/workflows-2055-blue)
![AI Workflows](https://img.shields.io/badge/AI%20agents-784-purple)
![License](https://img.shields.io/badge/license-MIT-green)

## 📋 Table of Contents

- [🤖 AI & LLM Agents](#-ai---llm-agents) (784)
- [📞 Communication Bots](#-communication-bots) (305)
- [📊 CRM & Sales](#-crm---sales) (46)
- [🛒 E-Commerce](#-e-commerce) (16)
- [📋 Project Management](#-project-management) (103)
- [📁 Google Workspace](#-google-workspace) (135)
- [📣 Marketing & Social](#-marketing---social) (31)
- [🗄️ Data & Database](#-data---database) (29)
- [⚙️ DevOps & GitHub](#-devops---github) (41)
- [📂 Files & Productivity](#-files---productivity) (49)
- [🔧 General Automation](#-general-automation) (516)

---

## 🌟 Why This Collection?

This repository contains **battle-tested n8n workflow templates** that you can import directly into your n8n instance. Each workflow is ready to use and covers real-world automation scenarios.

**Key highlights:**
- 784 AI/LLM agent workflows using OpenAI, Google Gemini, and LangChain
- Full coverage of major SaaS tools (Slack, Notion, HubSpot, Shopify, etc.)
- Production-ready patterns for webhooks, scheduling, and event-driven automation
- Multi-step workflows with error handling and data transformation

## 🚀 Quick Start

1. Install [n8n](https://n8n.io) (self-hosted or cloud)
2. Clone this repository: `git clone https://github.com/YOUR_USERNAME/awesome-n8n-workflows`
3. In n8n, go to **Workflows → Import** and select any `.json` file
4. Configure your credentials and activate the workflow

## 📊 Statistics

| Category | Count |
|----------|-------|
| 🤖 AI & LLM Agents | 784 |
| 📞 Communication Bots | 305 |
| 📊 CRM & Sales | 46 |
| 🛒 E-Commerce | 16 |
| 📋 Project Management | 103 |
| 📁 Google Workspace | 135 |
| 📣 Marketing & Social | 31 |
| 🗄️ Data & Database | 29 |
| ⚙️ DevOps & GitHub | 41 |
| 📂 Files & Productivity | 49 |
| 🔧 General Automation | 516 |
| **Total** | **2,055** |

---

## 🤖 AI & LLM Agents

Workflows powered by OpenAI GPT-4, Google Gemini, and LangChain agents. Build chatbots, document analyzers, content generators, and autonomous AI pipelines.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [#️⃣Nostr #damus AI Powered Reporting + Gmail + Telegram](workflows/0001_Telegram_Schedule_Automation_Scheduled.json) | chainllm, telegram, nostrobotsread, gmail, lmchatgooglegemini | 24 |
| 2 | [OpenAI-model-examples](workflows/0171_Readbinaryfiles_Code_Automation_Webhook.json) | openai, readbinaryfiles | 27 |
| 3 | [Telegram AI-bot](workflows/0248_Openai_Telegram_Automate_Triggered.json) | telegram, openai, telegramtrigger | 16 |
| 4 | [Auto WordPress Blog Generator (GPT + Postgres + WP Media)](workflows/0263_Postgres_Code_Automation_Webhook.json) | agent, lmchatopenai, postgres | 46 |
| 5 | [Discord AI bot](workflows/0270_Webhook_Discord_Automate_Webhook.json) | openai, discord | 9 |
| 6 | [0283 Lemlist Slack Create Webhook](workflows/0283_Lemlist_Slack_Create_Webhook.json) | lemlist, slack, lemlisttrigger, hubspot, openai | 12 |
| 7 | [0290 Wait Code Update Webhook](workflows/0290_Wait_Code_Update_Webhook.json) | googlesheets, openai, htmlextract | 11 |
| 8 | [0297 Manual Openai Export Triggered](workflows/0297_Manual_Openai_Export_Triggered.json) | openai, reddit | 15 |
| 9 | [0298 Code Readpdf Send Triggered](workflows/0298_Code_Readpdf_Send_Triggered.json) | googledrive, readpdf, gmailtrigger, openai | 18 |
| 10 | [0299 Code Webhook Create Webhook](workflows/0299_Code_Webhook_Create_Webhook.json) | crypto, gmailtrigger, googlesheets, gmail, openai | 49 |
| 11 | [0318 Splitout Limit Automation Webhook](workflows/0318_Splitout_Limit_Automation_Webhook.json) | textsplitterrecursivecharactertextsplitter, documentdefaultdataloader, lmchatopenai, chainsummarization | 16 |
| 12 | [0319 Gmail Googlecalendartool Send Triggered](workflows/0319_Gmail_Googlecalendartool_Send_Triggered.json) | agent, gmailtrigger, googlecalendartool, gmail, lmchatopenai, textclassifier | 10 |
| 13 | [0320 Send Triggered](workflows/0320_Send_Triggered.json) | agent, memorybufferwindow, lmchatopenai, toolserpapi, chattrigger | 5 |
| 14 | [0321 Manual Stickynote Automate Triggered](workflows/0321_Manual_Stickynote_Automate_Triggered.json) | agent, lmchatopenai, toolcode | 10 |
| 15 | [0322 Splitout Code Send Triggered](workflows/0322_Splitout_Code_Send_Triggered.json) | textsplitterrecursivecharactertextsplitter, informationextractor, agent, documentdefaultdataloader, gmail, lmchatopenai | 18 |
| 16 | [0323 Manual Stickynote Process Triggered](workflows/0323_Manual_Stickynote_Process_Triggered.json) | chainllm, outputparserautofixing, lmchatopenai, outputparserstructured | 11 |
| 17 | [0324 Manual Stickynote Update Triggered](workflows/0324_Manual_Stickynote_Update_Triggered.json) | lmchatopenai, chainretrievalqa, retrieverworkflow | 7 |
| 18 | [0325 Stickynote Send Triggered](workflows/0325_Stickynote_Send_Triggered.json) | memorybufferwindow, agent, lmchatopenai, toolserpapi, toolwikipedia, chattrigger | 9 |
| 19 | [0326 Manual Stickynote Send Triggered](workflows/0326_Manual_Stickynote_Send_Triggered.json) | googledrive, textsplitterrecursivecharactertextsplitter, agent, documentdefaultdataloader, vectorstorepinecone, lmchatopenai | 15 |
| 20 | [0327 Noop Slack Send Webhook](workflows/0327_Noop_Slack_Send_Webhook.json) | slack, memorybufferwindow, agent, lmchatopenai, toolserpapi, toolwikipedia | 14 |
| 21 | [0328 Manual GoogleDrive Automate Triggered](workflows/0328_Manual_GoogleDrive_Automate_Triggered.json) | googledrive, documentdefaultdataloader, lmchatopenai, textsplittertokensplitter, chainsummarization | 6 |
| 22 | [0329 Manual Send Triggered](workflows/0329_Manual_Send_Triggered.json) | agent, chattrigger, lmchatopenai, toolcode | 6 |
| 23 | [0331 Stopanderror Extractfromfile Send Webhook](workflows/0331_Stopanderror_Extractfromfile_Send_Webhook.json) | informationextractor, lmchatopenai, emailsend | 24 |
| 24 | [0332 Stickynote Send Triggered](workflows/0332_Stickynote_Send_Triggered.json) | chainllm, chattrigger, lmopenhuggingfaceinference | 4 |
| 25 | [0334 Openai Form Create Triggered](workflows/0334_Openai_Form_Create_Triggered.json) | googlesheets, openai | 9 |
| 26 | [Structured Data Extract, Data Mining with Bright Data & Goog](workflows/0337_Manual_Stickynote_Automation_Webhook.json) | chainllm, informationextractor, lmchatgooglegemini, readwritefile | 18 |
| 27 | [Printify Automation - Update Title and Description - AlexK19](workflows/0339_Splitout_Code_Update_Webhook.json) | googlesheets, openai, toolwikipedia, toolcalculator, googlesheetstrigger | 26 |
| 28 | [Blockchain DEX Screener Insights Agent](workflows/0340_Telegram_Automation_Webhook.json) | telegram, agent, memorybufferwindow, lmchatopenai, toolhttprequest, chattrigger | 15 |
| 29 | [0363 HTTP Executeworkflow Automate Webhook](workflows/0363_HTTP_Executeworkflow_Automate_Webhook.json) | agent, lmchatopenai, chattrigger, toolworkflow | 20 |
| 30 | [0371 Executeworkflow Summarize Send Triggered](workflows/0371_Executeworkflow_Summarize_Send_Triggered.json) | memorybufferwindow, openai, chattrigger, toolcode, toolworkflow | 15 |

> **+754 more workflows in this category** — browse the `workflows/` folder

## 📞 Communication Bots

Automation for Telegram, Slack, Discord, WhatsApp, and email. Send notifications, build bots, and connect messaging platforms.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [On new Stripe Invoice Payment update Hubspot and notify the ](workflows/0008_Slack_Stripe_Create_Triggered.json) | hubspot, slack, stripetrigger | 8 |
| 2 | [0017 Mattermost Emelia Automate Triggered](workflows/0017_Mattermost_Emelia_Automate_Triggered.json) | emeliatrigger, mattermost | 2 |
| 3 | [0020 Mattermost Emelia Automate Triggered](workflows/0020_Mattermost_Emelia_Automate_Triggered.json) | emeliatrigger, mattermost | 2 |
| 4 | [0027 Mattermost N8N Automate Triggered](workflows/0027_Mattermost_N8N_Automate_Triggered.json) | n8ntrigger, mattermost | 2 |
| 5 | [0028 Mattermost Workflow Automate Webhook](workflows/0028_Mattermost_Workflow_Automate_Webhook.json) | mattermost, workflowtrigger | 4 |
| 6 | [0036 Gmail GoogleDrive Import](workflows/0036_Gmail_GoogleDrive_Import.json) | googledrive, gmail | 3 |
| 7 | [0038 Manual Ical Send Triggered](workflows/0038_Manual_Ical_Send_Triggered.json) | ical, emailsend | 3 |
| 8 | [0040 Mattermost Noop Automate Triggered](workflows/0040_Mattermost_Noop_Automate_Triggered.json) | mattermost, notiontrigger | 4 |
| 9 | [0044 Trello Googlecloudnaturallanguage Automate Triggered](workflows/0044_Trello_Googlecloudnaturallanguage_Automate_Triggered.json) | slack, notion, googlecloudnaturallanguage, trello, typeformtrigger | 6 |
| 10 | [Get SSL Certificate](workflows/0045_Manual_Telegram_Import_Triggered.json) | telegram, uproc | 5 |
| 11 | [0061 Noop GitHub Automate Triggered](workflows/0061_Noop_GitHub_Automate_Triggered.json) | telegramtrigger, github | 5 |
| 12 | [Standup Bot - Worker](workflows/0066_Webhook_Cron_Automate_Scheduled.json) | mattermost | 29 |
| 13 | [0069 Manual Gmail Automation Triggered](workflows/0069_Manual_Gmail_Automation_Triggered.json) | gmail | 4 |
| 14 | [Google Calendar to Slack Status & Philips Hue](workflows/0078_Manual_Slack_Monitor_Webhook.json) | googlecalendartrigger, slack, googlecalendar | 9 |
| 15 | [What To Eat](workflows/0084_HTTP_Cron_Automation_Webhook.json) | emailsend | 9 |
| 16 | [0085 Shopify Twitter Create Triggered](workflows/0085_Shopify_Twitter_Create_Triggered.json) | telegram, shopifytrigger, twitter | 3 |
| 17 | [0086 Zohocrm Trello Create Triggered](workflows/0086_Zohocrm_Trello_Create_Triggered.json) | zohocrm, harvest, gmail, shopifytrigger, mailchimp, trello | 9 |
| 18 | [0087 Datetime Slack Automate Scheduled](workflows/0087_Datetime_Slack_Automate_Scheduled.json) | slack, googlesheets, shopify | 9 |
| 19 | [0089 Noop Telegram Automate Triggered](workflows/0089_Noop_Telegram_Automate_Triggered.json) | telegram, googleperspective, telegramtrigger | 5 |
| 20 | [0092 Wait Datetime Automate Triggered](workflows/0092_Wait_Datetime_Automate_Triggered.json) | pipedrive, slack, calendlytrigger | 5 |
| 21 | [0094 Noop Gmail Create Triggered](workflows/0094_Noop_Gmail_Create_Triggered.json) | hubspot, gmail, typeformtrigger | 7 |
| 22 | [0095 Googleslides Slack Automate Triggered](workflows/0095_Googleslides_Slack_Automate_Triggered.json) | slack, hubspottrigger, hubspot, airtable, googleslides | 10 |
| 23 | [0102 Manual HTTP Create Webhook](workflows/0102_Manual_HTTP_Create_Webhook.json) | emailsend, htmlextract | 8 |
| 24 | [0105 Netlify Slack Automate Triggered](workflows/0105_Netlify_Slack_Automate_Triggered.json) | slack, netlifytrigger | 2 |
| 25 | [0109 Slack Cron Automate Scheduled](workflows/0109_Slack_Cron_Automate_Scheduled.json) | slack, googlecalendar | 12 |
| 26 | [0113 Emailsend GoogleDrive Send Triggered](workflows/0113_Emailsend_GoogleDrive_Send_Triggered.json) | googledrivetrigger, emailsend | 2 |
| 27 | [0116 Graphql Discord Automate Scheduled](workflows/0116_Graphql_Discord_Automate_Scheduled.json) | graphql, discord | 5 |
| 28 | [Find a New Book](workflows/0119_Manual_Cron_Create_Webhook.json) | emailsend | 13 |
| 29 | [Receive a Mattermost message when a user updates their profi](workflows/0123_Facebook_Mattermost_Update_Triggered.json) | facebooktrigger, mattermost | 2 |
| 30 | [0124 Slack Typeform Create Triggered](workflows/0124_Slack_Typeform_Create_Triggered.json) | slack, dropcontact, airtable, typeformtrigger | 10 |

> **+275 more workflows in this category** — browse the `workflows/` folder

## 📊 CRM & Sales

Connect HubSpot, Pipedrive, Stripe, and other sales tools. Automate lead management, deal tracking, and payment processing.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [0011 Manual Copper Automate Triggered](workflows/0011_Manual_Copper_Automate_Triggered.json) | copper | 4 |
| 2 | [0012 Manual Copper Automate Triggered](workflows/0012_Manual_Copper_Automate_Triggered.json) | copper | 4 |
| 3 | [Create a new customer in Chargebee](workflows/0018_Manual_Chargebee_Create_Triggered.json) | chargebee | 2 |
| 4 | [Receive updates for events in Chargebee](workflows/0041_Chargebee_Update_Triggered.json) | chargebeetrigger | 1 |
| 5 | [Create an deal in Pipedrive](workflows/0062_Manual_Pipedrive_Create_Triggered.json) | pipedrive | 2 |
| 6 | [Receive updates for all changes in Pipedrive](workflows/0071_Pipedrive_Update_Triggered.json) | pipedrivetrigger | 1 |
| 7 | [Create Email Campaign From LinkedIn Post Interactions](workflows/0090_Wait_Lemlist_Create_Scheduled.json) | lemlist, dropcontact, hubspot, airtable, phantombuster | 16 |
| 8 | [0115 HubSpot Clearbit Update Triggered](workflows/0115_HubSpot_Clearbit_Update_Triggered.json) | hubspottrigger, clearbit, hubspot | 4 |
| 9 | [0129 HubSpot Cron Update Scheduled](workflows/0129_HubSpot_Cron_Update_Scheduled.json) | pipedrive, hubspot | 7 |
| 10 | [0130 HubSpot Cron Automate Scheduled](workflows/0130_HubSpot_Cron_Automate_Scheduled.json) | pipedrive, hubspot | 5 |
| 11 | [0239 Code Typeform Create Triggered](workflows/0239_Code_Typeform_Create_Triggered.json) | pipedrive, typeformtrigger | 8 |
| 12 | [0243 HubSpot Mailchimp Create Scheduled](workflows/0243_HubSpot_Mailchimp_Create_Scheduled.json) | hubspot, mailchimp | 3 |
| 13 | [0244 HubSpot Mailchimp Create Scheduled](workflows/0244_HubSpot_Mailchimp_Create_Scheduled.json) | hubspot, mailchimp | 5 |
| 14 | [0245 HTTP Stripe Create Webhook](workflows/0245_HTTP_Stripe_Create_Webhook.json) | pipedrive, stripe, pipedrivetrigger | 7 |
| 15 | [0246 Functionitem Pipedrive Create Scheduled](workflows/0246_Functionitem_Pipedrive_Create_Scheduled.json) | pipedrive, stripe | 11 |
| 16 | [0247 Functionitem HTTP Create Webhook](workflows/0247_Functionitem_HTTP_Create_Webhook.json) | pipedrivetrigger | 7 |
| 17 | [0249 Pipedrive Stickynote Create Webhook](workflows/0249_Pipedrive_Stickynote_Create_Webhook.json) | pipedrive, pipedrivetrigger | 11 |
| 18 | [0251 Pipedrive Spreadsheetfile Create Triggered](workflows/0251_Pipedrive_Spreadsheetfile_Create_Triggered.json) | googledrive, googledrivetrigger, pipedrive | 12 |
| 19 | [0252 HTTP GitHub Create Webhook](workflows/0252_HTTP_GitHub_Create_Webhook.json) | pipedrive, githubtrigger | 8 |
| 20 | [0253 HTTP GitHub Send Webhook](workflows/0253_HTTP_GitHub_Send_Webhook.json) | pipedrive, githubtrigger | 6 |
| 21 | [0257 Manual GoogleSheets Create Triggered](workflows/0257_Manual_GoogleSheets_Create_Triggered.json) | googlesheets, salesforce, renamekeys | 12 |
| 22 | [0258 Microsoftexcel Manual Create Triggered](workflows/0258_Microsoftexcel_Manual_Create_Triggered.json) | microsoftexcel, salesforce, renamekeys | 12 |
| 23 | [0259 Manual HTTP Create Webhook](workflows/0259_Manual_HTTP_Create_Webhook.json) | salesforce, renamekeys | 14 |
| 24 | [0265 Shopify HubSpot Create Triggered](workflows/0265_Shopify_HubSpot_Create_Triggered.json) | hubspot, shopifytrigger | 8 |
| 25 | [0266 Functionitem Zendesk Create Webhook](workflows/0266_Functionitem_Zendesk_Create_Webhook.json) | pipedrive, zendesk | 17 |
| 26 | [0267 Functionitem Zendesk Create Scheduled](workflows/0267_Functionitem_Zendesk_Create_Scheduled.json) | pipedrive, zendesk | 21 |
| 27 | [0285 Zendesk HubSpot Create Scheduled](workflows/0285_Zendesk_HubSpot_Create_Scheduled.json) | zendesk, hubspot | 9 |
| 28 | [0286 Zendesk HubSpot Create Scheduled](workflows/0286_Zendesk_HubSpot_Create_Scheduled.json) | zendesk, hubspot | 13 |
| 29 | [0288 Code Schedule Create Webhook](workflows/0288_Code_Schedule_Create_Webhook.json) | stripe, hubspot | 24 |
| 30 | [0416 Noop HubSpot Create Webhook](workflows/0416_Noop_HubSpot_Create_Webhook.json) | hubspottrigger, hubspot | 12 |

> **+16 more workflows in this category** — browse the `workflows/` folder

## 🛒 E-Commerce

Shopify, WooCommerce, and Chargebee automations. Manage orders, inventory, customer notifications, and billing.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [0120 Manual GoogleSheets Automate Triggered](workflows/0120_Manual_GoogleSheets_Automate_Triggered.json) | googlesheets, lemlist, dropcontact | 4 |
| 2 | [Creating an Onfleet Task for a new Shopify Fulfillment](workflows/0152_Shopify_Onfleet_Create_Triggered.json) | onfleet, shopifytrigger | 2 |
| 3 | [Updating Shopify tags on Onfleet events](workflows/0185_Shopify_Onfleet_Automation_Triggered.json) | shopify, onfleettrigger | 2 |
| 4 | [0268 Shopify Zendesk Create Triggered](workflows/0268_Shopify_Zendesk_Create_Triggered.json) | zendesk, shopifytrigger | 9 |
| 5 | [0269 Shopify Zendesk Create Triggered](workflows/0269_Shopify_Zendesk_Create_Triggered.json) | zendesk, shopifytrigger | 7 |
| 6 | [0278 Shopify Mautic Create Triggered](workflows/0278_Shopify_Mautic_Create_Triggered.json) | mautic, shopifytrigger | 3 |
| 7 | [Create, update and get a product from WooCommerce](workflows/0293_Manual_Woocommerce_Create_Triggered.json) | woocommerce | 4 |
| 8 | [0801 Filter Schedule Import Webhook](workflows/0801_Filter_Schedule_Import_Webhook.json) | shopify | 13 |
| 9 | [Sync New Shopify Products to Odoo Product](workflows/0961_Shopify_Filter_Create_Triggered.json) | shopifytrigger, odoo | 5 |
| 10 | [1015 Shopify Automate Triggered](workflows/1015_Shopify_Automate_Triggered.json) | shopifytrigger | 1 |
| 11 | [1016 Manual Shopify Automate Triggered](workflows/1016_Manual_Shopify_Automate_Triggered.json) | shopify | 2 |
| 12 | [New WooCommerce Customer to Mautic](workflows/1160_Mautic_Woocommerce_Create_Triggered.json) | mautic, woocommercetrigger | 5 |
| 13 | [1220 Airtable Lemlist Automate](workflows/1220_Airtable_Lemlist_Automate.json) | airtable, lemlist | 3 |
| 14 | [Shopify + Mautic](workflows/1526_Mautic_Webhook_Automation_Webhook.json) | crypto, graphql, shopifytrigger, mautic | 26 |
| 15 | [[n8n] - Shopify Orders to D365 Business Central Sales Orders](workflows/1560_Splitout_Code_Automation_Webhook.json) | shopify | 39 |
| 16 | [Sync New Shopify Customers to Odoo Contacts](workflows/1786_Shopify_Filter_Create_Triggered.json) | shopifytrigger, odoo | 5 |

## 📋 Project Management

Notion, ClickUp, Trello, Jira, and Airtable workflows. Automate task creation, status updates, and team notifications.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [New tweets](workflows/0005_Manual_Twitter_Create_Triggered.json) | twitter, airtable | 7 |
| 2 | [0026 Mailcheck Airtable Monitor](workflows/0026_Mailcheck_Airtable_Monitor.json) | mailcheck, airtable | 4 |
| 3 | [Create a task in ClickUp](workflows/0030_Manual_Clickup_Create_Triggered.json) | clickup | 2 |
| 4 | [0039 Calendly Notion Automate Triggered](workflows/0039_Calendly_Notion_Automate_Triggered.json) | calendlytrigger, notion | 2 |
| 5 | [0042 Crypto Airtable Update Webhook](workflows/0042_Crypto_Airtable_Update_Webhook.json) | crypto, airtable | 26 |
| 6 | [0043 Humanticai Calendly Automate Triggered](workflows/0043_Humanticai_Calendly_Automate_Triggered.json) | calendlytrigger, notion, humanticai | 4 |
| 7 | [Receive updates for events in ClickUp](workflows/0047_Clickup_Update_Triggered.json) | clickuptrigger | 1 |
| 8 | [0048 HTTP Htmlextract Create Webhook](workflows/0048_HTTP_Htmlextract_Create_Webhook.json) | notion, htmlextract | 7 |
| 9 | [0053 Trello GoogleCalendar Create Scheduled](workflows/0053_Trello_GoogleCalendar_Create_Scheduled.json) | trello, googlecalendar | 8 |
| 10 | [0055 Signl4 Interval Create Scheduled](workflows/0055_Signl4_Interval_Create_Scheduled.json) | notiontrigger, notion, signl4, interval | 13 |
| 11 | [Archive empty pages in Notion Database](workflows/0070_Splitinbatches_Notion_Export_Scheduled.json) | notion | 10 |
| 12 | [Receive updates for changes in the specified list in Trello](workflows/0076_Trello_Update_Triggered.json) | trellotrigger | 1 |
| 13 | [0099 Webhook Airtable Automate Webhook](workflows/0099_Webhook_Airtable_Automate_Webhook.json) | redis, airtable | 11 |
| 14 | [0103 Netlify Airtable Automate Triggered](workflows/0103_Netlify_Airtable_Automate_Triggered.json) | airtable, netlifytrigger | 3 |
| 15 | [0125 Calendly Notion Automate Triggered](workflows/0125_Calendly_Notion_Automate_Triggered.json) | calendlytrigger, notion, dropcontact | 3 |
| 16 | [0141 Notion Webhook Create Webhook](workflows/0141_Notion_Webhook_Create_Webhook.json) | notion | 12 |
| 17 | [0142 Notion Webhook Create Webhook](workflows/0142_Notion_Webhook_Create_Webhook.json) | notion | 23 |
| 18 | [0165 Webhook Respondtowebhook Create Webhook](workflows/0165_Webhook_Respondtowebhook_Create_Webhook.json) | crypto, airtable | 16 |
| 19 | [Update Crypto Values](workflows/0177_Coingecko_Cron_Update_Scheduled.json) | airtable, coingecko | 8 |
| 20 | [0181 Manual HTTP Automation Webhook](workflows/0181_Manual_HTTP_Automation_Webhook.json) | airtable | 5 |
| 21 | [User Request Management](workflows/0215_Typeform_Clickup_Automation_Triggered.json) | clickup, typeformtrigger | 7 |
| 22 | [Insert and update data in Airtable](workflows/0218_Manual_Airtable_Update_Triggered.json) | airtable | 6 |
| 23 | [0241 Asana Notion Create Triggered](workflows/0241_Asana_Notion_Create_Triggered.json) | asana, notion, asanatrigger | 10 |
| 24 | [Get the logo, icon, and information of a company and store i](workflows/0242_Manual_Brandfetch_Import_Triggered.json) | airtable, brandfetch | 5 |
| 25 | [0264 GitHub Stickynote Create Triggered](workflows/0264_GitHub_Stickynote_Create_Triggered.json) | githubtrigger, notion | 11 |
| 26 | [0272 Notion GoogleDrive Create Triggered](workflows/0272_Notion_GoogleDrive_Create_Triggered.json) | googledrivetrigger, notion | 2 |
| 27 | [0274 Zendesk Asana Create Webhook](workflows/0274_Zendesk_Asana_Create_Webhook.json) | zendesk, asana | 7 |
| 28 | [0275 Mautic Mondaycom Create Triggered](workflows/0275_Mautic_Mondaycom_Create_Triggered.json) | mondaycom, mautictrigger | 3 |
| 29 | [0280 Zendesk Jira Create Webhook](workflows/0280_Zendesk_Jira_Create_Webhook.json) | zendesk, jira | 7 |
| 30 | [0281 Stickynote Notion Create Webhook](workflows/0281_Stickynote_Notion_Create_Webhook.json) | notion | 3 |

> **+73 more workflows in this category** — browse the `workflows/` folder

## 📁 Google Workspace

Google Sheets, Drive, Docs, Calendar, and Gmail automations. Sync data, automate reports, and manage files.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [typeform feedback workflow](workflows/0004_GoogleSheets_Typeform_Automate_Triggered.json) | googlesheets, typeformtrigger | 5 |
| 2 | [0016 Manual Googleslides Automate Triggered](workflows/0016_Manual_Googleslides_Automate_Triggered.json) | googleslides | 3 |
| 3 | [0035 GoogleSheets Webhook Automate Webhook](workflows/0035_GoogleSheets_Webhook_Automate_Webhook.json) | googlesheets | 2 |
| 4 | [0068 Functionitem Manual Import Scheduled](workflows/0068_Functionitem_Manual_Import_Scheduled.json) | googledrive | 9 |
| 5 | [0082 GoogleSheets Interval Process Scheduled](workflows/0082_GoogleSheets_Interval_Process_Scheduled.json) | dropbox, googlesheets, interval | 4 |
| 6 | [0149 Awss3 Wait Automate Triggered](workflows/0149_Awss3_Wait_Automate_Triggered.json) | googledrivetrigger, awstranscribe, googlesheets, awss3 | 8 |
| 7 | [0150 Awsrekognition GoogleSheets Automation Webhook](workflows/0150_Awsrekognition_GoogleSheets_Automation_Webhook.json) | awsrekognition, googlesheets | 6 |
| 8 | [0151 Awss3 GoogleDrive Import Triggered](workflows/0151_Awss3_GoogleDrive_Import_Triggered.json) | awss3, googledrivetrigger | 4 |
| 9 | [0156 HTTP Awsrekognition Automation Webhook](workflows/0156_HTTP_Awsrekognition_Automation_Webhook.json) | awsrekognition, googlesheets | 4 |
| 10 | [0172 Noop GoogleSheets Create Webhook](workflows/0172_Noop_GoogleSheets_Create_Webhook.json) | googlesheets | 6 |
| 11 | [Create an Onfleet task when a file in Google Drive is update](workflows/0187_Onfleet_GoogleDrive_Create_Triggered.json) | onfleet, googledrivetrigger | 2 |
| 12 | [0222 GoogleSheets Readbinaryfile Automate](workflows/0222_GoogleSheets_Readbinaryfile_Automate.json) | googlesheets, readbinaryfile | 3 |
| 13 | [0223 HTTP GoogleSheets Automation Webhook](workflows/0223_HTTP_GoogleSheets_Automation_Webhook.json) | googlesheets | 6 |
| 14 | [0233 Manual N8Ntrainingcustomerdatastore Create Triggered](workflows/0233_Manual_N8Ntrainingcustomerdatastore_Create_Triggered.json) | googlesheets, n8ntrainingcustomerdatastore | 6 |
| 15 | [0234 GoogleSheets Cron Create Scheduled](workflows/0234_GoogleSheets_Cron_Create_Scheduled.json) | mysql, googlesheets | 3 |
| 16 | [0235 GoogleSheets Cron Automation Scheduled](workflows/0235_GoogleSheets_Cron_Automation_Scheduled.json) | mysql, googlesheets | 3 |
| 17 | [0236 Manual GoogleSheets Create Scheduled](workflows/0236_Manual_GoogleSheets_Create_Scheduled.json) | googlesheets, interval | 7 |
| 18 | [0237 GoogleSheets Spreadsheetfile Create Webhook](workflows/0237_GoogleSheets_Spreadsheetfile_Create_Webhook.json) | googlesheets | 3 |
| 19 | [0238 GoogleSheets Respondtowebhook Automate Webhook](workflows/0238_GoogleSheets_Respondtowebhook_Automate_Webhook.json) | googlesheets | 4 |
| 20 | [0256 GoogleSheets Readbinaryfile Automate](workflows/0256_GoogleSheets_Readbinaryfile_Automate.json) | googlesheets, readbinaryfile | 3 |
| 21 | [0271 Manual HTTP Create Webhook](workflows/0271_Manual_HTTP_Create_Webhook.json) | googlesheets, xml | 10 |
| 22 | [0276 Microsoftonedrive Readbinaryfile Automation Webhook](workflows/0276_Microsoftonedrive_Readbinaryfile_Automation_Webhook.json) | googledrive, writebinaryfile, ftp, readbinaryfile, microsoftonedrive | 24 |
| 23 | [0307 Code Postgres Automate Triggered](workflows/0307_Code_Postgres_Automate_Triggered.json) | googlesheets, postgrestrigger | 9 |
| 24 | [0310 HTTP Manual Automation Webhook](workflows/0310_HTTP_Manual_Automation_Webhook.json) | googlesheets | 8 |
| 25 | [0313 HTTP Schedule Create Scheduled](workflows/0313_HTTP_Schedule_Create_Scheduled.json) | googlecalendar | 9 |
| 26 | [Add a event to Calender](workflows/0342_Manual_GoogleCalendar_Create_Triggered.json) | googlecalendar | 2 |
| 27 | [Dialpad to Syncro](workflows/0347_HTTP_GoogleSheets_Sync_Webhook.json) | googlesheets | 22 |
| 28 | [Google Cal to Zoom meeting](workflows/0348_Datetime_GoogleCalendar_Automation_Scheduled.json) | zoom, googlecalendar | 6 |
| 29 | [Google Sheet to Mailchimp](workflows/0349_Manual_GoogleSheets_Automation_Scheduled.json) | interval, mailchimp, googlesheets | 4 |
| 30 | [0365 Code Manual Send Webhook](workflows/0365_Code_Manual_Send_Webhook.json) | googlesheets | 8 |

> **+105 more workflows in this category** — browse the `workflows/` folder

## 📣 Marketing & Social

Twitter/X, LinkedIn, YouTube, and WordPress automations. Schedule posts, track mentions, and grow your audience.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [0059 Manual Twitter Automate Triggered](workflows/0059_Manual_Twitter_Automate_Triggered.json) | twitter | 4 |
| 2 | [0073 Manual Rssfeedread Automate Triggered](workflows/0073_Manual_Rssfeedread_Automate_Triggered.json) | rssfeedread | 6 |
| 3 | [0144 HTTP Twitter Automation Scheduled](workflows/0144_HTTP_Twitter_Automation_Scheduled.json) | twitter | 4 |
| 4 | [Receive updates when a form is submitted in Mautic, and send](workflows/0155_Mautic_Twilio_Update_Triggered.json) | twilio, mautictrigger | 2 |
| 5 | [0183 Strapi Webhook Automation Webhook](workflows/0183_Strapi_Webhook_Automation_Webhook.json) | googlecloudnaturallanguage, twitter, strapi, interval | 14 |
| 6 | [0277 Calendly Mautic Create Triggered](workflows/0277_Calendly_Mautic_Create_Triggered.json) | calendlytrigger, mautic | 3 |
| 7 | [TwitterWorkflow](workflows/0356_Manual_Twitter_Automate_Scheduled.json) | twitter, rocketchat | 6 |
| 8 | [Wordpress-to-csv](workflows/0359_Manual_Wordpress_Automation_Triggered.json) | wordpress, writebinaryfile | 4 |
| 9 | [Upload video, create playlist and add video to playlist](workflows/0476_Manual_Youtube_Create_Triggered.json) | youtube, readbinaryfile | 5 |
| 10 | [0477 Manual Youtube Create Triggered](workflows/0477_Manual_Youtube_Create_Triggered.json) | youtube | 9 |
| 11 | [0623 Comparedatasets Manual Create Triggered](workflows/0623_Comparedatasets_Manual_Create_Triggered.json) | comparedatasets, spotify, youtube | 12 |
| 12 | [0641 HTTP Rssfeedread Create Webhook](workflows/0641_HTTP_Rssfeedread_Create_Webhook.json) | rssfeedreadtrigger | 10 |
| 13 | [post to mattermost v2](workflows/0752_HTTP_Rssfeedread_Automation_Scheduled.json) | rssfeedread | 6 |
| 14 | [Automatically Update YouTube Video Descriptions with Inserte](workflows/0773_Code_Manual_Update_Triggered.json) | youtube | 9 |
| 15 | [Extract And Decode Google News RSS URLs to Clean Article Lin](workflows/0932_Limit_Code_Create_Webhook.json) | rssfeedread | 20 |
| 16 | [Mailchimp](workflows/0938_Manual_Mailchimp_Automation_Triggered.json) | mailchimp | 2 |
| 17 | [0963 Mautic Webhook Update Webhook](workflows/0963_Mautic_Webhook_Update_Webhook.json) | mautic | 17 |
| 18 | [0989 Mailchimp Automate Triggered](workflows/0989_Mailchimp_Automate_Triggered.json) | mailchimptrigger | 1 |
| 19 | [1014 Manual Wordpress Automate Triggered](workflows/1014_Manual_Wordpress_Automate_Triggered.json) | wordpress | 2 |
| 20 | [1017 Manual Mautic Automate Triggered](workflows/1017_Manual_Mautic_Automate_Triggered.json) | mautic | 2 |
| 21 | [1046 Manual Rssfeedread Automate Triggered](workflows/1046_Manual_Rssfeedread_Automate_Triggered.json) | rssfeedread | 2 |
| 22 | [Create a post and update the post in WordPress](workflows/1075_Manual_Wordpress_Create_Triggered.json) | wordpress | 3 |
| 23 | [1096 Manual Linkedin Automation Webhook](workflows/1096_Manual_Linkedin_Automation_Webhook.json) | linkedin | 3 |
| 24 | [Read RSS feed from two different sources](workflows/1122_Manual_Rssfeedread_Automation_Triggered.json) | rssfeedread | 4 |
| 25 | [YouTube to Raindrop](workflows/1140_Functionitem_Raindrop_Automation_Scheduled.json) | youtube, raindrop | 6 |
| 26 | [Get only new RSS with Photo](workflows/1180_Rssfeedread_Htmlextract_Create_Scheduled.json) | rssfeedread, htmlextract | 5 |
| 27 | [Receive updates when a new activity gets created and tweet a](workflows/1211_Twitter_Strava_Create_Triggered.json) | stravatrigger, twitter | 2 |
| 28 | [1336 Strapi Webhook Automate Webhook](workflows/1336_Strapi_Webhook_Automate_Webhook.json) | googlecloudnaturallanguage, twitter, strapi, interval | 14 |
| 29 | [Youtube Searcher](workflows/1788_Postgres_Code_Automation_Webhook.json) | youtube, postgres | 21 |
| 30 | [Wordpress Form to Mautic](workflows/1892_Noop_Mautic_Automation_Webhook.json) | mautic | 10 |

> **+1 more workflows in this category** — browse the `workflows/` folder

## 🗄️ Data & Database

PostgreSQL, MySQL, Redis, Supabase, and BigQuery workflows. ETL pipelines, data sync, and automated reports.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [0023 HTTP Googlebigquery Automation Scheduled](workflows/0023_HTTP_Googlebigquery_Automation_Scheduled.json) | googlebigquery | 4 |
| 2 | [0139 HTTP Mysql Automation Webhook](workflows/0139_HTTP_Mysql_Automation_Webhook.json) | postgres, mysql | 6 |
| 3 | [extract_swifts](workflows/0178_Functionitem_Executecommand_Automation_Webhook.json) | uproc, writebinaryfile, executecommand, mongodb, readbinaryfile, htmlextract | 23 |
| 4 | [0284 Manual Readbinaryfile Create Triggered](workflows/0284_Manual_Readbinaryfile_Create_Triggered.json) | readbinaryfile, mysql | 4 |
| 5 | [0292 Manual Stickynote Export Triggered](workflows/0292_Manual_Stickynote_Export_Triggered.json) | mysql | 5 |
| 6 | [0317 Manual Movebinarydata Process Triggered](workflows/0317_Manual_Movebinarydata_Process_Triggered.json) | writebinaryfile, xml, mysql | 13 |
| 7 | [0352 Readbinaryfile Spreadsheetfile Create](workflows/0352_Readbinaryfile_Spreadsheetfile_Create.json) | postgres, readbinaryfile | 3 |
| 8 | [0376 Webhook Code Create Webhook](workflows/0376_Webhook_Code_Create_Webhook.json) | mysql | 5 |
| 9 | [0387 Redis Code Create Scheduled](workflows/0387_Redis_Code_Create_Scheduled.json) | redis, microsoftteams | 23 |
| 10 | [0460 Postgres Filter Import Scheduled](workflows/0460_Postgres_Filter_Import_Scheduled.json) | postgres, n8n | 6 |
| 11 | [0497 Redis Schedule Import Scheduled](workflows/0497_Redis_Schedule_Import_Scheduled.json) | redis | 17 |
| 12 | [0632 Webhook Manual Create Webhook](workflows/0632_Webhook_Manual_Create_Webhook.json) | supabase | 21 |
| 13 | [0747 Writebinaryfile Spreadsheetfile Automate](workflows/0747_Writebinaryfile_Spreadsheetfile_Automate.json) | postgres, writebinaryfile | 3 |
| 14 | [Postgres Data Ingestion](workflows/0822_Cron_Postgres_Automation_Scheduled.json) | postgres | 3 |
| 15 | [0831 Wait Code Monitor Webhook](workflows/0831_Wait_Code_Monitor_Webhook.json) | redis | 18 |
| 16 | [0835 Microsoftoutlook Schedule Automation Scheduled](workflows/0835_Microsoftoutlook_Schedule_Automation_Scheduled.json) | microsoftoutlook, mysql | 6 |
| 17 | [Monitoring and alerting](workflows/0842_Twilio_Cron_Send_Scheduled.json) | postgres, twilio | 5 |
| 18 | [Prevent concurrent workflow runs using Redis](workflows/0925_Stopanderror_Wait_Automate_Triggered.json) | redis | 43 |
| 19 | [PostgreSQL export to CSV](workflows/0930_Manual_Spreadsheetfile_Export_Triggered.json) | postgres | 4 |
| 20 | [0962 Manual Postgres Automate Triggered](workflows/0962_Manual_Postgres_Automate_Triggered.json) | postgres | 2 |
| 21 | [0982 Manual Mongodb Automate Triggered](workflows/0982_Manual_Mongodb_Automate_Triggered.json) | mongodb | 3 |
| 22 | [1025 Manual Redis Automate Triggered](workflows/1025_Manual_Redis_Automate_Triggered.json) | redis | 2 |
| 23 | [1055 Manual Mysql Automation Triggered](workflows/1055_Manual_Mysql_Automation_Triggered.json) | mysql | 4 |
| 24 | [1056 Manual Postgres Automate Triggered](workflows/1056_Manual_Postgres_Automate_Triggered.json) | postgres | 4 |
| 25 | [n8n_mysql_purge_history_greater_than_10_days](workflows/1076_Manual_Cron_Automation_Scheduled.json) | mysql | 3 |
| 26 | [2. Refresh Pipedrive tokens](workflows/1504_Stopanderror_Code_Automation_Webhook.json) | supabase | 29 |
| 27 | [Compare 2 SQL datasets](workflows/1851_Manual_Comparedatasets_Automation_Triggered.json) | comparedatasets, mysql | 5 |
| 28 | [New Ticket Alerts to Teams](workflows/1933_Redis_Code_Create_Webhook.json) | redis, microsoftteams | 8 |
| 29 | [How to automatically import CSV files into postgres](workflows/1961_Manual_Readbinaryfile_Import_Triggered.json) | readbinaryfile, postgres | 4 |

## ⚙️ DevOps & GitHub

GitHub, AWS S3, SQS, and CI/CD automations. Automate deployments, monitor repos, and manage cloud resources.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [0021 HTTP Awssqs Automation Scheduled](workflows/0021_HTTP_Awssqs_Automation_Scheduled.json) | awssqs | 4 |
| 2 | [0033 HTTP Mqtt Automation Webhook](workflows/0033_HTTP_Mqtt_Automation_Webhook.json) | mqtt | 4 |
| 3 | [0049 Manual Awss3 Automate Triggered](workflows/0049_Manual_Awss3_Automate_Triggered.json) | awss3, awstranscribe | 3 |
| 4 | [0060 Travisci GitHub Automate Triggered](workflows/0060_Travisci_GitHub_Automate_Triggered.json) | travisci, githubtrigger | 4 |
| 5 | [0093 HTTP GitHub Create Scheduled](workflows/0093_HTTP_GitHub_Create_Scheduled.json) | github | 11 |
| 6 | [Automate assigning GitHub issues](workflows/0096_Noop_GitHub_Automate_Triggered.json) | githubtrigger, github | 10 |
| 7 | [Steam + CF Report](workflows/0097_Executecommand_Mailgun_Automation_Webhook.json) | mailgun, executecommand | 9 |
| 8 | [0108 Noop GitHub Create Triggered](workflows/0108_Noop_GitHub_Create_Triggered.json) | githubtrigger, github | 11 |
| 9 | [0112 Manual Awstextract Automate Triggered](workflows/0112_Manual_Awstextract_Automate_Triggered.json) | awss3, awstextract | 3 |
| 10 | [0135 GitHub Cron Create Scheduled](workflows/0135_GitHub_Cron_Create_Scheduled.json) | gitlab, github | 6 |
| 11 | [0190 Executecommand Functionitem Automate](workflows/0190_Executecommand_Functionitem_Automate.json) | executecommand | 3 |
| 12 | [Tools / Backup Gitlab](workflows/0200_Manual_Executecommand_Export_Scheduled.json) | executecommand | 7 |
| 13 | [0279 Zendesk GitHub Create Webhook](workflows/0279_Zendesk_GitHub_Create_Webhook.json) | zendesk, github | 7 |
| 14 | [0289 GitHub Stickynote Update Triggered](workflows/0289_GitHub_Stickynote_Update_Triggered.json) | homeassistant, githubtrigger | 4 |
| 15 | [[n8n] Advanced URL Parsing and Shortening Workflow - Switchy](workflows/0392_Stopanderror_GitHub_Automate_Webhook.json) | github | 56 |
| 16 | [0516 Code GitHub Create Scheduled](workflows/0516_Code_GitHub_Create_Scheduled.json) | github, executecommand | 24 |
| 17 | [0553 Code Schedule Send Scheduled](workflows/0553_Code_Schedule_Send_Scheduled.json) | ftp, mqtttrigger, mqtt | 6 |
| 18 | [0560 Splitout Filter Import Webhook](workflows/0560_Splitout_Filter_Import_Webhook.json) | spotify, mqtttrigger | 26 |
| 19 | [0592 Stopanderror Awss3 Automation Webhook](workflows/0592_Stopanderror_Awss3_Automation_Webhook.json) | awss3 | 17 |
| 20 | [0593 Awss3 Compression Automate Triggered](workflows/0593_Awss3_Compression_Automate_Triggered.json) | compression, awss3 | 6 |
| 21 | [Backup workflows to git repository](workflows/0628_Code_Schedule_Export_Scheduled.json) | github, n8n | 17 |
| 22 | [0667 Code GitHub Create Scheduled](workflows/0667_Code_GitHub_Create_Scheduled.json) | github, n8n | 23 |
| 23 | [0718 Code GitHub Create Scheduled](workflows/0718_Code_GitHub_Create_Scheduled.json) | github, n8n | 25 |
| 24 | [N8N Español - Ejemplos](workflows/0737_Manual_Executecommand_Automation_Triggered.json) | executecommand | 7 |
| 25 | [0799 Splitout Executecommand Automate Scheduled](workflows/0799_Splitout_Executecommand_Automate_Scheduled.json) | executecommand, n8ntrigger | 7 |
| 26 | [0853 Manual Executecommand Automate Triggered](workflows/0853_Manual_Executecommand_Automate_Triggered.json) | readbinaryfiles, executecommand | 4 |
| 27 | [Receive messages for a MQTT queue](workflows/0992_Mqtt_Send_Triggered.json) | mqtttrigger | 1 |
| 28 | [0997 GitHub Automate Triggered](workflows/0997_GitHub_Automate_Triggered.json) | githubtrigger | 1 |
| 29 | [new](workflows/1066_Manual_GitHub_Create_Triggered.json) | github | 2 |
| 30 | [Dashboard](workflows/1107_HTTP_GitHub_Automation_Webhook.json) | github | 24 |

> **+11 more workflows in this category** — browse the `workflows/` folder

## 📂 Files & Productivity

File processing, Outlook, Calendly, and Dropbox workflows. Automate document handling and scheduling.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [screenshot](workflows/0031_Functionitem_Dropbox_Automation_Webhook.json) | uproc, dropbox, awsses | 10 |
| 2 | [0153 HTTP Dropbox Update Webhook](workflows/0153_HTTP_Dropbox_Update_Webhook.json) | dropbox, xml | 5 |
| 3 | [Create, add an attachment, and send a draft using the Micros](workflows/0312_Manual_HTTP_Create_Webhook.json) | microsoftoutlook | 5 |
| 4 | [Capture Website Screenshots with Bright Data Web Unlocker an](workflows/0338_Manual_Stickynote_Export_Webhook.json) | readwritefile | 6 |
| 5 | [0396 Datetime Schedule Automation Scheduled](workflows/0396_Datetime_Schedule_Automation_Scheduled.json) | dropbox, n8n | 17 |
| 6 | [0501 Manual Extractfromfile Send Webhook](workflows/0501_Manual_Extractfromfile_Send_Webhook.json) | HTTP/Webhook | 10 |
| 7 | [0507 Manual Stickynote Automation Webhook](workflows/0507_Manual_Stickynote_Automation_Webhook.json) | readwritefile | 5 |
| 8 | [0508 Converttofile Manual Process Triggered](workflows/0508_Converttofile_Manual_Process_Triggered.json) | n8n | 7 |
| 9 | [0509 Manual Stickynote Automation Webhook](workflows/0509_Manual_Stickynote_Automation_Webhook.json) | readwritefile | 6 |
| 10 | [0513 Manual Stickynote Automation Webhook](workflows/0513_Manual_Stickynote_Automation_Webhook.json) | readwritefile | 5 |
| 11 | [0514 Manual Stickynote Automation Webhook](workflows/0514_Manual_Stickynote_Automation_Webhook.json) | readwritefile | 5 |
| 12 | [0517 HTTP Stickynote Process Webhook](workflows/0517_HTTP_Stickynote_Process_Webhook.json) | readwritefile | 5 |
| 13 | [0519 Code Manual Create Webhook](workflows/0519_Code_Manual_Create_Webhook.json) | readwritefile | 6 |
| 14 | [0521 Manual Stickynote Automation Webhook](workflows/0521_Manual_Stickynote_Automation_Webhook.json) | readwritefile | 5 |
| 15 | [0522 Manual Stickynote Automation Webhook](workflows/0522_Manual_Stickynote_Automation_Webhook.json) | readwritefile | 5 |
| 16 | [0561 Gitlab Code Create Triggered](workflows/0561_Gitlab_Code_Create_Triggered.json) | gitlab, n8n | 21 |
| 17 | [0582 Wait Dropbox Create Webhook](workflows/0582_Wait_Dropbox_Create_Webhook.json) | dropbox | 20 |
| 18 | [0640 Wait Splitout Create Scheduled](workflows/0640_Wait_Splitout_Create_Scheduled.json) | readwritefile | 19 |
| 19 | [0642 HTTP Extractfromfile Process Webhook](workflows/0642_HTTP_Extractfromfile_Process_Webhook.json) | HTTP/Webhook | 11 |
| 20 | [0660 Calendly Noop Create Triggered](workflows/0660_Calendly_Noop_Create_Triggered.json) | klicktipp, calendlytrigger | 19 |
| 21 | [0661 Calendly Noop Create Triggered](workflows/0661_Calendly_Noop_Create_Triggered.json) | klicktipp, calendlytrigger | 19 |
| 22 | [0673 Limit Code Create Webhook](workflows/0673_Limit_Code_Create_Webhook.json) | microsoftoutlooktrigger | 41 |
| 23 | [0779 Manual HTTP Create Webhook](workflows/0779_Manual_HTTP_Create_Webhook.json) | readwritefile | 3 |
| 24 | [0790 Splitout Schedule Create Webhook](workflows/0790_Splitout_Schedule_Create_Webhook.json) | readwritefile | 24 |
| 25 | [0798 Splitout Code Automation Webhook](workflows/0798_Splitout_Code_Automation_Webhook.json) | mergepdfs, readwritefile | 7 |
| 26 | [0802 Webhook Nocodb Create Webhook](workflows/0802_Webhook_Nocodb_Create_Webhook.json) | nocodb, dropbox | 20 |
| 27 | [0887 Manual Stickynote Create Webhook](workflows/0887_Manual_Stickynote_Create_Webhook.json) | HTTP/Webhook | 11 |
| 28 | [0914 Webhook Respondtowebhook Create Webhook](workflows/0914_Webhook_Respondtowebhook_Create_Webhook.json) | HTTP/Webhook | 6 |
| 29 | [1009 Calendly Automate Triggered](workflows/1009_Calendly_Automate_Triggered.json) | calendlytrigger | 1 |
| 30 | [1078 Manual Dropbox Automation Webhook](workflows/1078_Manual_Dropbox_Automation_Webhook.json) | dropbox | 5 |

> **+19 more workflows in this category** — browse the `workflows/` folder

## 🔧 General Automation

HTTP requests, webhooks, cron jobs, and multi-purpose automation patterns.

| # | Workflow | Services | Nodes |
|---|----------|----------|-------|
| 1 | [Complete Guide to Setting Up and Generating TOTP Codes in n8](workflows/0002_Manual_Totp_Automation_Triggered.json) | totp | 2 |
| 2 | [0003 Bitwarden Automate](workflows/0003_Bitwarden_Automate.json) | bitwarden | 4 |
| 3 | [0006 Openweathermap Cron Automate Scheduled](workflows/0006_Openweathermap_Cron_Automate_Scheduled.json) | openweathermap, plivo | 3 |
| 4 | [Create a new task in Todoist](workflows/0007_Manual_Todoist_Create_Triggered.json) | todoist | 2 |
| 5 | [0009 Process](workflows/0009_Process.json) | HTTP/Webhook | 5 |
| 6 | [0010 Writebinaryfile Create](workflows/0010_Writebinaryfile_Create.json) | writebinaryfile | 3 |
| 7 | [Loading data into a spreadsheet](workflows/0013_Manual_Noop_Import_Triggered.json) | HTTP/Webhook | 4 |
| 8 | [Insert data into a new row for a table in Coda](workflows/0014_Manual_Coda_Create_Triggered.json) | coda | 3 |
| 9 | [Send updates about the position of the ISS every minute to a](workflows/0015_HTTP_Cron_Update_Webhook.json) | amqp | 4 |
| 10 | [verify email](workflows/0019_Manual_Uproc_Send_Triggered.json) | uproc | 4 |
| 11 | [0022 Manual Webflow Automate Triggered](workflows/0022_Manual_Webflow_Automate_Triggered.json) | webflow | 4 |
| 12 | [Look up a person using their email in Clearbit](workflows/0024_Manual_Clearbit_Send_Triggered.json) | clearbit | 2 |
| 13 | [location_by_ip](workflows/0025_Manual_Uproc_Automation_Triggered.json) | uproc, awsses | 6 |
| 14 | [Create a new member, update the information of the member, c](workflows/0029_Manual_Orbit_Create_Triggered.json) | orbit | 5 |
| 15 | [0032 Manual Filemaker Automate Triggered](workflows/0032_Manual_Filemaker_Automate_Triggered.json) | filemaker | 5 |
| 16 | [0034 Code Filter Create Scheduled](workflows/0034_Code_Filter_Create_Scheduled.json) | spotify, nocodb | 30 |
| 17 | [Get a volume and add it to your bookshelf](workflows/0037_Manual_Googlebooks_Create_Triggered.json) | googlebooks | 4 |
| 18 | [Get all the stories starting with `release` and publish them](workflows/0046_Manual_Storyblok_Import_Triggered.json) | storyblok | 3 |
| 19 | [0050 Uptimerobot Automate](workflows/0050_Uptimerobot_Automate.json) | uptimerobot | 3 |
| 20 | [0051 Manual Microsofttodo Automate Triggered](workflows/0051_Manual_Microsofttodo_Automate_Triggered.json) | microsofttodo | 4 |
| 21 | [0052 Manual Git Automate Triggered](workflows/0052_Manual_Git_Automate_Triggered.json) | git | 5 |
| 22 | [Standup Bot - Initialize](workflows/0054_Manual_Writebinaryfile_Automate_Triggered.json) | writebinaryfile | 4 |
| 23 | [Get Company by Name](workflows/0056_Manual_Uproc_Import_Triggered.json) | uproc | 4 |
| 24 | [Receive updates when a new account is added by an admin in A](workflows/0057_Activecampaign_Create_Triggered.json) | activecampaigntrigger | 1 |
| 25 | [Standup Bot - Read Config](workflows/0058_Manual_Readbinaryfile_Automate_Triggered.json) | readbinaryfile | 3 |
| 26 | [Get DNS entries](workflows/0063_Manual_Uproc_Import_Triggered.json) | uproc | 3 |
| 27 | [Standup Bot - Override Config](workflows/0064_Manual_Writebinaryfile_Automate_Triggered.json) | writebinaryfile | 3 |
| 28 | [Send daily weather updates via a message in Line](workflows/0065_Openweathermap_Line_Update_Scheduled.json) | openweathermap, line | 3 |
| 29 | [Verify phone numbers](workflows/0067_Manual_Uproc_Automation_Triggered.json) | uproc | 4 |
| 30 | [Send daily weather updates via a message using the Gotify no](workflows/0072_Openweathermap_Cron_Update_Scheduled.json) | gotify, openweathermap | 3 |

> **+486 more workflows in this category** — browse the `workflows/` folder

---

## 💼 Use Cases & Monetization

This collection is perfect for:

- **Freelancers**: Offer n8n automation services on Upwork/Fiverr using these as starting points
- **SaaS builders**: Use workflows as foundations for automation products
- **Consultants**: Sell packaged automation solutions to businesses
- **Developers**: Learn automation patterns and integration best practices

## 🤝 Contributing

Contributions welcome! To add a workflow:
1. Export your n8n workflow as JSON
2. Name it following the pattern: `CATEGORY_Service1_Service2_Description.json`
3. Submit a pull request

## 📄 License

MIT License — free to use, modify, and distribute.

---

⭐ **If this helps you, please star the repository!**