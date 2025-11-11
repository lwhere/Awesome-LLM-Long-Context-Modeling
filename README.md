# Awesome GUI Agent

<div align="center">
  <p align="center">
    <a href="#1-survey--position-papers">🧾 Surveys</a> |
    <a href="#2-general-purpose-gui-agents">🤖 Agents</a> |
    <a href="#3-benchmarks--evaluation">🧪 Benchmarks</a> |
    <a href="#4-ui-perception--understanding">👁️ UI Perception</a> |
    <a href="#5-tooling--frameworks">🛠️ Tooling</a> |
    <a href="#6-blogs--talks">📰 Blogs</a>
  </p>
</div>

<div align="center">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-red.svg)](https://github.com/Xnhyacinth/awesome-gui-agent/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/Xnhyacinth/awesome-gui-agent.svg?color=blue)](https://github.com/Xnhyacinth/awesome-gui-agent/commits)

</div>

This repository curates research papers, datasets, open-source systems, and learning materials for building **graphical user interface (GUI) agents** powered by large language models, multimodal perception, and planning frameworks. The goal is to help practitioners keep track of the rapidly evolving ecosystem around desktop, mobile, and web automation agents.

🔥 Contributions are welcome! Submit a pull request or open an issue to share new resources.

---

### Contents

* [📢 News](#-news)
* [1. Survey & Position Papers](#1-survey--position-papers)
* [2. General-Purpose GUI Agents](#2-general-purpose-gui-agents)
  * [2.1 Desktop & Mobile](#21-desktop--mobile)
  * [2.2 Web](#22-web)
* [3. Benchmarks & Evaluation](#3-benchmarks--evaluation)
* [4. UI Perception & Understanding](#4-ui-perception--understanding)
* [5. Tooling & Frameworks](#5-tooling--frameworks)
* [6. Blogs & Talks](#6-blogs--talks)
* [Contributing](#contributing)
* [Acknowledgements](#acknowledgements)

# 📢 News

- **[2024.09.12]** [OpenGVLab released MobileAgent](https://github.com/OpenGVLab/MobileAgent), a full-stack smartphone automation agent with multimodal perception, reasoning, and real devices in the loop.
- **[2024.08.23]** [Microsoft Research open-sourced OSWorld](https://github.com/xlang-ai/OSWorld), a large-scale benchmark and dataset for operating system manipulation with language agents.
- **[2024.07.18]** [browser-use 0.3 dropped](https://github.com/browser-use/browser-use), bringing Playwright-backed action execution, DOM grounding, and tracing hooks for browser agents.

---

## 1. Survey & Position Papers

1. [**Autonomous Agents in the Era of Foundation Models.**](https://arxiv.org/abs/2312.10908) *Qiao et al., 2023.* Comprehensive view on agent architectures, tool integration, and evaluation, including GUI automation as a core scenario.

2. [**Large Language Model-based Agents: A Survey.**](https://arxiv.org/abs/2405.10772) *Jiang et al., 2024.* Reviews LLM-powered agents, covering planning, perception, and safety considerations for computer-use assistants.

3. [**Vision-Language-Action Models: A Survey.**](https://arxiv.org/abs/2402.00560) *Gao et al., 2024.* Summarizes multimodal pipelines that connect visual grounding with action generation for both embodied and screen-based environments.

---

## 2. General-Purpose GUI Agents

### 2.1 Desktop & Mobile

1. [**AppAgent: Multimodal Agents for GUI Automation.**](https://github.com/microsoft/AppAgent) *Microsoft Research, 2023.* Hierarchical planner that observes the screen, reasons about states, and executes mouse/keyboard programs on desktop apps.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/AppAgent?style=social)](https://github.com/microsoft/AppAgent)

2. [**MobileAgent: LLM-based Task Automation for Smartphones.**](https://github.com/OpenGVLab/MobileAgent) *OpenGVLab, 2024.* End-to-end framework for physical and emulated Android devices with visual grounding, reflection, and safety guardrails.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/MobileAgent?style=social)](https://github.com/OpenGVLab/MobileAgent)

3. [**OpenInterpreter.**](https://github.com/OpenInterpreter/open-interpreter) *Open Interpreter, 2023.* Natural language interface that lets LLMs execute code, issue shell commands, and control OS-level GUI automation hooks.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter?style=social)](https://github.com/OpenInterpreter/open-interpreter)

4. [**OS-Copilot Baselines.**](https://github.com/xlang-ai/OSWorld) *XLang Lab, 2024.* Reference agents bundled with OSWorld that combine OmniParser perception, retrieval, and tool-use for complex desktop workflows.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/OSWorld?style=social)](https://github.com/xlang-ai/OSWorld)

### 2.2 Web

1. [**WebVoyager.**](https://github.com/OpenBMB/WebVoyager) *OpenBMB, 2024.* Multi-agent system that captures panoramic browser context, narrates state, and plans with LLMs for robust web navigation.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/WebVoyager?style=social)](https://github.com/OpenBMB/WebVoyager)

2. [**WebGLM.**](https://github.com/THUDM/WebGLM) *THUDM, 2023.* Toolkit built on ChatGLM for web tasks, featuring DOM extraction, memory, and reflection to improve reliability.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/WebGLM?style=social)](https://github.com/THUDM/WebGLM)

3. [**A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis.**](https://openreview.net/forum?id=9JQtrumvg8) *Google DeepMind, ICLR 2024.* Strong baseline that combines scratchpad planning, synthesized JavaScript tools, and verification for production web workflows.

4. [**Skyvern.**](https://github.com/SkyvernAI/skyvern) *SkyvernAI, 2024.* Production-focused LLM agent that records demonstrations, builds reusable browser automations, and executes them headlessly.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SkyvernAI/skyvern?style=social)](https://github.com/SkyvernAI/skyvern)

---

## 3. Benchmarks & Evaluation

1. [**OSWorld.**](https://github.com/xlang-ai/OSWorld) Large-scale benchmark of 1,600+ desktop tasks spanning email, spreadsheets, and developer tooling with multimodal observations and baseline agents.

2. [**Mind2Web.**](https://github.com/OSU-NLP/Mind2Web) Dataset of high-level web tasks across 137 sites, annotated with hierarchical goals, gold trajectories, and evaluation scripts.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OSU-NLP/Mind2Web?style=social)](https://github.com/OSU-NLP/Mind2Web)

3. [**WebArena.**](https://github.com/webarena-dev/webarena) Realistic open-domain browsing environment mirroring popular websites with automated scoring and multi-agent baselines.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/webarena-dev/webarena?style=social)](https://github.com/webarena-dev/webarena)

4. [**MiniWoB++.**](https://github.com/Farama-Foundation/miniwob-plusplus) Classic benchmark of 100+ micro web tasks with programmatic evaluation; widely used for imitation, RL, and agentic planning.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Farama-Foundation/miniwob-plusplus?style=social)](https://github.com/Farama-Foundation/miniwob-plusplus)

5. [**GAIA Benchmark.**](https://github.com/GAIA-benchmark/GAIA) Holistic evaluation suite for general computer-use agents with search, reasoning, and execution subtasks.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/GAIA-benchmark/GAIA?style=social)](https://github.com/GAIA-benchmark/GAIA)

6. [**AgentBench.**](https://github.com/THUDM/AgentBench) Multi-domain benchmark covering OS, code, web, and embodied tasks; includes metrics for accuracy, efficiency, and safety.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/AgentBench?style=social)](https://github.com/THUDM/AgentBench)

7. [**BrowserGym.**](https://github.com/browsergym/browsergym) Unified gym interface for browser tasks with instrumentation, reward wrappers, and reproducible baselines.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/browsergym/browsergym?style=social)](https://github.com/browsergym/browsergym)

8. [**Android in the Wild.**](https://github.com/google-research-datasets/android-in-the-wild) Large collection of real Android screens with accessibility metadata to stress-test mobile UI grounding.

---

## 4. UI Perception & Understanding

1. [**OmniParser.**](https://github.com/OpenGVLab/OmniParser) Vision-language parser that converts screenshots into structured UI trees, supporting OSWorld and MobileAgent pipelines.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/OmniParser?style=social)](https://github.com/OpenGVLab/OmniParser)

2. [**Screen2Words.**](https://github.com/google-research/screen2words) Dataset and models that turn mobile UI screenshots into descriptive captions for downstream reasoning.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/screen2words?style=social)](https://github.com/google-research/screen2words)

3. [**ScreenQA.**](https://github.com/google-research-datasets/ScreenQA) Large-scale QA dataset for understanding desktop and mobile screens, useful for training visual question-answering modules.

4. [**RICO Dataset.**](https://interactionmining.org/rico) 66k Android UI screens with hierarchical view structures enabling layout analysis and component detection.

5. [**UIED: A Hybrid Approach for Detecting UI Elements.**](https://github.com/yuchuhang/UIED) Pixel and component-level detectors for buttons, text, and containers, offering a strong baseline for GUI perception.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/yuchuhang/UIED?style=social)](https://github.com/yuchuhang/UIED)

---

## 5. Tooling & Frameworks

1. [**browser-use.**](https://github.com/browser-use/browser-use) Developer-friendly toolkit for Playwright-based browser control with LLM action plans, DOM grounding, and observability.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/browser-use/browser-use?style=social)](https://github.com/browser-use/browser-use)

2. [**Skyvern.**](https://github.com/SkyvernAI/skyvern) Declarative automation stack that records demos, builds deterministic action graphs, and executes web flows with LLM fallbacks.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SkyvernAI/skyvern?style=social)](https://github.com/SkyvernAI/skyvern)

3. [**AutoGen.**](https://github.com/microsoft/autogen) Multi-agent orchestration framework with built-in tool calling, memory, and event loops suited for GUI planning.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen?style=social)](https://github.com/microsoft/autogen)

4. [**AgentVerse.**](https://github.com/InternLM/AgentVerse) Modular environment for composing heterogeneous agents, including browser and desktop operators.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/AgentVerse?style=social)](https://github.com/InternLM/AgentVerse)

5. [**OpenAgents.**](https://github.com/LinkSoul-AI/OpenAgents) Production-ready agent stack with connectors for browsers, office suites, and automation backends.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/LinkSoul-AI/OpenAgents?style=social)](https://github.com/LinkSoul-AI/OpenAgents)

6. [**LangChain Browser Toolkit.**](https://python.langchain.com/docs/integrations/toolkits/browser/) Set of tools for LangChain agents, leveraging Playwright and Selenium drivers with structured action schemas.

---

## 6. Blogs & Talks

1. [**OpenAI – Towards Generalist Computer-Using Agents.**](https://openai.com/research/generalist-computer-use) Overview of the challenges in letting GPT-4-class models operate computers safely and reliably.

2. [**Adept – How We Built ACT-1.**](https://www.adept.ai/blog/act-1) Engineering deep dive into multi-modal models that combine language and low-level UI actions.

3. [**Hugging Face – Web Agents with LLMs.**](https://huggingface.co/blog/web-agents) Tutorial covering architectures, benchmarks, and hands-on code for browser automation.

4. [**MobileAgent Project Page.**](https://opengvlab.github.io/MobileAgent/) Demos, technical report, and design notes for on-device mobile agents.

5. [**browser-use Documentation Hub.**](https://browser-use.github.io/) Guides for building robust browser automations, including tracing, evaluation, and deployment tips.

---

## Contributing

1. Check for duplicates before submitting a new item.
2. Follow the existing markdown style: section title, numbered list, short description, and optional badges.
3. Keep entries factual—include publication venue/year and mention code availability where possible.
4. Run markdown linting (`markdownlint README.md`) if you modify formatting extensively.

We welcome issues that highlight missing categories, incorrect links, or requests for clarifications.

---

## Acknowledgements

Inspired by the broader awesome lists community. Special thanks to researchers and engineers sharing open-source GUI agent datasets, benchmarks, and systems.

If you find this list useful, consider giving the repository a ⭐ and sharing it with colleagues working on computer-use agents!
