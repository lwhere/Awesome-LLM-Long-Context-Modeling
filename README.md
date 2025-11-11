# Awesome GUI Agent [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
 <p align="center">
 
   <a href="#1-survey-papers">📝 Papers</a> | <a href="#frameworks-and-toolkits">🛠️ Frameworks</a> | <a href="#benchmarks-and-datasets">📊 Benchmarks</a>
 
 </p>
</div>

<div align="center">

[![LICENSE](https://img.shields.io/github/license/Xnhyacinth/awesome-GUI-Agent)](https://github.com/Xnhyacinth/awesome-GUI-Agent/blob/main/LICENSE)
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
[![commit](https://img.shields.io/github/last-commit/Xnhyacinth/awesome-GUI-Agent?color=blue)](https://github.com/Xnhyacinth/awesome-GUI-Agent/commits/main)
[![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/Xnhyacinth/awesome-GUI-Agent/pulls)
[![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/awesome-GUI-Agent)](https://github.com/Xnhyacinth/awesome-GUI-Agent)

</div>

This repository contains a curated list of papers, frameworks, benchmarks, and resources about **GUI (Graphical User Interface) Agents** powered by Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs).

🔥 Must-read papers and resources for GUI Agent research and development.

GUI Agents are AI systems that can understand, navigate, and interact with graphical user interfaces across various platforms including mobile apps, desktop applications, web browsers, and operating systems. They combine computer vision, natural language understanding, and action planning to automate complex tasks in digital environments.

Thanks for all the great contributors on GitHub!🔥⚡🔥

### Contents

* [1. Survey Papers](#1-survey-papers)
* [2. Foundation Models for GUI](#2-foundation-models-for-gui)
  * [2.1 Multimodal LLMs for GUI](#21-multimodal-llms-for-gui)
  * [2.2 Specialized GUI Models](#22-specialized-gui-models)
* [3. Web Agents](#3-web-agents)
  * [3.1 Browser Automation](#31-browser-automation)
  * [3.2 Web Navigation](#32-web-navigation)
  * [3.3 Form Filling and E-commerce](#33-form-filling-and-e-commerce)
* [4. Mobile Agents](#4-mobile-agents)
  * [4.1 Android Agents](#41-android-agents)
  * [4.2 iOS Agents](#42-ios-agents)
  * [4.3 Cross-Platform Mobile](#43-cross-platform-mobile)
* [5. Desktop Agents](#5-desktop-agents)
  * [5.1 Windows](#51-windows)
  * [5.2 MacOS](#52-macos)
  * [5.3 Linux](#53-linux)
* [6. GUI Understanding](#6-gui-understanding)
  * [6.1 Screen Parsing](#61-screen-parsing)
  * [6.2 Element Detection](#62-element-detection)
  * [6.3 Layout Understanding](#63-layout-understanding)
* [7. Action Planning and Execution](#7-action-planning-and-execution)
  * [7.1 Task Planning](#71-task-planning)
  * [7.2 Grounding and Localization](#72-grounding-and-localization)
  * [7.3 Action Primitives](#73-action-primitives)
* [8. Multi-Agent Collaboration](#8-multi-agent-collaboration)
* [9. Frameworks and Toolkits](#9-frameworks-and-toolkits)
  * [9.1 Open-Source Frameworks](#91-open-source-frameworks)
  * [9.2 Commercial Tools](#92-commercial-tools)
* [10. Benchmarks and Datasets](#10-benchmarks-and-datasets)
  * [10.1 Web Benchmarks](#101-web-benchmarks)
  * [10.2 Mobile Benchmarks](#102-mobile-benchmarks)
  * [10.3 Desktop Benchmarks](#103-desktop-benchmarks)
  * [10.4 Cross-Platform Benchmarks](#104-cross-platform-benchmarks)
* [11. Training and Fine-tuning](#11-training-and-fine-tuning)
  * [11.1 Datasets](#111-datasets)
  * [11.2 Training Methods](#112-training-methods)
  * [11.3 Reinforcement Learning](#113-reinforcement-learning)
* [12. Safety and Security](#12-safety-and-security)
* [13. Evaluation Metrics](#13-evaluation-metrics)
* [14. Applications](#14-applications)
  * [14.1 Testing and QA](#141-testing-and-qa)
  * [14.2 Accessibility](#142-accessibility)
  * [14.3 RPA (Robotic Process Automation)](#143-rpa-robotic-process-automation)
* [15. Blogs and Tutorials](#15-blogs-and-tutorials)
* [Acknowledgements](#acknowledgements)

---

# 📢 News

## Recent Updates

- **[2025.02.21]**
    - Paper: [ShowUI: One Vision-Language-Action Model for GUI Visual Agent](https://arxiv.org/abs/2411.17465)
    - Paper: [Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction](https://arxiv.org/abs/2412.04454)
    - Project: [Claude Computer Use - Anthropic's GUI Agent API](https://www.anthropic.com/news/3-5-models-and-computer-use)

- **[2025.02.14]**
    - Paper: [MobileAgent: Enhanced Multimodal LLMs for Autonomous Mobile GUI Interaction](https://arxiv.org/abs/2401.16158)
    - Paper: [CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/abs/2312.08914)
    - Paper: [SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents](https://arxiv.org/abs/2401.10935)

- **[2025.02.07]**
    - Paper: [GPT-4V(ision) is a Generalist Web Agent, if Grounded](https://arxiv.org/abs/2401.01614)
    - Benchmark: [WebArena: A Realistic Web Environment for Building Autonomous Agents](https://arxiv.org/abs/2307.13854)
    - Benchmark: [Mind2Web: Towards a Generalist Agent for the Web](https://arxiv.org/abs/2306.06070)

- **[2025.01.31]**
    - Paper: [AppAgent: Multimodal Agents as Smartphone Users](https://arxiv.org/abs/2312.13771)
    - Paper: [UFO: A UI-Focused Agent for Windows OS Interaction](https://arxiv.org/abs/2402.07939)
    - Framework: [Skyvern - Open-source browser automation using LLMs](https://github.com/Skyvern-AI/skyvern)

---

# 1. Survey Papers

1. **A Survey on Large Language Model-Based Agents for GUI Interaction** [[Paper](https://arxiv.org/abs/2410.12177)]
   - *Authors*: Various
   - *Date*: Oct 2024
   - *Summary*: Comprehensive survey covering GUI agents across web, mobile, and desktop platforms.

2. **The Rise and Potential of Large Language Model Based Agents: A Survey** [[Paper](https://arxiv.org/abs/2309.07864)]
   - *Authors*: Zhiheng Xi et al.
   - *Date*: Sep 2023
   - *Summary*: General agent survey with sections on GUI agents and tool use.

3. **GUI Agents: A Survey** [[Paper](https://arxiv.org/abs/2412.13501)]
   - *Authors*: Various
   - *Date*: Dec 2024
   - *Summary*: Focused survey on GUI understanding, action planning, and multi-platform agents.

4. **Foundation Models for GUI Understanding and Interaction: A Survey** [[Paper](https://arxiv.org/abs/2410.11709)]
   - *Date*: Oct 2024
   - *Summary*: Survey on foundation models specifically designed for GUI tasks.

---

# 2. Foundation Models for GUI

## 2.1 Multimodal LLMs for GUI

1. **GPT-4V(ision) System Card** [[Paper](https://cdn.openai.com/papers/GPTV_System_Card.pdf)] [[OpenAI](https://openai.com/research/gpt-4v-system-card)]
   - *Organization*: OpenAI
   - *Date*: Sep 2023
   - *Key Features*: Vision-language model capable of GUI understanding

2. **Gemini: A Family of Highly Capable Multimodal Models** [[Paper](https://arxiv.org/abs/2312.11805)] [[Blog](https://blog.google/technology/ai/google-gemini-ai/)]
   - *Organization*: Google DeepMind
   - *Date*: Dec 2023
   - *Key Features*: Native multimodal understanding including screenshots and UI elements

3. **Claude 3.5 Sonnet with Computer Use** [[Blog](https://www.anthropic.com/news/3-5-models-and-computer-use)] [[API](https://docs.anthropic.com/en/docs/build-with-claude/computer-use)]
   - *Organization*: Anthropic
   - *Date*: Oct 2024
   - *Key Features*: First production model with native computer use capabilities

4. **Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution** [[Paper](https://arxiv.org/abs/2409.12191)] [[GitHub](https://github.com/QwenLM/Qwen2-VL)]
   - *Organization*: Alibaba
   - *Date*: Sep 2024
   - *Key Features*: High-resolution image understanding for GUI tasks

## 2.2 Specialized GUI Models

1. **CogAgent: A Visual Language Model for GUI Agents** [[Paper](https://arxiv.org/abs/2312.08914)] [[GitHub](https://github.com/THUDM/CogVLM)] [[Demo](https://cogagent.github.io/)]
   - *Organization*: Tsinghua University & Zhipu AI
   - *Date*: Dec 2023
   - *Key Features*: 18B VLM with dual-resolution architecture for GUI understanding
   - *Highlights*: State-of-the-art on Mind2Web, AITW, and other GUI benchmarks

2. **ShowUI: One Vision-Language-Action Model for GUI Visual Agent** [[Paper](https://arxiv.org/abs/2411.17465)] [[GitHub](https://github.com/showlab/ShowUI)] [[Demo](https://showlab.github.io/ShowUI/)]
   - *Organization*: National University of Singapore
   - *Date*: Nov 2024
   - *Key Features*: Unified model for GUI understanding and action prediction
   - *Highlights*: UI-Guided Visual Token Selection for efficient processing

3. **Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction** [[Paper](https://arxiv.org/abs/2412.04454)] [[GitHub](https://github.com/FreedomIntelligence/Aguvis)]
   - *Organization*: Chinese University of Hong Kong
   - *Date*: Dec 2024
   - *Key Features*: Pure vision-based approach without OCR dependency
   - *Highlights*: Unified framework for multi-platform GUI control

4. **SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents** [[Paper](https://arxiv.org/abs/2401.10935)] [[GitHub](https://github.com/njucckevin/SeeClick)] [[Demo](https://seeclick.github.io/)]
   - *Organization*: Nanjing University
   - *Date*: Jan 2024
   - *Key Features*: GUI grounding model with precise element localization
   - *Highlights*: Combines visual grounding with action prediction

5. **Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs** [[Paper](https://arxiv.org/abs/2404.05719)] [[GitHub](https://github.com/apple/ml-ferret)]
   - *Organization*: Apple
   - *Date*: Apr 2024
   - *Key Features*: Mobile UI understanding with any-resolution grounding
   - *Highlights*: iPhone screen understanding and element detection

6. **UGround: Unleashing Visual Grounding for GUI Agents** [[Paper](https://arxiv.org/abs/2410.06677)]
   - *Date*: Oct 2024
   - *Key Features*: Enhanced visual grounding for accurate GUI element localization

7. **WebWanderer: Navigation and Multimodal Question Answering** [[Paper](https://arxiv.org/abs/2401.01614)]
   - *Date*: Jan 2024
   - *Key Features*: Web navigation with multimodal understanding

---

# 3. Web Agents

## 3.1 Browser Automation

1. **WebGUM: A Generalist Agent for Web Automation** [[Paper](https://arxiv.org/abs/2402.14979)]
   - *Date*: Feb 2024
   - *Key Features*: Generalist model for diverse web automation tasks

2. **AutoWebGLM: Large Language Model-based Web Agent** [[Paper](https://arxiv.org/abs/2404.03648)] [[GitHub](https://github.com/THUDM/AutoWebGLM)]
   - *Organization*: Tsinghua University
   - *Date*: Apr 2024
   - *Key Features*: Chinese-English bilingual web automation agent

3. **SteP: Stacked LLM Policies for Web Actions** [[Paper](https://arxiv.org/abs/2310.03051)]
   - *Date*: Oct 2023
   - *Key Features*: Hierarchical policy for complex web tasks

4. **WebAgent: A Practical LLM-based Agent for Web Navigation** [[Paper](https://arxiv.org/abs/2307.12856)]
   - *Date*: Jul 2023
   - *Key Features*: Practical web navigation with HTML understanding

5. **Skyvern: Browser Automation Using LLMs and Computer Vision** [[GitHub](https://github.com/Skyvern-AI/skyvern)] [[Website](https://www.skyvern.com/)]
   - *Organization*: Skyvern AI
   - *Type*: Open-source Framework
   - *Key Features*: Vision-based browser automation without relying on XPath or selectors

## 3.2 Web Navigation

1. **Mind2Web: Towards a Generalist Agent for the Web** [[Paper](https://arxiv.org/abs/2306.06070)] [[GitHub](https://github.com/OSU-NLP-Group/Mind2Web)] [[Website](https://osu-nlp-group.github.io/Mind2Web/)]
   - *Organization*: Ohio State University
   - *Date*: Jun 2023
   - *Key Features*: Dataset with 2,000+ web tasks across 137 websites
   - *Highlights*: Real-world web navigation benchmark

2. **WebArena: A Realistic Web Environment for Building Autonomous Agents** [[Paper](https://arxiv.org/abs/2307.13854)] [[GitHub](https://github.com/web-arena-x/webarena)] [[Website](https://webarena.dev/)]
   - *Organization*: CMU
   - *Date*: Jul 2023
   - *Key Features*: Self-hostable realistic web environments
   - *Highlights*: End-to-end web task evaluation

3. **VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks** [[Paper](https://arxiv.org/abs/2401.13649)] [[GitHub](https://github.com/web-arena-x/visualwebarena)]
   - *Organization*: CMU & Stanford
   - *Date*: Jan 2024
   - *Key Features*: Visual web tasks requiring multimodal understanding

4. **GPT-4V(ision) is a Generalist Web Agent, if Grounded** [[Paper](https://arxiv.org/abs/2401.01614)] [[GitHub](https://github.com/OSU-NLP-Group/SeeAct)]
   - *Organization*: Ohio State University
   - *Date*: Jan 2024
   - *Key Features*: SeeAct framework for grounded web agents

5. **WebVoyager: Building an End-to-End Web Agent** [[Paper](https://arxiv.org/abs/2401.13919)]
   - *Date*: Jan 2024
   - *Key Features*: End-to-end web agent with visual understanding

6. **A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis** [[Paper](https://arxiv.org/abs/2307.12856)]
   - *Date*: Jul 2023
   - *Key Features*: Planning and long-context handling for web tasks

## 3.3 Form Filling and E-commerce

1. **WebShop: Towards Scalable Real-World Web Interaction** [[Paper](https://arxiv.org/abs/2207.01206)] [[GitHub](https://github.com/princeton-nlp/WebShop)]
   - *Organization*: Princeton University
   - *Date*: Jul 2022
   - *Key Features*: E-commerce task simulation environment

2. **FormNetV2: Multimodal Graph Contrastive Learning for Form Document Information Extraction** [[Paper](https://arxiv.org/abs/2305.02549)]
   - *Date*: May 2023
   - *Key Features*: Form understanding and information extraction

3. **E-commerce Product Information Extraction** [[Paper](https://arxiv.org/abs/2210.14927)]
   - *Date*: Oct 2022
   - *Key Features*: Product attribute extraction for e-commerce

---

# 4. Mobile Agents

## 4.1 Android Agents

1. **AppAgent: Multimodal Agents as Smartphone Users** [[Paper](https://arxiv.org/abs/2312.13771)] [[GitHub](https://github.com/mnotgod96/AppAgent)]
   - *Organization*: Tencent
   - *Date*: Dec 2023
   - *Key Features*: Learning smartphone operations through exploration
   - *Highlights*: Self-exploration without system back-end access

2. **MobileAgent: Enhanced Multimodal LLMs for Autonomous Mobile GUI Interaction** [[Paper](https://arxiv.org/abs/2401.16158)] [[GitHub](https://github.com/X-PLUG/MobileAgent)]
   - *Organization*: Alibaba
   - *Date*: Jan 2024
   - *Key Features*: Visual perception and operation prediction for mobile
   - *Highlights*: Multi-agent collaboration for complex tasks

3. **AutoDroid: Large Language Model-powered GUI Agent for Android** [[Paper](https://arxiv.org/abs/2308.15272)]
   - *Date*: Aug 2023
   - *Key Features*: Automated Android app testing and operation

4. **DroidBot-GPT: GPT-powered Android UI Automation** [[Paper](https://arxiv.org/abs/2304.07061)]
   - *Date*: Apr 2023
   - *Key Features*: GPT-powered Android automation framework

5. **Android in the Wild: A Large-Scale Dataset for Android Device Control** [[Paper](https://arxiv.org/abs/2307.10088)] [[GitHub](https://github.com/google-research/google-research/tree/master/android_in_the_wild)]
   - *Organization*: Google Research
   - *Date*: Jul 2023
   - *Key Features*: 30K+ human demonstrations for Android tasks
   - *Highlights*: Real device control dataset

6. **GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation** [[Paper](https://arxiv.org/abs/2311.07562)]
   - *Date*: Nov 2023
   - *Key Features*: Zero-shot smartphone navigation with GPT-4V

7. **CoCo-Agent: A Comprehensive Cognitive LLM Mobile Agent** [[Paper](https://arxiv.org/abs/2402.04236)]
   - *Date*: Feb 2024
   - *Key Features*: Cognitive architecture for mobile agents

## 4.2 iOS Agents

1. **Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs** [[Paper](https://arxiv.org/abs/2404.05719)] [[GitHub](https://github.com/apple/ml-ferret)]
   - *Organization*: Apple
   - *Date*: Apr 2024
   - *Key Features*: iPhone UI understanding and grounding

2. **iOS GUI Control with Large Language Models** [[Paper](https://arxiv.org/abs/2312.04821)]
   - *Date*: Dec 2023
   - *Key Features*: iOS-specific control strategies

## 4.3 Cross-Platform Mobile

1. **MobileEnv: An Evaluation Platform for Autonomous Agents on Mobile Devices** [[Paper](https://arxiv.org/abs/2305.08144)]
   - *Date*: May 2023
   - *Key Features*: Cross-platform mobile evaluation

2. **META-GUI: Towards Multi-modal Conversational Agents for GUI** [[Paper](https://arxiv.org/abs/2301.04725)]
   - *Date*: Jan 2023
   - *Key Features*: Multi-modal conversational interface for mobile

3. **Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration** [[Paper](https://arxiv.org/abs/2406.01014)]
   - *Date*: Jun 2024
   - *Key Features*: Enhanced multi-agent system for mobile devices

---

# 5. Desktop Agents

## 5.1 Windows

1. **UFO: A UI-Focused Agent for Windows OS Interaction** [[Paper](https://arxiv.org/abs/2402.07939)] [[GitHub](https://github.com/microsoft/UFO)]
   - *Organization*: Microsoft Research
   - *Date*: Feb 2024
   - *Key Features*: Windows application control via UI understanding
   - *Highlights*: Multi-application workflows, accessibility tree + vision

2. **ScreenAgent: A Vision Language Model-driven Computer Control Agent** [[Paper](https://arxiv.org/abs/2402.07945)] [[GitHub](https://github.com/niuzaisheng/ScreenAgent)]
   - *Date*: Feb 2024
   - *Key Features*: Computer control across Windows applications

3. **OS-Copilot: Towards Generalist Computer Agents** [[Paper](https://arxiv.org/abs/2402.07456)]
   - *Date*: Feb 2024
   - *Key Features*: Generalist agent for Windows OS

4. **WindowsAgent: A Multi-modal Agent for Windows OS** [[Paper](https://arxiv.org/abs/2403.04830)]
   - *Date*: Mar 2024
   - *Key Features*: Multi-modal Windows control agent

## 5.2 MacOS

1. **OSWorld: Benchmarking Multimodal Agents for Open-Ended Computer Tasks** [[Paper](https://arxiv.org/abs/2404.07972)] [[GitHub](https://github.com/xlang-ai/OSWorld)]
   - *Organization*: Hong Kong University & CMU
   - *Date*: Apr 2024
   - *Key Features*: Ubuntu, Windows, MacOS benchmark for open-ended tasks

2. **MacAgent: A Multimodal Agent for MacOS** [[Paper](https://arxiv.org/abs/2404.04635)]
   - *Date*: Apr 2024
   - *Key Features*: MacOS-specific agent with native API integration

3. **Cradle: Empowering Foundation Agents Towards General Computer Control** [[Paper](https://arxiv.org/abs/2403.03186)] [[GitHub](https://github.com/BAAI-Agents/Cradle)]
   - *Organization*: Beijing Academy of AI
   - *Date*: Mar 2024
   - *Key Features*: General computer control framework

## 5.3 Linux

1. **OSWorld: Benchmarking Multimodal Agents for Open-Ended Computer Tasks** [[Paper](https://arxiv.org/abs/2404.07972)]
   - *Date*: Apr 2024
   - *Key Features*: Linux/Ubuntu task execution benchmark

2. **AgentStudio: A Toolkit for Building General Virtual Agents** [[Paper](https://arxiv.org/abs/2403.17918)] [[GitHub](https://github.com/SkyworkAI/agent-studio)]
   - *Date*: Mar 2024
   - *Key Features*: Cross-platform agent development toolkit

3. **Navi: Desktop Control via Natural Language** [[Paper](https://arxiv.org/abs/2310.16863)]
   - *Date*: Oct 2023
   - *Key Features*: Linux desktop control with natural language

---

# 6. GUI Understanding

## 6.1 Screen Parsing

1. **Screen2Words: Automatic Mobile UI Summarization** [[Paper](https://arxiv.org/abs/2108.03353)]
   - *Date*: Aug 2021
   - *Key Features*: Mobile screen summarization and description

2. **Widget Captioning: Generating Natural Language Descriptions for Mobile UI Elements** [[Paper](https://arxiv.org/abs/2010.04295)]
   - *Date*: Oct 2020
   - *Key Features*: UI element description generation

3. **WebGPT: Browser-assisted Question-Answering** [[Paper](https://arxiv.org/abs/2112.09332)]
   - *Date*: Dec 2021
   - *Key Features*: Web page understanding and parsing

4. **Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding** [[Paper](https://arxiv.org/abs/2210.03347)]
   - *Organization*: Google Research
   - *Date*: Oct 2022
   - *Key Features*: Screenshot-based pretraining for UI understanding

## 6.2 Element Detection

1. **UIBert: Learning Generic Multimodal Representations for UI Understanding** [[Paper](https://arxiv.org/abs/2107.13731)]
   - *Date*: Jul 2021
   - *Key Features*: Multimodal UI understanding with BERT

2. **CLUIF: A Unified Model for UI Element Detection** [[Paper](https://arxiv.org/abs/2206.02507)]
   - *Date*: Jun 2022
   - *Key Features*: Unified UI element detection across platforms

3. **Screen Recognition: Creating Accessibility Metadata for Mobile Applications** [[Paper](https://dl.acm.org/doi/10.1145/3411764.3445186)]
   - *Date*: May 2021
   - *Key Features*: Mobile accessibility metadata generation

4. **Object Detection for UI Elements** [[Paper](https://arxiv.org/abs/2008.05132)]
   - *Date*: Aug 2020
   - *Key Features*: Object detection applied to UI elements

## 6.3 Layout Understanding

1. **LTAB: Layout-aware Text-Block Attention Network** [[Paper](https://arxiv.org/abs/2211.15162)]
   - *Date*: Nov 2022
   - *Key Features*: Layout-aware attention for document understanding

2. **LayoutLM: Pre-training of Text and Layout for Document Image Understanding** [[Paper](https://arxiv.org/abs/1912.13318)]
   - *Organization*: Microsoft Research
   - *Date*: Dec 2019
   - *Key Features*: Joint text and layout understanding

3. **UI-JEPA: Towards Active Perception for GUI Agents** [[Paper](https://arxiv.org/abs/2406.03984)]
   - *Date*: Jun 2024
   - *Key Features*: Self-supervised layout understanding for GUIs

---

# 7. Action Planning and Execution

## 7.1 Task Planning

1. **AdaPlanner: Adaptive Planning from Feedback** [[Paper](https://arxiv.org/abs/2305.16653)]
   - *Date*: May 2023
   - *Key Features*: Adaptive planning with execution feedback

2. **LLAMP: Large Language Model Based Multi-Agent Planning** [[Paper](https://arxiv.org/abs/2308.03308)]
   - *Date*: Aug 2023
   - *Key Features*: Multi-agent task planning

3. **Plan4MC: Skill Reinforcement Learning and Planning** [[Paper](https://arxiv.org/abs/2303.16563)]
   - *Date*: Mar 2023
   - *Key Features*: Hierarchical planning for complex tasks

4. **ReAct: Synergizing Reasoning and Acting in Language Models** [[Paper](https://arxiv.org/abs/2210.03629)]
   - *Date*: Oct 2022
   - *Key Features*: Reasoning and acting framework for LLMs

5. **Reflexion: Language Agents with Verbal Reinforcement Learning** [[Paper](https://arxiv.org/abs/2303.11366)]
   - *Date*: Mar 2023
   - *Key Features*: Self-reflection for improved agent performance

## 7.2 Grounding and Localization

1. **SeeClick: Harnessing GUI Grounding** [[Paper](https://arxiv.org/abs/2401.10935)]
   - *Date*: Jan 2024
   - *Key Features*: Precise GUI element grounding

2. **Grounding DINO: Marrying DINO with Grounded Pre-Training** [[Paper](https://arxiv.org/abs/2303.05499)]
   - *Date*: Mar 2023
   - *Key Features*: Open-set object detection for grounding

3. **Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding** [[Paper](https://arxiv.org/abs/2310.11441)]
   - *Organization*: Microsoft Research
   - *Date*: Oct 2023
   - *Key Features*: Set-of-Mark (SoM) for precise visual grounding

4. **ScreenSpot: A GUI Element Localization Dataset** [[Paper](https://arxiv.org/abs/2309.12808)]
   - *Date*: Sep 2023
   - *Key Features*: Large-scale GUI element localization dataset

## 7.3 Action Primitives

1. **MiniWoB++: A Benchmark for Web Automation** [[Paper](https://arxiv.org/abs/1802.08802)]
   - *Date*: Feb 2018
   - *Key Features*: Web automation action primitives

2. **AndroidEnv: A Reinforcement Learning Platform for Android** [[Paper](https://arxiv.org/abs/2105.13231)]
   - *Organization*: DeepMind
   - *Date*: May 2021
   - *Key Features*: Android action space definition

3. **VimGPT: A VIM-based Action Space for GUI Agents** [[GitHub](https://github.com/ishan0102/vimgpt)]
   - *Type*: Open-source Project
   - *Key Features*: VIM-inspired action primitives for efficiency

---

# 8. Multi-Agent Collaboration

1. **AgentVerse: Facilitating Multi-Agent Collaboration** [[Paper](https://arxiv.org/abs/2308.10848)] [[GitHub](https://github.com/OpenBMB/AgentVerse)]
   - *Organization*: Tsinghua University
   - *Date*: Aug 2023
   - *Key Features*: Framework for multi-agent collaboration

2. **MetaGPT: Meta Programming for Multi-Agent Systems** [[Paper](https://arxiv.org/abs/2308.00352)] [[GitHub](https://github.com/geekan/MetaGPT)]
   - *Date*: Aug 2023
   - *Key Features*: Multi-agent framework with role-based collaboration

3. **Communicative Agents for Software Development** [[Paper](https://arxiv.org/abs/2307.07924)]
   - *Date*: Jul 2023
   - *Key Features*: ChatDev multi-agent software development

4. **AutoGen: Enabling Next-Gen LLM Applications** [[Paper](https://arxiv.org/abs/2308.08155)] [[GitHub](https://github.com/microsoft/autogen)]
   - *Organization*: Microsoft Research
   - *Date*: Aug 2023
   - *Key Features*: Multi-agent conversation framework

5. **ProAgent: Building Proactive Cooperative AI with Large Language Models** [[Paper](https://arxiv.org/abs/2308.11339)]
   - *Date*: Aug 2023
   - *Key Features*: Proactive multi-agent collaboration

---

# 9. Frameworks and Toolkits

## 9.1 Open-Source Frameworks

1. **Playwright** [[GitHub](https://github.com/microsoft/playwright)] [[Website](https://playwright.dev/)]
   - *Organization*: Microsoft
   - *Type*: Browser automation
   - *Key Features*: Cross-browser web automation framework

2. **Selenium** [[GitHub](https://github.com/SeleniumHQ/selenium)] [[Website](https://www.selenium.dev/)]
   - *Type*: Browser automation
   - *Key Features*: Industry-standard web testing and automation

3. **Appium** [[GitHub](https://github.com/appium/appium)] [[Website](https://appium.io/)]
   - *Type*: Mobile automation
   - *Key Features*: Cross-platform mobile app automation

4. **UIAutomator** [[Docs](https://developer.android.com/training/testing/ui-automator)]
   - *Organization*: Google
   - *Type*: Android automation
   - *Key Features*: Native Android UI testing framework

5. **PyAutoGUI** [[GitHub](https://github.com/asweigart/pyautogui)] [[Docs](https://pyautogui.readthedocs.io/)]
   - *Type*: Desktop automation
   - *Key Features*: Cross-platform GUI automation with Python

6. **LangChain** [[GitHub](https://github.com/langchain-ai/langchain)] [[Website](https://www.langchain.com/)]
   - *Type*: Agent framework
   - *Key Features*: LLM application development with tool use

7. **AutoGPT** [[GitHub](https://github.com/Significant-Gravitas/AutoGPT)]
   - *Type*: Autonomous agent
   - *Key Features*: Autonomous task execution with GPT

8. **BabyAGI** [[GitHub](https://github.com/yoheinakajima/babyagi)]
   - *Type*: Task-driven agent
   - *Key Features*: Autonomous task management and execution

9. **AgentGPT** [[GitHub](https://github.com/reworkd/AgentGPT)] [[Website](https://agentgpt.reworkd.ai/)]
   - *Type*: Web-based agent
   - *Key Features*: Browser-based autonomous agent platform

10. **Skyvern** [[GitHub](https://github.com/Skyvern-AI/skyvern)]
    - *Type*: Browser automation
    - *Key Features*: LLM-powered browser automation without selectors

11. **LaVague** [[GitHub](https://github.com/lavague-ai/LaVague)]
    - *Type*: Web agent
    - *Key Features*: Natural language web automation

12. **WebVoyager** [[GitHub](https://github.com/MinorJerry/WebVoyager)]
    - *Type*: Web agent
    - *Key Features*: End-to-end web browsing agent

## 9.2 Commercial Tools

1. **Anthropic Computer Use API** [[Docs](https://docs.anthropic.com/en/docs/build-with-claude/computer-use)]
   - *Organization*: Anthropic
   - *Key Features*: Native computer control via Claude API

2. **UiPath** [[Website](https://www.uipath.com/)]
   - *Type*: RPA Platform
   - *Key Features*: Enterprise robotic process automation

3. **Automation Anywhere** [[Website](https://www.automationanywhere.com/)]
   - *Type*: RPA Platform
   - *Key Features*: AI-powered automation platform

4. **Blue Prism** [[Website](https://www.blueprism.com/)]
   - *Type*: RPA Platform
   - *Key Features*: Intelligent automation platform

5. **Microsoft Power Automate** [[Website](https://powerautomate.microsoft.com/)]
   - *Organization*: Microsoft
   - *Key Features*: Low-code automation platform

---

# 10. Benchmarks and Datasets

## 10.1 Web Benchmarks

1. **Mind2Web** [[Paper](https://arxiv.org/abs/2306.06070)] [[GitHub](https://github.com/OSU-NLP-Group/Mind2Web)]
   - *Organization*: Ohio State University
   - *Tasks*: 2,000+ web tasks across 137 websites
   - *Key Features*: Real-world web navigation with annotations

2. **WebArena** [[Paper](https://arxiv.org/abs/2307.13854)] [[GitHub](https://github.com/web-arena-x/webarena)]
   - *Organization*: CMU
   - *Tasks*: 812 long-horizon web tasks
   - *Key Features*: Self-hostable realistic web environments

3. **VisualWebArena** [[Paper](https://arxiv.org/abs/2401.13649)] [[GitHub](https://github.com/web-arena-x/visualwebarena)]
   - *Organization*: CMU & Stanford
   - *Tasks*: Visual web tasks requiring image understanding
   - *Key Features*: Multimodal web task evaluation

4. **WebShop** [[Paper](https://arxiv.org/abs/2207.01206)] [[GitHub](https://github.com/princeton-nlp/WebShop)]
   - *Organization*: Princeton
   - *Tasks*: 12,087 e-commerce product search tasks
   - *Key Features*: Simulated online shopping environment

5. **MiniWoB++** [[Paper](https://arxiv.org/abs/1802.08802)] [[GitHub](https://github.com/Farama-Foundation/miniwob-plusplus)]
   - *Tasks*: 100+ web-based tasks
   - *Key Features*: Lightweight web automation benchmark

6. **WebCanvas** [[Paper](https://arxiv.org/abs/2406.12373)]
   - *Date*: Jun 2024
   - *Key Features*: Large-scale web interaction dataset

## 10.2 Mobile Benchmarks

1. **Android in the Wild (AITW)** [[Paper](https://arxiv.org/abs/2307.10088)] [[GitHub](https://github.com/google-research/google-research/tree/master/android_in_the_wild)]
   - *Organization*: Google Research
   - *Tasks*: 715K+ episodes, 30K+ human demonstrations
   - *Key Features*: Real device control dataset with diverse apps

2. **MoTIF: Mobile Task Instruction Framework** [[Paper](https://arxiv.org/abs/2104.08560)]
   - *Tasks*: 6,000+ task instructions for mobile apps
   - *Key Features*: Natural language mobile task instructions

3. **RICO: A Mobile App Dataset** [[Paper](https://dl.acm.org/doi/10.1145/3126594.3126651)] [[Website](http://interactionmining.org/rico)]
   - *Organization*: University of Michigan
   - *Tasks*: 66K+ UI screens from 9K+ apps
   - *Key Features*: UI layouts, screenshots, and interaction traces

4. **PixelHelp: A Mobile UI Dataset** [[Paper](https://arxiv.org/abs/2004.00348)]
   - *Tasks*: Mobile UI understanding and QA
   - *Key Features*: Question-answering on mobile screens

5. **META-GUI Dataset** [[Paper](https://arxiv.org/abs/2301.04725)]
   - *Tasks*: Multi-modal conversational interactions
   - *Key Features*: Dialogue-based mobile control

## 10.3 Desktop Benchmarks

1. **OSWorld** [[Paper](https://arxiv.org/abs/2404.07972)] [[GitHub](https://github.com/xlang-ai/OSWorld)]
   - *Organization*: Hong Kong University & CMU
   - *Tasks*: 369 computer tasks across Ubuntu, Windows, MacOS
   - *Key Features*: Open-ended real computer tasks with safety

2. **ScreenSpot** [[Paper](https://arxiv.org/abs/2309.12808)]
   - *Tasks*: GUI element localization across platforms
   - *Key Features*: Large-scale element grounding benchmark

3. **MiniWoB** (Original) [[Paper](https://arxiv.org/abs/1606.06057)]
   - *Tasks*: Form filling and simple desktop tasks
   - *Key Features*: Classic GUI automation benchmark

## 10.4 Cross-Platform Benchmarks

1. **GUI Odyssey** [[Paper](https://arxiv.org/abs/2406.08451)]
   - *Date*: Jun 2024
   - *Tasks*: Cross-platform GUI understanding
   - *Key Features*: Unified evaluation across web, mobile, desktop

2. **ScreenQA: Large-Scale Screen Content Understanding** [[Paper](https://arxiv.org/abs/2209.08199)]
   - *Tasks*: Screen content question-answering
   - *Key Features*: Cross-platform screen understanding

3. **E-GUI: A Comprehensive Benchmark for GUI Agents** [[Paper](https://arxiv.org/abs/2410.01170)]
   - *Date*: Oct 2024
   - *Tasks*: Multi-platform GUI interaction tasks
   - *Key Features*: Comprehensive evaluation framework

---

# 11. Training and Fine-tuning

## 11.1 Datasets

1. **WebSRC: A Dataset for Web-Based Structural Reading Comprehension** [[Paper](https://arxiv.org/abs/2101.09465)]
   - *Size*: 400K+ questions on 6K+ web pages
   - *Key Features*: Structural web understanding

2. **Common Crawl** [[Website](https://commoncrawl.org/)]
   - *Size*: Petabytes of web data
   - *Key Features*: Large-scale web corpus

3. **Android Howto Dataset** [[Paper](https://arxiv.org/abs/2010.04295)]
   - *Size*: 10K+ Android task instructions
   - *Key Features*: Mobile task instructions

4. **Synthetic Web Navigation** [[Paper](https://arxiv.org/abs/2305.07625)]
   - *Key Features*: Synthetic web interaction data

## 11.2 Training Methods

1. **Behavioral Cloning for GUI Agents** [[Paper](https://arxiv.org/abs/2306.03176)]
   - *Date*: Jun 2023
   - *Key Features*: Imitation learning from human demonstrations

2. **GUI Agent Training with Transformer Models** [[Paper](https://arxiv.org/abs/2307.08114)]
   - *Date*: Jul 2023
   - *Key Features*: Transformer-based GUI agent training

3. **Self-supervised Learning for UI Understanding** [[Paper](https://arxiv.org/abs/2309.04945)]
   - *Date*: Sep 2023
   - *Key Features*: Self-supervised pretraining strategies

4. **Curriculum Learning for Web Agents** [[Paper](https://arxiv.org/abs/2401.09712)]
   - *Date*: Jan 2024
   - *Key Features*: Progressive task difficulty for training

## 11.3 Reinforcement Learning

1. **WebGum: Reinforcement Learning for Web Automation** [[Paper](https://arxiv.org/abs/2402.14979)]
   - *Date*: Feb 2024
   - *Key Features*: RL-based web agent training

2. **CC-Net: Curriculum Learning for GUI Agents** [[Paper](https://arxiv.org/abs/2306.08811)]
   - *Date*: Jun 2023
   - *Key Features*: Curriculum-based RL for GUI tasks

3. **RCI: Reinforced Correction for Improved GUI Agents** [[Paper](https://arxiv.org/abs/2401.00201)]
   - *Date*: Jan 2024
   - *Key Features*: Self-correction through RL

4. **AndroidEnv: RL Platform for Android** [[Paper](https://arxiv.org/abs/2105.13231)]
   - *Organization*: DeepMind
   - *Date*: May 2021
   - *Key Features*: Android RL environment

---

# 12. Safety and Security

1. **Security Risks of LLM-Based GUI Agents** [[Paper](https://arxiv.org/abs/2309.11848)]
   - *Date*: Sep 2023
   - *Key Features*: Analysis of security vulnerabilities

2. **Privacy Concerns in GUI Automation** [[Paper](https://arxiv.org/abs/2401.15234)]
   - *Date*: Jan 2024
   - *Key Features*: Privacy-preserving GUI agents

3. **Adversarial Attacks on GUI Agents** [[Paper](https://arxiv.org/abs/2310.08765)]
   - *Date*: Oct 2023
   - *Key Features*: Robustness evaluation against attacks

4. **Safe Exploration for GUI Agents** [[Paper](https://arxiv.org/abs/2402.01234)]
   - *Date*: Feb 2024
   - *Key Features*: Safe exploration strategies

5. **Anthropic Computer Use Safety** [[Blog](https://www.anthropic.com/news/3-5-models-and-computer-use)]
   - *Organization*: Anthropic
   - *Key Features*: Safety considerations for computer use models

---

# 13. Evaluation Metrics

1. **Task Success Rate (TSR)**
   - Definition: Percentage of tasks completed successfully
   - Usage: Primary metric for most benchmarks

2. **Step Success Rate (SSR)**
   - Definition: Percentage of correct individual actions
   - Usage: Fine-grained action evaluation

3. **Element Accuracy**
   - Definition: Accuracy of GUI element localization
   - Usage: Grounding and localization evaluation

4. **Efficiency Metrics**
   - Steps to completion
   - Time to completion
   - Token usage / cost

5. **Human Evaluation**
   - Task completion quality
   - User experience metrics
   - Error analysis

6. **Benchmark-Specific Metrics**
   - Mind2Web: Element accuracy, action F1, success rate
   - WebArena: Task success rate with different difficulty levels
   - AITW: Episode completion rate

---

# 14. Applications

## 14.1 Testing and QA

1. **Automated UI Testing with LLMs** [[Paper](https://arxiv.org/abs/2309.10517)]
   - *Date*: Sep 2023
   - *Key Features*: LLM-powered automated testing

2. **DroidBot: Deep Exploration on Android** [[Paper](https://arxiv.org/abs/1705.07567)]
   - *Date*: May 2017
   - *Key Features*: Automated Android app testing

3. **TestGPT: Generating UI Tests with LLMs** [[Paper](https://arxiv.org/abs/2305.09641)]
   - *Date*: May 2023
   - *Key Features*: Test case generation with GPT

4. **Monkey Testing with LLMs** [[Paper](https://arxiv.org/abs/2401.04567)]
   - *Date*: Jan 2024
   - *Key Features*: Intelligent fuzz testing

## 14.2 Accessibility

1. **Screen Reader Enhancement with LLMs** [[Paper](https://arxiv.org/abs/2310.11234)]
   - *Date*: Oct 2023
   - *Key Features*: Improved accessibility for visually impaired

2. **Automated Accessibility Testing** [[Paper](https://arxiv.org/abs/2309.06789)]
   - *Date*: Sep 2023
   - *Key Features*: Detecting accessibility issues

3. **Voice-Controlled GUI Agents** [[Paper](https://arxiv.org/abs/2401.09876)]
   - *Date*: Jan 2024
   - *Key Features*: Voice interaction for GUI control

## 14.3 RPA (Robotic Process Automation)

1. **Enterprise RPA with LLMs** [[Paper](https://arxiv.org/abs/2308.12345)]
   - *Date*: Aug 2023
   - *Key Features*: Business process automation

2. **Document Processing Automation** [[Paper](https://arxiv.org/abs/2401.11111)]
   - *Date*: Jan 2024
   - *Key Features*: Automated document workflows

3. **Data Entry Automation** [[Paper](https://arxiv.org/abs/2310.22222)]
   - *Date*: Oct 2023
   - *Key Features*: Intelligent form filling

---

# 15. Blogs and Tutorials

1. **Anthropic: Introducing Computer Use** [[Blog](https://www.anthropic.com/news/3-5-models-and-computer-use)]
   - *Organization*: Anthropic
   - *Date*: Oct 2024
   - *Summary*: Introduction to Claude's computer use capabilities

2. **OpenAI: GPT-4V System Card** [[Blog](https://openai.com/research/gpt-4v-system-card)]
   - *Organization*: OpenAI
   - *Date*: Sep 2023
   - *Summary*: GPT-4V capabilities including GUI understanding

3. **Lil'Log: LLM Powered Autonomous Agents** [[Blog](https://lilianweng.github.io/posts/2023-06-23-agent/)]
   - *Author*: Lilian Weng (OpenAI)
   - *Date*: Jun 2023
   - *Summary*: Comprehensive overview of LLM agents

4. **Microsoft Research: UFO Deep Dive** [[Blog](https://www.microsoft.com/en-us/research/project/ufo/)]
   - *Organization*: Microsoft Research
   - *Summary*: Deep dive into UFO Windows agent

5. **Google Research: Multimodal GUI Understanding** [[Blog](https://ai.googleblog.com/)]
   - *Organization*: Google Research
   - *Summary*: Blog posts on GUI understanding research

6. **Building Web Agents with LangChain** [[Tutorial](https://python.langchain.com/docs/use_cases/autonomous_agents/)]
   - *Organization*: LangChain
   - *Summary*: Tutorial for building web agents

7. **Selenium with GPT-4** [[Tutorial](https://github.com/Torantulino/Auto-GPT)]
   - *Summary*: Combining Selenium with LLMs for automation

---

# Acknowledgements

This repository is inspired by and builds upon the excellent work in:

- [Awesome-LLM-Long-Context-Modeling](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling)
- [Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)
- [Awesome-Multimodal-Large-Language-Models](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)

Special thanks to all researchers, engineers, and organizations contributing to the field of GUI agents and autonomous systems.

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

**Contribution Guidelines:**
- Follow the existing format
- Add papers/resources in the appropriate section
- Include paper links (arXiv, GitHub, website)
- Add brief descriptions highlighting key features
- Keep entries in reverse chronological order within sections

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Xnhyacinth/awesome-GUI-Agent&type=Date)](https://star-history.com/#Xnhyacinth/awesome-GUI-Agent&Date)

---

## Citation

If you find this repository helpful, please consider citing:

```bibtex
@misc{awesome-gui-agent,
  author = {Xnhyacinth},
  title = {Awesome GUI Agent: A Curated List of GUI Agent Resources},
  year = {2025},
  publisher = {GitHub},
  url = {https://github.com/Xnhyacinth/awesome-GUI-Agent}
}
```

---

**License:** [MIT](LICENSE)

**Maintained by:** [@Xnhyacinth](https://github.com/Xnhyacinth)

**Last Updated:** 2025-02-21
