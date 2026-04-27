# 🛡️ Prompt Injections DB

<div align="center">
  <img src="https://img.shields.io/badge/Maintained-Yes-success.svg" alt="Maintained Yes" />
  <img src="https://img.shields.io/badge/Security-Critical-red.svg" alt="Security Critical" />
  <p><strong>A curated, open-source database of prompt injections and jailbreaks for testing LLM security.</strong></p>
</div>

## ✨ Overview

As Large Language Models (LLMs) become integrated into core business systems, securing them against adversarial inputs is critical. **Prompt Injections DB** is a comprehensive, structured dataset of known jailbreaks, prompt injections, and adversarial attack vectors designed specifically for red-teaming AI applications.

## 🗃️ Database Structure

The database is categorized by attack vectors:

- **System Prompt Leaks**: Techniques to extract the underlying instructions.
- **Roleplay/Persona Jailbreaks**: Bypassing safety rails by forcing the AI into a persona (e.g., DAN).
- **Format Overrides**: Using XML/JSON structures or code blocks to confuse the parser.
- **Context Window Flooding**: Hiding malicious payloads within large chunks of benign text.
- **Multi-lingual Evasion**: Bypassing English-only safety filters using translation/transliteration.

## 🚀 How to Use (Red Teaming)

You can use this repository to evaluate the robustness of your AI agents or RAG pipelines.

1.  **Clone the DB**:
    ```bash
    git clone https://github.com/RanaAhmar/prompt-injections-db.git
    cd prompt-injections-db
    ```

2.  **Integrate with Testing Frameworks**:
    Load the JSON files located in `./payloads/` into your automated testing suites (e.g., Pytest, Jest) to fuzz your LLM endpoints.

*Note: For educational and defensive security purposes only.*

## 🤝 Contributing

We welcome submissions of new, novel attack vectors! Please review our `CONTRIBUTING.md` guidelines before submitting a Pull Request to ensure the payload is categorized correctly.








---

## 🚀 Discover More from Stackaura

If you found this tool useful, check out our other high-performance web utilities and follow **Ahmar Hussain** for more open-source excellence.

### 🌟 Featured Projects
- **[Stackaura Hub](https://github.com/RanaAhmar/stackaura-hub)** - The central index for all 100 repositories.
- **[Free LLM APIs](https://github.com/RanaAhmar/free-llm-apis)** - A curated list of zero-cost AI endpoints.
- **[Awesome MCP Servers](https://github.com/RanaAhmar/awesome-mcp-servers)** - The ultimate collection of Model Context Protocol implementations.
- **[System Design Cheatsheet](https://github.com/RanaAhmar/system-design-cheatsheet)** - Master complex architectures in minutes.
- **[Next.js SaaS Starter](https://github.com/RanaAhmar/nextjs-saas-starter)** - The fastest way to launch your next product.

### 🔗 Stay Connected
- **Website:** [stackaura.com](https://www.stackaura.com/)
- **LinkedIn:** [Ahmar Hussain](https://www.linkedin.com/in/ahmar204/)
- **Facebook:** [Ahmar Hussain](https://www.facebook.com/Ahmar204)
- **GitHub:** [@RanaAhmar](https://github.com/RanaAhmar)

---








---
### 🌟 Part of the [Stackaura](https://github.com/RanaAhmar) Ecosystem
*Empowering developers with automated tools and high-performance solutions.*

**Explore more:**
- 🚀 [All Projects](https://github.com/RanaAhmar?tab=repositories)
- 🛠️ [Daily Coding Tips](https://github.com/RanaAhmar/daily-coding-tips)
- 📊 [Profile Dashboard](https://github.com/RanaAhmar/RanaAhmar)

*If you find this project useful, please consider giving it a star! ⭐*


---
### 🌟 Part of the [Stackaura](https://github.com/RanaAhmar) Ecosystem
*Empowering developers with automated tools and high-performance solutions.*

**Explore more:**
- 🚀 [All Projects](https://github.com/RanaAhmar?tab=repositories)
- 🛠️ [Daily Coding Tips](https://github.com/RanaAhmar/daily-coding-tips)
- 📊 [Profile Dashboard](https://github.com/RanaAhmar/RanaAhmar)

*If you find this project useful, please consider giving it a star! ⭐*
