# Open-Source LLM Skill Downloader

**An automated framework to equip Large Language Models (LLMs) with optimized, open-source capability skills.** This project allows you to issue structured commands to various LLMs, prompting them to fetch, install, and execute highly efficient modular skills. 

The core goal is to optimize model efficiency, delivering **accurate answers using fewer tokens** through precise prompt engineering, semantic routing, and specialized execution micro-skills.

## 🚀 Key Features

* **Cross-LLM Compatibility:** Standardized syntax to dispatch skill-download directives across OpenAI, Anthropic, Gemini, and open-weight models (Llama, Mistral).
* **Token Efficiency:** Minimizes prompt bloat by modularizing capabilities so models only call the logic they need.
* **Open-Source Repository:** Easily expandable ecosystem where developers can contribute custom operational skills.

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/llm-skill-downloader.git
   cd llm-skill-downloader
   ```

2. **Configure your LLM Environment:**
   Export your preferred model keys or local execution endpoints:
   ```bash
   export OPENAI_API_KEY="your_key"
   export ANTHROPIC_API_KEY="your_key"
   ```

3. **Usage Example:**
   Pass the initialization prompt to your agent to load the core catalog:
   ```text
   "System Command: Initialize Skill Registry from skills.md. Activate token-conservation protocol."
   ```

## 📜 License
Distributed under the MIT License. See `LICENSE` for details.
