
# AI Summarizer with Claude AI Sonnet 3.5

This project is an experimental AI summarizer built using Claude AI Sonnet 3.5. It integrates Cloudflare Worker for backend deployment and leverages the Claude AI Anthropic API to generate desired summarization results.
# Features
AI Summarization: Uses Claude AI Sonnet 3.5 to generate high-quality summaries of given text.
Cloudflare Worker Backend: Backend deployment via Cloudflare Workers ensures low-latency and highly scalable performance.
API Integration: Connects to the Claude AI Anthropic API to generate summarizations.
## Getting Started
To get the project up and running on your local machine, follow the steps below:
### Prerequisites
Before you begin, ensure you have the following:
- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/)
- A **Claude AI Anthropic API key**. You can obtain this key by signing up for access to the Claude AI API from [Anthropic](https://www.anthropic.com/). 
### Installation
- npm install
- CLAUDE_API_KEY=your_api_key_here (Create a .env file in the root directory of the project and add the following line (replacing your_api_key_here with your actual API key)
- npm start
### Cloudflare Commands for setting up the worker
- npm create cloudflare@latest -- my-summarizer (create new worker)
- npx wrangler dev (setup Wrangler ClI)
- npx wrangler deploy (deploy your project)
### Key Changes:
1. **API Key Prerequisite**: Added instructions for obtaining and setting the Claude AI Anthropic API key.
2. **.env Configuration**: Added a step to set the API key in a `.env` file, which is a common practice for storing sensitive information securely.
Make sure you replace `your_api_key_here` with the actual API key.
For more reference regarding this project, Visit [Scrimba](https://v2.scrimba.com/claude-ai-c09gsmkso3)