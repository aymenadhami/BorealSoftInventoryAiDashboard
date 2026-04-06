# Boreal Soft — Inventory Dashboard Demo 🌲

A front-end demonstration of a smart, interactive inventory and sales dashboard featuring an integrated AI assistant. 

**Note on this Demo:** This repository contains a standalone, client-side demonstration of the Boreal Soft dashboard. To make it easily viewable without backend dependencies, the live ERP connection has been removed and replaced with sample data. Additionally, the production version's locally hosted Llama LLM—which powers the AI chat—has been replaced with a simulated, rule-based JavaScript engine to demonstrate the UX and intent-parsing features.

## 🚀 Features

### 1. Interactive Data Visualization
* **Inventory On Hand:** Track product distribution by units, categories (Accounting, Tax, ERP), and license counts.
* **Warehouse Breakdown:** Monitor stock levels across multiple locations (Cloud-East, Cloud-West, On-Prem DC, Partner Hub).
* **Sales & Turnover:** Analyze product performance, margins, turnover rates, and projected stockout risks.
* **Dynamic Charts:** Powered by [Chart.js](https://www.chartjs.org/), featuring responsive donut and bar charts for quick KPI scanning.

### 2. "AI" Chat Assistant (Simulated NLP)
The demo includes a bottom-right chat widget that mimics the production app's Llama integration. You can ask natural language questions to query the mock data. Try asking:
* *"Top 5 by revenue"*
* *"What's in Cloud-East?"*
* *"Show me stockout risks"*
* *"Margin of QuickLedger Pro"*

**Smart Chat UI:** The bot doesn't just return text; it can generate inline charts and data tables directly within the chat stream.
**Fullscreen Expansion & Export:** Click on any chart or table generated in the chat to open a full-screen overlay, complete with options to download the data as a PNG or CSV.

## 🛠️ Tech Stack (Demo Version)
* **HTML5 / CSS3:** Custom, responsive styling with a modern dark theme and CSS variables. No heavy CSS frameworks.
* **Vanilla JavaScript:** Handles all UI state, tab switching, and rule-based chat parsing. 
* **Chart.js (v4.4.1):** Used for all data visualizations.

## 🏢 Production Architecture Context
While this demo is purely static, the production version of this application operates as a full-stack internal tool:
* **Live ERP Integration:** Fetches real-time inventory, sales, and logistics data directly from the company's Enterprise Resource Planning system.
* **Local LLM Backend:** The chatbot is powered by a locally hosted Llama server, ensuring sensitive company data remains entirely on-premise while providing deep, context-aware data analysis and natural language querying.

## 💻 Usage
Since this is a static demo, no build steps, servers, or API keys are required.

1. Clone or download this repository.
2. Open `borealsoftdemo.html` in any modern web browser.
3. Explore the tabs, interact with the charts, and test out the chat widget!

## 📄 License
[Insert License Here - e.g., MIT, Proprietary, etc.]
