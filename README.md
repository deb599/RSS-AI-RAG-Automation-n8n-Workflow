# RSS-AI-RAG-Automation---n8n-Workflow

# Overview
This n8n workflow automates the process of curating and analyzing content from RSS feeds with the aim of filtering and classifying information related to AI risk topics. It uses a combination of automation pipelines and AI-powered analysis to parse incoming RSS data, assess risk relevance, and organize content for downstream processing or alerting.

# Key Features
* RSS Feed Integration: Automatically fetches and processes multiple RSS feeds to gather the latest content on AI-related topics.

* Content Parsing and Filtering: Uses custom code to identify and assess risk factors in the gathered content using relevant key words.

* Classification and Summarization: Summarizes large volumes of text and classifies them into relevant categories using generative AI.

* Workflow Automation: Integrates REST APIs, HTTP requests, and custom JavaScript nodes to orchestrate processing with no-code/low-code design.

* Scalable and Adaptable: Designed for flexible configurations to add/remove feeds, update classification rules, or extend AI model integrations.

* Multi-Agent Tool Integration: Leverages multi-agent orchestration for adaptive problem solving and dynamic content curation.

# How It Works
* Trigger: The workflow starts by user entering inputs on the no. of days of RSS feed to fetch and link to Google sheets as per template

* Fetch: Go through configured RSS feeds to fetch new content items.

* Filtering and Classification: Filters out low-risk or irrelevant content, classifies key information, and summarizes text for quick insight.

* Output and Notification: Outputs results to chosen destination.

# Technologies and Tools
* n8n for workflow automation

* AI models for text classification and summarization

* RSS feed monitoring and integration

* REST API and HTTP requests for external tool connections

* Custom JavaScript function nodes for advanced logic

* Multi-agent orchestration methods for dynamic problem solving

# Usage and Customization
* This workflow is ideal for researchers, analysts, or organizations monitoring AI safety and risk-related content from various sources. It provides a robust framework to streamline information retrieval and focus attention on the most critical insights.

* Customization points include:

- Adding or updating RSS feeds via Google sheets

- Tailoring filtering thresholds via chat input

# Security and Privacy
Sensitive endpoints and credentials are expected to be configured securely by the user.

# Screenshots and Visuals
<img width="826" height="329" alt="Screenshot 2025-10-01 at 11 14 22 am" src="https://github.com/user-attachments/assets/07829a97-4e91-4b1b-aa15-581ebd93ee9f" />

Want to give it a spin? Just fill out the form below — it will trigger the workflow so you can see it in action:

http://localhost:5678/form/8f4fa592-86fe-46d8-9da9-ba82086f54cf

For feedback or questions, please use this form: https://forms.gle/REoHYFmh5xGVpH4w8

* json file and RSS list available for purchase at https://automationgirl.gumroad.com/l/iupjb
# Author
Debasmita Mukherjee
