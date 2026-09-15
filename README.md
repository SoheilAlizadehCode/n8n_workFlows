n8n Workflows 🚀

A curated collection of practical and production-oriented n8n workflows for business automation, AI-powered processes, data processing, lead generation, monitoring, notifications, and third-party service integrations.

The goal of this repository is to provide ready-to-import n8n workflows that can be adapted and reused in real-world projects.

✨ What You'll Find

This repository contains workflows covering a wide range of automation use cases:

🤖 AI-powered automation and multi-agent workflows

📊 Data processing and Google Sheets automation

📧 Email automation and notifications

📱 Telegram and WhatsApp integrations

🔎 SEO auditing and visibility monitoring

🎯 Lead generation and prospecting

🕵️ Competitor intelligence and monitoring

🛒 Shopify order automation

💰 Invoice and payment automation

📈 Crypto price and market monitoring

🌐 Web scraping and data extraction

💼 LinkedIn automation and monitoring

📋 Trello and Google Forms integrations

🔔 Slack and Telegram notifications

🌍 Website change detection and AI summaries

📁 Workflows

Some of the workflows currently included in this repository:

Workflow	Use Case
AI Investment Scenario Simulator	AI-powered investment scenario analysis
Abandoned Checkout Recovery	Recover abandoned checkouts
Automated Crypto Coin Crash Tracker	Monitor crypto price movements
BuiltWith to Trello	Send technology/company data to Trello
Competitor Intelligence Radar	Monitor competitors
Create Customers	Customer creation automation
Crypto News Risk Monitor	Analyze crypto news and send alerts
Crypto Price Alert Bot	Crypto alerts via Telegram and Google Sheets
Customer Payment Reminder Scheduler	Automated payment reminders
SEO Audit Generator	Generate SEO audit reports using AI
Google Maps Business Scraper	Extract business information
Intelligent Invoice Data Capture	Extract and process invoice data
LinkedIn Comments to Leads	Extract and enrich potential leads
TikTok Creator Growth Monitor	Track creator growth
Precision Prospector	Automated prospecting
Shopify Orders Monitor	Query Shopify orders through Telegram
WhatsApp Fee Reminders	Send payment reminders through WhatsApp
LinkedIn Profile Change Tracker	Monitor LinkedIn profile changes
G2 Review Monitor	Track competitor reviews
AI Research Article Pipeline	Generate research-backed articles
Website Change Monitor	Detect website changes and summarize them with AI
Google Forms → Trello	Create Trello cards from form submissions

The repository is continuously evolving, and new workflows may be added over time.

🧩 Requirements

Most workflows require:

n8n

Appropriate API credentials for the services used by each workflow

The required n8n nodes or community nodes

API keys for external services where applicable

Depending on the workflow, you may also need services such as:

Google Sheets

Gmail

Telegram

Slack

WhatsApp

Shopify

LinkedIn

Apify

Bright Data

Firecrawl

Trello

OpenAI

Google Gemini

Gainium

KSeF

Not every workflow requires all of these services.

🚀 Getting Started
1. Install n8n

If you don't already have n8n installed, follow the official n8n documentation:

https://docs.n8n.io/

You can run n8n locally, using Docker, or through n8n Cloud.

2. Clone the repository
git clone https://github.com/SoheilAlizadehCode/n8n_workFlows.git
cd n8n_workFlows

3. Import a workflow

Open your n8n instance and import the desired .json workflow.

In n8n:

Workflows → Import from File

Then select one of the JSON files from this repository.

4. Configure credentials

After importing a workflow, configure the required credentials and environment-specific settings.

For example:

API keys

OAuth credentials

Telegram Bot tokens

Google credentials

Shopify credentials

Database connections

Webhook URLs

5. Review before activation

Before enabling a workflow in production:

Review all nodes.

Configure credentials.

Check API endpoints.

Review input and output data.

Test the workflow manually.

Configure error handling where necessary.

Enable the workflow.

🔐 Security

Never commit secrets or credentials to this repository.

Do not store the following inside workflow files:

API keys
Access tokens
Passwords
OAuth secrets
Private credentials
Webhook secrets
Database credentials


Use n8n's credential management system or environment variables instead.

If you accidentally expose a credential, revoke and rotate it immediately.

⚠️ Important Notes

These workflows are provided as reusable automation examples.

Before using a workflow in production, make sure you understand:

The APIs being used

The data being collected or processed

API rate limits

Authentication requirements

Third-party service terms

Privacy and data protection requirements

Potential costs associated with external APIs

Some workflows depend on third-party services and may require changes if those services modify their APIs.

🛠️ Customization

n8n workflows are highly customizable.

You can modify:

Triggers

API endpoints

AI models

Prompts

Filters

Data transformations

Notification channels

Database connections

Scheduling

Error handling

Use these workflows as a starting point and adapt them to your own environment and requirements.

🤝 Contributing

Contributions are welcome!

If you have a useful n8n workflow that could benefit others:

Fork the repository.

Create a new branch.

Add your workflow as a .json file.

Make sure no credentials or secrets are included.

Add a clear description of the workflow.

Test the workflow before submitting it.

Open a Pull Request.

Contribution Guidelines

Please make sure contributed workflows:

Do not contain secrets or personal credentials.

Have descriptive names.

Are reasonably documented.

Follow a clear workflow structure.

Include required setup information.

Are tested before submission.

📚 Useful Resources

n8n

n8n Documentation

n8n Community

⭐ Support

If you find these workflows useful, consider giving the repository a ⭐ on GitHub.

Feel free to open an Issue if you find a bug, have a question, or have an idea for a new workflow.

📄 License

Please check the repository's license before using, modifying, or redistributing these workflows.

Made with ❤️ and n8n
