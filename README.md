# Awesome GUI Agent

<div align="center">
  <p align="center">
    <a href="#1-surveys-and-overviews">🧠 Surveys</a> |
    <a href="#5-benchmarks-and-evaluation-suites">🧪 Benchmarks</a> |
    <a href="#7-frameworks-and-tooling">🛠️ Tooling</a> |
    <a href="#10-blogs-talks-and-community-updates">📰 Community</a>
  </p>
  <p align="center">
    <a href="https://opensource.org/licenses/MIT"><img alt="License" src="https://img.shields.io/badge/License-MIT-green.svg"></a>
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    <img alt="Maintained" src="https://img.shields.io/badge/status-active-blue.svg">
  </p>
</div>

An awesome-style collection of papers, datasets, benchmarks, frameworks, and community resources for building **Graphical User Interface (GUI) Agents**: systems that can perceive interfaces, plan multi-step actions, and execute workflows across desktop, mobile, and web environments. The list emphasizes work released through October 2024.

> 💡 *Looking for something to add?* Please check the [contributing guidelines](#11-contributing) and open an issue or pull request.

---

### Contents

* [📢 News](#-news)
* [1. Surveys and Overviews](#1-surveys-and-overviews)
* [2. Foundational Systems](#2-foundational-systems)
  * [2.1 Early Web and Desktop Agents](#21-early-web-and-desktop-agents)
  * [2.2 Multimodal Action Models](#22-multimodal-action-models)
* [3. GUI Perception and Representation](#3-gui-perception-and-representation)
  * [3.1 Screen Parsing and Layout Understanding](#31-screen-parsing-and-layout-understanding)
  * [3.2 Vision-Language Models for UI](#32-vision-language-models-for-ui)
* [4. Planning, Control, and Memory](#4-planning-control-and-memory)
  * [4.1 Reasoning for GUI Agents](#41-reasoning-for-gui-agents)
  * [4.2 Learning from Demonstrations and Feedback](#42-learning-from-demonstrations-and-feedback)
* [5. Benchmarks and Evaluation Suites](#5-benchmarks-and-evaluation-suites)
* [6. Datasets and Data Generation](#6-datasets-and-data-generation)
* [7. Frameworks and Tooling](#7-frameworks-and-tooling)
  * [7.1 Environment Simulators](#71-environment-simulators)
  * [7.2 Agent Toolkits and Runtimes](#72-agent-toolkits-and-runtimes)
  * [7.3 Low-Level Automation Primitives](#73-low-level-automation-primitives)
* [8. Applications and Use Cases](#8-applications-and-use-cases)
* [9. Evaluation Methodologies](#9-evaluation-methodologies)
* [10. Blogs, Talks, and Community Updates](#10-blogs-talks-and-community-updates)
* [11. Contributing](#11-contributing)
* [12. License](#12-license)
* [13. Acknowledgements](#13-acknowledgements)

---

# 📢 News

## 2024

- **[2024.07.23]** Anthropic opened the *Claude Computer Use* beta, enabling developers to script GUI workflows with natural language policies through the Claude 3.5 Sonnet model. [Announcement](https://www.anthropic.com/news/claude-3-5-sonnet)
- **[2024.05.13]** OpenAI introduced *GPT-4o* with live desktop sharing and on-device perception that unlocks richer multimodal computer-use agents. [Launch post](https://openai.com/index/hello-gpt-4o/)
- **[2024.02.15]** The BrowserGym team released a unified benchmark and toolkit (v1.0) for web-based autonomous agents with reproducible evaluation harnesses. [Paper](https://arxiv.org/abs/2402.13510) | [Code](https://github.com/browsergym/browsergym)
## 2023

- **[2023.11.27]** *Mind2Web* introduced an open dataset of 3,000+ real-world web tasks and an evaluation leaderboard for LLM-powered web agents. [Paper](https://arxiv.org/abs/2311.09731) | [Site](https://mind2web.org/)
- **[2023.03.15]** Adept presented *ACT-1*, a transformer that jointly reasons over screen pixels, text, and action history to control computers from natural language instructions. [Blog](https://www.adept.ai/blog/act-1)

---

# 1. Surveys and Overviews

1. [**A Survey on Large Language Model based Autonomous Agents.**](https://arxiv.org/abs/2308.11432) *Mengchun Zhang et al.* arXiv 2023.
2. [**Vision-Language-Action Models: A Survey on Embodied AI.**](https://arxiv.org/abs/2308.00833) *Chen et al.* arXiv 2023.
3. [**Foundation Model Agents: A Survey.**](https://arxiv.org/abs/2402.01761) *Xi et al.* arXiv 2024.

---

# 2. Foundational Systems

## 2.1 Early Web and Desktop Agents

1. [**MiniWoB++: A Minimalist Benchmark for Web-Based Reinforcement Learning.**](https://github.com/deepmind/miniwob-plusplus) *Liu et al.* ICML 2018.
2. [**WebNav: Benchmarking Reinforcement Learning for Web Navigation.**](https://arxiv.org/abs/1711.04854) *Shi et al.* NeurIPS 2017.
3. [**WebShop: Towards Scalable Real-World Web Interaction with Grounded Agents.**](https://arxiv.org/abs/2206.10498) *Yao et al.* ICML 2022.
4. [**WebGPT: Browser-assisted Question-Answering with Human Feedback.**](https://arxiv.org/abs/2112.09332) *Nakano et al.* arXiv 2021.

## 2.2 Multimodal Action Models

1. [**ACT-1: Transformer for Actions.**](https://www.adept.ai/blog/act-1) *Adept AI Labs.* 2023.
2. [**AppAgent: Multimodal Agents for Task Automation on Mobile Apps.**](https://arxiv.org/abs/2311.10367) *Liang et al.* arXiv 2023.
3. [**TaskMatrix.AI: A Holistic Multimodal Agent for Cross-Platform Computer Control.**](https://arxiv.org/abs/2303.16434) *Wu et al.* arXiv 2023.
4. [**Fuyu-8B: Multimodal Foundation Model for Computer Use.**](https://www.adept.ai/blog/fuyu-8b) *Adept AI Labs.* 2023.

---

# 3. GUI Perception and Representation

## 3.1 Screen Parsing and Layout Understanding

1. [**Rico: A Mobile App Dataset for Building Data-Driven Design Applications.**](https://interactionmining.org/rico.html) *Deka et al.* UIST 2017.
2. [**UIBERT: Learning Generic Representations for UI Screen Understanding.**](https://arxiv.org/abs/2107.13731) *Li et al.* NeurIPS 2021.
3. [**Pix2Struct: Screenshot Parsing for Language Models.**](https://arxiv.org/abs/2210.03347) *Lee et al.* arXiv 2022.
4. [**OmniParser: Structured Vision-Language Parsing for Computer Interfaces.**](https://github.com/OpenGVLab/OmniParser) *OpenGVLab.* 2024.

## 3.2 Vision-Language Models for UI

1. [**Flamingo: A Visual Language Model for Few-Shot Learning.**](https://arxiv.org/abs/2204.14198) *Alayrac et al.* NeurIPS 2022.
2. [**Kosmos-2: Grounding Multimodal Large Language Models to the World.**](https://arxiv.org/abs/2306.14824) *Peng et al.* arXiv 2023.
3. [**Fuyu-8B: Perception, Language, and Action.**](https://www.adept.ai/blog/fuyu-8b) *Adept AI Labs.* 2023.
4. [**GPT-4 Technical Report.**](https://arxiv.org/abs/2303.08774) *OpenAI.* 2023.

---

# 4. Planning, Control, and Memory

## 4.1 Reasoning for GUI Agents

1. [**ReAct: Synergizing Reasoning and Acting in Language Models.**](https://arxiv.org/abs/2210.03629) *Yao et al.* ICLR 2023.
2. [**Reflexion: Language Agents with Verbal Reinforcement Learning.**](https://arxiv.org/abs/2303.11366) *Shinn et al.* NeurIPS 2023.
3. [**Self-Refine: Iterative Refinement with Self-Feedback.**](https://arxiv.org/abs/2303.17651) *Madaan et al.* NeurIPS 2023.
4. [**Toolformer: Language Models Can Teach Themselves to Use Tools.**](https://arxiv.org/abs/2302.04761) *Schick et al.* ICLR 2023.

## 4.2 Learning from Demonstrations and Feedback

1. [**Demonstrate-Search-Predict: Web Navigation via Thought Cloning.**](https://arxiv.org/abs/2305.17590) *Nogueira et al.* arXiv 2023.
2. [**Mind2Web: Towards a Generalist Web Agent with Imitation Learning.**](https://arxiv.org/abs/2311.09731) *Deng et al.* arXiv 2023.

---

# 5. Benchmarks and Evaluation Suites

1. [**BrowserGym.**](https://github.com/browsergym/browsergym) A reproducible evaluation harness and suite of web tasks with automated grading. 2024.
2. [**WebArena.**](https://github.com/web-arena-x/webarena) Realistic multi-domain web environments (GitHub, Reddit, shopping) with automatic scoring. 2023.
3. [**Mind2Web Leaderboard.**](https://mind2web.org/) Full-browser evaluation with human-authored instructions. 2023.
4. [**MiniWoB++.**](https://github.com/deepmind/miniwob-plusplus) Classic micro-task collection for UI reinforcement learning. 2018.
5. [**AndroidEnv.**](https://github.com/google-research/android_env) Android device simulator for RL and imitation learning. 2021.
6. [**MiniWoB++ Leaderboard.**](https://miniwob.farama.org/) Community evaluation for classic UI tasks. 2023.

---

# 6. Datasets and Data Generation

1. [**Mind2Web Dataset.**](https://huggingface.co/datasets/mind2web/mind2web) Multi-domain dataset with demonstrations for web control. 2023.
2. [**WebShop Interaction Logs.**](https://arxiv.org/abs/2206.10498) User-like shopping trajectories for goal-oriented browsing. 2022.
3. [**Rico.**](https://interactionmining.org/rico.html) 66k Android UI screens with interaction traces. 2017.
4. [**ScreenQA.**](https://screenqa.github.io/) Visual question answering dataset over UI screenshots. 2023.
5. [**TaskMatrix.Hub.**](https://github.com/microsoft/TaskMatrix) Cross-application action dataset powering TaskMatrix.AI. 2023.

---

# 7. Frameworks and Tooling

## 7.1 Environment Simulators

1. [**BrowserGym.**](https://github.com/browsergym/browsergym) Unified API for Chrome-based automation with reproducible setups. 2024.
2. [**WebArena Sandbox.**](https://github.com/web-arena-x/webarena) Headless browsers with task-specific servers. 2023.
3. [**MiniWoB++.**](https://github.com/deepmind/miniwob-plusplus) Lightweight HTML tasks for rapid experimentation. 2018.
4. [**AndroidEnv.**](https://github.com/google-research/android_env) Android automation environment grounded in RL. 2021.

## 7.2 Agent Toolkits and Runtimes

1. [**LangChain Browser Toolkit.**](https://python.langchain.com/docs/modules/agents/toolkits/browser) Abstractions for LLM-driven browsing with Playwright. 2024.
2. [**AutoGen.**](https://github.com/microsoft/autogen) Multi-agent orchestration with built-in tool invocation. 2023.
3. [**OpenHands.**](https://github.com/All-Hands-AI/OpenHands) An extensible runtime for observable, reproducible agent execution. 2024.
4. [**Mind2Web Baselines.**](https://github.com/OSU-NLP-Group/Mind2Web) Reference agents and evaluation scripts. 2023.

## 7.3 Low-Level Automation Primitives

1. [**Playwright.**](https://playwright.dev/) Reliable browser automation that underpins many web agents. Microsoft, 2020–present.
2. [**Selenium.**](https://www.selenium.dev/) Classic browser automation framework with mature ecosystem. 2004–present.
3. [**PyAutoGUI.**](https://pyautogui.readthedocs.io/en/latest/) Cross-platform mouse and keyboard automation. 2014–present.
4. [**uiautomator2.**](https://github.com/openatx/uiautomator2) Android device automation library with Python bindings. 2017–present.

---

# 8. Applications and Use Cases

1. [**Computer-Use Assistants.**](https://github.com/anthropics/anthropic-cookbook/tree/main/computer-use) Sample tasks for the Claude Computer Use API. 2024.
2. [**TaskMatrix.AI Demonstrations.**](https://arxiv.org/abs/2303.16434) Cross-application workflows executed by multimodal agents. 2023.
3. [**Mind2Web Case Studies.**](https://mind2web.org/) Annotated real-world browsing sessions. 2023.

---

# 9. Evaluation Methodologies

1. [**AgentBench: Benchmarking LLM as Agents.**](https://arxiv.org/abs/2308.03688) *Liu et al.* NeurIPS 2023.
2. [**ARENA: Automatic Robustness Evaluation for Web Agents.**](https://arxiv.org/abs/2310.06760) *Gur et al.* arXiv 2023.
3. [**BrowserGym Evaluation Harness.**](https://github.com/browsergym/browsergym) Open-source metrics and reproducible reporting. 2024.
4. [**WebArena Measurement Suite.**](https://github.com/web-arena-x/webarena) Task-level scoring and perturbation testing. 2023.

---

# 10. Blogs, Talks, and Community Updates

- **Anthropic Developer Blog — Computer Use Deep Dive** (2024). Practical guidance for crafting safe GUI workflows. [Link](https://www.anthropic.com/news/claude-computer-use)
- **OpenAI DevDay Session: Building Agents that Use Computers** (2023). Best practices for tool-augmented GPT agents. [Video](https://www.youtube.com/watch?v=xvy_jG2T3TQ)
- **Adept Blog — Introducing Fuyu-8B** (2023). Insights on multimodal models for computer use. [Article](https://www.adept.ai/blog/fuyu-8b)
- **Mind2Web Blog and Leaderboard Updates** (2023). Dataset release notes and competition news. [Blog](https://mind2web.org/)
- **LangChain Browser Agent Guide** (2024). Tutorial for Playwright-backed LLM agents. [Docs](https://python.langchain.com/docs/modules/agents/toolkits/browser)

---

# 11. Contributing

We welcome pull requests that improve coverage, fix outdated links, or add high-quality resources. Please:

1. Ensure the resource is publicly available and verifiable.
2. Use the section headings and numbering already in the README.
3. Include publication venue (conference, arXiv) and year when applicable.
4. Keep descriptions concise (≤ 20 words) and objective.

---

# 12. License

This project is released under the [MIT License](LICENSE).

---

# 13. Acknowledgements

Inspired by numerous awesome lists and the open-source agents community. Thanks to all researchers and practitioners sharing datasets, code, and evaluation suites that make progress on GUI agents possible.
