# Awesome GUI Agent Datasets for Computer-Use and Phone-Use

A curated list of datasets for training GUI agents—AI systems that automate interactions with graphical user interfaces on computers, phones, and browsers. Sorted by year (most recent first).

---

## 2026

- **AndroidDaily**
  - *Description*: A verifiable benchmark for mobile GUI agents on real-world closed-source Android applications, emphasizing automated result verification without human judges.
  - *Data*: Tasks across popular closed-source apps (e.g., Maps, YouTube) with executable verification scripts.
  - *URL*: https://arxiv.org/abs/2605.27761

- **ClawBench**
  - *Description*: An open benchmark and trace corpus for AI browser agents operating live websites, with isolated runs and replayable five-layer execution evidence.
  - *Data*: V1 includes 153 tasks across 144 live websites, plus per-run video, screenshots, HTTP traffic, browser actions, and agent messages; V2 adds 130 tasks with rolling trace releases.
  - *URL*: https://huggingface.co/datasets/NAIL-Group/ClawBench ; https://huggingface.co/datasets/NAIL-Group/ClawBenchV1Trace ; https://github.com/TIGER-AI-Lab/ClawBench

---

## 2025

- **Aria-UI/Aria-UI_Data**
  - *Description*: A comprehensive collection of GUI grounding data covering web, mobile, and desktop interfaces, designed for versatile grounding instruction understanding and context-aware grounding.
  - *Data*: Web Data (2.9M instructions, 173k images), Mobile Data (1.1M instructions, 104k images from AMEX), Desktop Data (150k instructions, 7.8k images from Ubuntu).
  - *URL*: https://huggingface.co/datasets/Aria-UI/Aria-UI_Data

- **Multimodal-Mind2Web**
  - *Description*: A multimodal version of Mind2Web, pairing HTML documents with corresponding website screenshots to support the development of general-purpose web agents.
  - *Data*: 7,775 actions from 1,009 training tasks; 1,339 actions from 177 test tasks (same website), 1,019 actions from 142 test tasks (new website), 4,060 actions from 694 test tasks (new domain).
  - *URL*: https://huggingface.co/datasets/osunlp/Multimodal-Mind2Web

- **GUIMid**
  - *Description*: A consolidated mid-training dataset designed to enhance the foundational agentic capabilities of VLMs for GUI tasks, by leveraging data from adjacent, non-GUI domains.
  - *Data*: 300,000 samples — MathInstruct (150k), CodeI/O (20k), Olympiad Math (50k), Multi-modal Math (80k).
  - *URL*: https://github.com/hkust-nlp/GUIMid

- **STEVE (Windows OS dataset)**
  - *Description*: A Windows OS dataset for UI grounding, collected via Windows VM, OmniParser, screenshots, and accessibility tree data.
  - *Data*: 10,000 desktop images and 80,000 UI elements, augmented with AITW public data.
  - *URL*: https://github.com/FanbinLu/STEVE

- **Aguvis Data Collection (xlangai/aguvis-stage1 & stage2)**
  - *Description*: A large-scale cross-platform dataset of GUI agent trajectories with multimodal grounding and reasoning annotations, including inner monologue. Stage 1 focuses on grounding, Stage 2 on planning/reasoning trajectories.
  - *Data*: Stage 1: 4.2M grounding samples; Stage 2: 1.3M agent trajectories across web, desktop, and mobile.
  - *URL*: https://huggingface.co/datasets/xlangai/aguvis-stage1 ; https://huggingface.co/datasets/xlangai/aguvis-stage2

- **OS-Genesis**
  - *Description*: An interaction-driven pipeline synthesizing high-quality GUI agent trajectory data without human supervision, using reverse task synthesis and a trajectory reward model.
  - *Data*: Raw triples `<s_pre, a, s_post>`, complete trajectory data, SoM (State-of-Mind) info. Covers Mobile and Web platforms.
  - *URL*: https://github.com/OS-Copilot/OS-Genesis

- **Mobile-R1 (PG23/Mobile-R1)**
  - *Description*: A high-quality dataset for training VLM-based mobile agents, focused on Chinese mobile applications.
  - *Data*: 1,007 trajectories across 28 apps, 3,924 total steps, full interaction trajectories with screenshots and action parameters.
  - *URL*: https://mobile-r1.github.io/Mobile-R1/

- **ShowUI_desktop**
  - *Description*: A vision–language–action dataset for desktop GUI element grounding with rich bounding-box and keypoint annotations.
  - *Data*: ~7,500 desktop screenshots across 15 apps; 8,000 element annotations with bounding boxes, spatial-relation, and intent queries.
  - *URL*: https://huggingface.co/datasets/Voxel51/ShowUI_desktop

- **GUI-Robust**
  - *Description*: A dataset evaluating GUI agent performance under seven real-world anomaly conditions (occlusion, dynamic content changes, etc.), using a semi-automated collection combining RPA recordings and MLLM annotation.
  - *Data*: 10,000+ action sequences with seven anomaly types, task descriptions, stepwise instructions, screenshots, and grounding metadata.
  - *URL*: https://github.com/chessbean1/GUI-Robust

- **VideoGUI**
  - *Description*: A multi-modal benchmark from professional instructional videos, evaluating agents across hierarchical levels: high-level planning, mid-level planning, and atomic action execution.
  - *Data*: 86 complex tasks (avg. 22.7 actions each), 463 subtasks, 2.7K manually annotated actions across 11 software applications.
  - *URL*: https://github.com/showlab/videogui

- **Mind2Web 2**
  - *Description*: A benchmark of 130 realistic, long-horizon tasks requiring real-time web browsing and extensive information synthesis, constructed with 1,000+ hours of human labor. Introduces an Agent-as-a-Judge evaluation framework.
  - *Data*: 130 tasks with time-varying and complex answer structures.
  - *URL*: https://huggingface.co/datasets/osunlp/Mind2Web-2

- **Online-Mind2Web**
  - *Description*: An online version of Mind2Web with tasks evaluated in real-world online environments across domains like clothing, food, housing, and transportation.
  - *Data*: 300 tasks from 136 websites, with task_id, website, task_description, and reference_length fields.
  - *URL*: https://github.com/OSU-NLP-Group/Online-Mind2Web

- **LearnGUI**
  - *Description*: A dataset for studying illustration-based learning in mobile GUI agents, enhancing performance in unseen scenarios.
  - *Data*: 2,252 offline and 101 online tasks across 73 apps, with high-quality human demonstrations, screenshots, and action sequences.
  - *URL*: https://huggingface.co/datasets/lgy0404/LearnGUI

- **AndroidInteraction**
  - *Description*: Focuses on user interaction needs and notifications in phone UI automation, enabling agent-initiated interactions.
  - *Data*: 750+ demonstrations across 250+ apps, including action-observation pairs with screenshots and accessibility metadata.
  - *URL*: https://arxiv.org/abs/2503.19537

- **WorldGUI**
  - *Description*: An interactive benchmark for desktop GUI automation supporting tasks across multiple applications from any starting point.
  - *Data*: 611 tasks across 10 desktop and web apps, with user queries, instructional videos, and project files.
  - *URL*: https://github.com/showlab/WorldGUI

- **DeskVision**
  - *Description*: Large-scale desktop region captioning dataset for advanced GUI agents, improving visual element understanding.
  - *Data*: Large-scale desktop GUI dataset with rich annotations for diverse UI systems and elements using automated captioning.
  - *URL*: https://arxiv.org/abs/2503.11170

- **GUI-Lasagne**
  - *Description*: Multi-level, large-scale dataset for training agents like SpiritSight, focusing on GUI understanding and grounding.
  - *Data*: 5.73M samples, 2.24M screenshots, 57.8M elements, with a 3-tier structure for image-text alignment and navigation.
  - *URL*: https://arxiv.org/abs/2503.03196

- **TongUI / GUI-Net**
  - *Description*: Builds generalized GUI agents by learning from multimodal web tutorials across multiple operating systems.
  - *Data*: 143K–1M trajectory data points across 5 OS and 200+ apps, with multimodal web instructions, text, and screenshots.
  - *URL*: https://tongui-agent.github.io/

- **ScreenSpot-Pro**
  - *Description*: Benchmark for GUI grounding in high-resolution professional environments for multimodal LLMs.
  - *Data*: 1,581 task data points across 23 industries, with high-resolution screenshots, natural language instructions, and bounding box annotations.
  - *URL*: https://huggingface.co/datasets/Voxel51/ScreenSpot-Pro

- **WebGames**
  - *Description*: A dataset for training agents to play web-based games, focusing on interactive GUI tasks.
  - *Data*: 50+ unique interactive challenges in JSONL format with 160×210px environments and text-based goals.
  - *URL*: https://github.com/convergence-ai/webgames

- **Explorer**
  - *Description*: The largest-scale web trajectory dataset to date, dynamically exploring web pages to create contextually relevant tasks.
  - *Data*: 94K successful web trajectories, 49K unique URLs, 720K screenshots, generated by a multi-agent LLM pipeline.
  - *URL*: https://arxiv.org/abs/2502.11357

- **InSTA**
  - *Description*: An Internet-scale dataset for training GUI-based web agents, generated through an automated LLM pipeline without human annotations.
  - *Data*: 150k diverse websites from Common Crawl, rich web navigation tasks, trajectories in Playwright API calls, LLM-based evaluation.
  - *URL*: https://huggingface.co/datasets/data-for-agents/insta-150k-v3

- **VideoCAD**
  - *Description*: A large-scale synthetic dataset for learning UI interactions and 3D reasoning from CAD software, with annotated video recordings of CAD operations.
  - *Data*: 41K+ annotated video recordings of CAD operations (up to 20× longer time horizon than other datasets).
  - *URL*: https://arxiv.org/abs/2505.24838

- **AutomotiveUI-Bench-4K**
  - *Description*: An open-source dataset for understanding and interacting with automotive infotainment systems, serving as a validation benchmark for automotive UI.
  - *Data*: 998 images with 4,208 annotations across 15 automotive brands (2018–2025 models); IVI UI in German and English, annotations in English.
  - *URL*: https://paperswithcode.com/dataset/automotiveui-bench-4k

- **OS-Atlas**
  - *Description*: A foundational GUI action model excelling at GUI grounding and OOD agentic tasks, leveraging a large open-source cross-platform grounding corpus.
  - *Data*: 13M+ GUI elements across mobile, desktop, and web platforms, synthesized via a specialized toolkit. Includes ScreenSpot-v2 benchmark.
  - *URL*: https://osatlas.github.io/

- **UGround Web-Hybrid (UGround-V1)**
  - *Description*: The largest GUI visual grounding dataset at release (ICLR 2025 Oral), training the UGround universal visual grounding model. Built from web-based synthetic data by OSU NLP + Orby AI.
  - *Data*: 10M GUI elements (~95% web) over 1.3M screenshots; Web-Hybrid split is ~8M elements / 775K screenshots. Format: screenshot + referring expression → coordinates.
  - *URL*: https://arxiv.org/abs/2410.05243 ; https://huggingface.co/osunlp/UGround-V1-7B

- **Jedi (with OSWorld-G benchmark)**
  - *Description*: Computer-use grounding dataset built via UI decomposition and synthesis; trains Jedi-3B/7B and improves OSWorld agent success from 23% to 51%. NeurIPS 2025 Spotlight (xlang-ai). Companion benchmark OSWorld-G has 564 samples across 32 UI-types.
  - *Data*: 4M grounding examples across four pipelines (icon grounding, component rendering, document/spreadsheet/presentation augmentation). Desktop-focused.
  - *URL*: https://arxiv.org/abs/2505.13227 ; https://huggingface.co/datasets/xlangai/Jedi ; https://github.com/xlang-ai/OSWorld-G

- **AutoGUI-704k**
  - *Description*: Functionality-annotated GUI grounding dataset where an LLM infers element functionality by comparing UI states before/after simulated interactions. Annotation accuracy ~96.7%. ACL 2025.
  - *Data*: ~704k functionality grounding/referring tasks; multi-device screenshots spanning web (861 domains from Common Crawl) and Android.
  - *URL*: https://arxiv.org/abs/2502.01977 ; https://huggingface.co/datasets/AutoGUI/AutoGUI-v1-702k

- **AgentNet (OpenCUA)**
  - *Description*: First large-scale open desktop computer-use trajectory dataset with reflective long chain-of-thought reasoning per step, collected via the AgentNetTool cross-platform screen recorder. NeurIPS 2025 Spotlight (xlang-ai). MIT License.
  - *Data*: 22,625 trajectories averaging 18.6 steps each, spanning 140+ applications and 190 websites across Windows (~12K), macOS (~5K), and Ubuntu (~5K).
  - *URL*: https://arxiv.org/abs/2508.09123 ; https://huggingface.co/datasets/xlangai/AgentNet ; https://github.com/xlang-ai/OpenCUA

- **OSWorld**
  - *Description*: First scalable real-computer task environment for multimodal agents with execution-based evaluation across Ubuntu/Windows/macOS. Humans complete 72.36% vs. best model 12.24% at release. NeurIPS 2024; OSWorld-Verified released July 2025.
  - *Data*: 369 computer tasks, each with an initial-state config and a custom execution-based evaluation script.
  - *URL*: https://arxiv.org/abs/2404.07972 ; https://github.com/xlang-ai/OSWorld

- **WindowsAgentArena (WAA)**
  - *Description*: Windows-focused, reproducible multimodal OS agent benchmark built on the OSWorld framework; parallelizable via Azure (full eval in ~20 minutes). The Navi baseline reached 19.5% vs. 74.5% human success.
  - *Data*: 154 diverse multi-step tasks across 7 Windows app categories (Office, browser, system settings, VS Code, media, etc.).
  - *URL*: https://arxiv.org/abs/2409.08264 ; https://microsoft.github.io/WindowsAgentArena/

- **VeriGUI**
  - *Description*: First verifiable long-chain GUI dataset emphasizing subtask-level verifiability and long-horizon complexity; supports open-ended interaction within each subtask.
  - *Data*: Richly annotated GUI task trajectories across desktop and web (130 web task trajectories in initial release, expanding). Human-expert annotated.
  - *URL*: https://arxiv.org/abs/2508.04026 ; https://github.com/VeriGUI-Team/VeriGUI

- **GUI-ReWalk**
  - *Description*: Reasoning-enhanced framework synthesizing diverse GUI trajectories via stochastic random-walk exploration plus task-guided completion. IJCAI 2026 accepted (ByteDance).
  - *Data*: 50k+ annotated tasks averaging ~22.5 steps, multi-platform (mobile + desktop). Pipeline released under Apache-2.0.
  - *URL*: https://arxiv.org/abs/2509.15738 ; https://github.com/bytedance/GUI-ReWalk

- **AgentSynth**
  - *Description*: Scalable computer-use trajectory generation pipeline that chains executable subtasks into complex, long-horizon datasets by exploiting information asymmetry.
  - *Data*: Synthetic generalist computer-use tasks/trajectories (cost-efficient generation pipeline).
  - *URL*: https://arxiv.org/abs/2506.01968

- **WorkArena / WorkArena++**
  - *Description*: Enterprise "knowledge worker" web-agent benchmark on ServiceNow, delivered via BrowserGym. WorkArena++ adds compositional planning and reasoning tasks. ICML 2024 / NeurIPS 2024.
  - *Data*: WorkArena: 29 tasks (20k+ instances); WorkArena++: compositional tasks built on the atomic set.
  - *URL*: https://arxiv.org/abs/2403.07718 ; https://arxiv.org/abs/2407.05291

- **BrowserGym**
  - *Description*: Unified gym environment for web-agent research, bundling MiniWoB++, WebArena, VisualWebArena, WorkArena, WebLINX, AssistantBench under a single API with multimodal observations.
  - *Data*: Multimodal observations (HTML, accessibility tree, screenshot, element coordinates) with a standardized flexible action space.
  - *URL*: https://arxiv.org/abs/2412.05467 ; https://github.com/ServiceNow/BrowserGym

- **ST-WebAgentBench**
  - *Description*: Benchmark for safety and trustworthiness of web agents built on WebArena/BrowserGym, covering six safety dimensions (user-consent, boundary, strict execution, hierarchy, robustness, error handling).
  - *Data*: 222 tasks across GitLab/ShoppingAdmin/SuiteCRM plus 646 policy instances.
  - *URL*: https://arxiv.org/abs/2410.06703

- **Falcon-UI**
  - *Description*: GUI instruction dataset and model emphasizing understanding GUI context before following user instructions (Dec 2024).
  - *Data*: Large-scale GUI screenshot/context dataset for instruction-free pretraining across multiple platforms.
  - *URL*: https://arxiv.org/abs/2412.09362

- **SPA-Bench**
  - *Description*: Comprehensive smartphone-agent benchmark with a plug-and-play execution framework, automatic evaluation pipeline, and bilingual support (English + Chinese). ICLR 2025 Spotlight (Huawei Noah's Ark Lab).
  - *Data*: 340 Android tasks (300 single-app + 40 cross-app) across system and third-party apps, with 7 task-completion/resource metrics.
  - *URL*: https://arxiv.org/abs/2410.15164 ; https://github.com/ai-agents-2030/SPA-Bench

- **AndroidLab (with Android Instruct)**
  - *Description*: Reproducible Android agent environment + benchmark + training dataset supporting XML and Set-of-Marks operation modes. ACL 2025.
  - *Data*: 138 benchmark tasks across 9 apps; Android Instruct training set of 94.3k operation records (text-only + multimodal).
  - *URL*: https://arxiv.org/abs/2410.24024 ; https://aclanthology.org/2025.acl-long.107/

- **MONDAY**
  - *Description*: Scalable video-to-dataset pipeline producing cross-platform mobile-navigation data from YouTube instructional videos; improves cross-platform generalization. CVPR 2025.
  - *Data*: 20K instructional videos; 333K detected scenes; 313K annotated frames/actions; Android + iOS.
  - *URL*: https://arxiv.org/abs/2505.12632 ; https://github.com/runamu/monday

- **UI-Vision**
  - *Description*: First license-permissive desktop-centric GUI benchmark for offline fine-grained evaluation with three tasks: Element Grounding, Layout Grounding, Action Prediction. ICML 2025 (Mila/ServiceNow).
  - *Data*: 83 desktop applications across 6 categories; dense human-demonstration annotations (bounding boxes, UI labels, click/drag/keyboard trajectories).
  - *URL*: https://arxiv.org/abs/2503.15661 ; https://huggingface.co/datasets/ServiceNow/ui-vision

- **WinSpot**
  - *Description*: First GUI grounding benchmark specifically designed for Windows desktop environments. ACL 2025 (short paper).
  - *Data*: Windows GUI screenshots with grounding instruction → element annotations (high-quality train/eval set).
  - *URL*: https://aclanthology.org/2025.acl-short.85/

- **Mobile-Bench-v2**
  - *Description*: More realistic and comprehensive VLM-based mobile agent benchmark with offline multi-path evaluation and an ad/noise-contaminated variant (AITZ-Noise) for robustness.
  - *Data*: Multi-path mobile trajectories with checkpoint-style metrics.
  - *URL*: https://arxiv.org/abs/2505.11891

- **ColorBench**
  - *Description*: Benchmarks mobile agents using a graph-structured framework (trajectory graphs rather than rigid chains) for complex long-horizon tasks.
  - *Data*: Mobile long-horizon tasks with graph-structured decision modeling.
  - *URL*: https://arxiv.org/abs/2510.14621

- **UI-Genie (UI-Genie-RM-517k & UI-Genie-Agent-16k)**
  - *Description*: Self-improving framework with a specialized GUI reward model; generates the first large-scale GUI reward dataset plus high-quality synthetic trajectories without manual annotation. NeurIPS 2025.
  - *Data*: UI-Genie-RM-517k (~458K synthetic reward samples + ~59K from exploration); UI-Genie-Agent-16k (16K synthetic mobile/Android trajectories, image-text interleaved).
  - *URL*: https://arxiv.org/abs/2505.21496 ; https://github.com/Euphoria16/UI-Genie

- **GUI-Critic-R1**
  - *Description*: Pre-operative critic datasets for diagnosing GUI action errors before execution; built via reasoning-bootstrapping from public trajectories (AITZ, AMEX, GUI-Odyssey, AITW). NeurIPS 2025 (X-PLUG).
  - *Data*: GUI-Critic-Train: 6K CoT samples (mobile); GUI-Critic-Test: 1K samples (mobile + web), each with correctness score, critique, and suggestion.
  - *URL*: https://arxiv.org/abs/2506.04614 ; https://github.com/X-PLUG/MobileAgent/tree/main/GUI-Critic-R1

- **GUI-Reflection**
  - *Description*: Framework + data equipping multimodal GUI models with self-reflection and error-correction across pre-training, offline SFT, and online tuning phases.
  - *Data*: Reflection-oriented training data combined with grounding/navigation sources (AMEX, AndroidControl, GUI-Odyssey, etc.).
  - *URL*: https://arxiv.org/abs/2506.08012

- **MMBench-GUI**
  - *Description*: Hierarchical multi-platform GUI evaluation framework with four ascending levels (content understanding, element grounding, task automation, task collaboration) and an Efficiency-Quality-Aware metric.
  - *Data*: Multi-level, multi-platform tasks spanning mobile, desktop, and web.
  - *URL*: https://arxiv.org/abs/2507.19478

- **GUI-Bee**
  - *Description*: Aligns GUI action grounding to novel environments via autonomous exploration, generating environment-specific grounding data (Jan 2025).
  - *Data*: Self-collected, environment-specific grounding data across diverse GUIs.
  - *URL*: https://arxiv.org/abs/2501.13896

- **EDGE**
  - *Description*: Enhanced grounded GUI understanding using enriched multi-granularity synthetic data (Nov 2024).
  - *Data*: Multi-granularity GUI understanding data (element-level, region-level, screen-level).
  - *URL*: https://arxiv.org/abs/2411.07618

---

## 2024

- **MultiUI**
  - *Description*: A large-scale dataset for GUI agents' text-rich visual understanding, using structured accessibility trees to generate high-quality multimodal instructions.
  - *Data*: 7.3M multimodal instruction samples from 1M websites, covering element grounding, action prediction, and interaction modeling.
  - *URL*: https://huggingface.co/datasets/neulab/MultiUI

- **Mind2Web-Live**
  - *Description*: Dynamic evaluation using "key nodes" representing critical intermediate states in web tasks.
  - *Data*: 542 tasks with 4,550 detailed annotation steps, annotated by human experts.
  - *URL*: https://huggingface.co/datasets/iMeanAI/Mind2Web-Live

- **WebVLN**
  - *Description*: Expands web GUI tasks by combining navigation with question-answering; agents use text queries to locate relevant web pages and extract information.
  - *Data*: 8,990 navigation paths and 14,825 QA pairs, leveraging HTML and visual content from websites.
  - *URL*: https://drive.google.com/drive/folders/1Gzm44P5QBxvBYUU4BiYW-WlxbiB5M19K

- **WebLINX**
  - *Description*: Focuses on conversational GUI agents, emphasizing real-world web navigation through multi-turn dialogue.
  - *Data*: 2,300+ expert demonstrations with 100,000+ interactions across 155 real-world websites, including DOM trees and screenshots.
  - *URL*: https://huggingface.co/datasets/McGill-NLP/WebLINX

- **AgentTrek**
  - *Description*: Synthesizes high-quality trajectory data by leveraging web tutorials.
  - *Data*: 4,902 trajectories with task metadata, step-by-step instructions, action sequences, visual observations, and reproducible native traces.
  - *URL*: https://agenttrek.github.io/

- **ScreenAI**
  - *Description*: Extends data collection to mobile and desktop interfaces, covering screen annotation, question-answering, and navigation tasks.
  - *Data*: Hundreds of millions of annotated samples.
  - *URL*: https://github.com/google-research-datasets/screen_qa

- **VisualAgentBench**
  - *Description*: A cross-platform benchmark assessing GUI agents in both mobile and web settings, emphasizing interaction-focused tasks.
  - *Data*: Uses Android Virtual Device and WebArena-Lite environments.
  - *URL*: https://github.com/THUDM/VisualAgentBench

- **VGA**
  - *Description*: A VQA dataset minimizing "hallucinations" in VLMs for GUI understanding by balancing attention between image and text inputs. Uses a "Referent Method" to align responses to visual content.
  - *Data*: 63.8k high-quality VQA examples, based on the Rico dataset.
  - *URL*: https://github.com/Linziyang1999/VGA-visual-GUI-assistant

- **MobileViews**
  - *Description*: Large-scale mobile GUI dataset with screenshot-view hierarchy pairs from thousands of Android apps.
  - *Data*: 600,000+ screenshot-view hierarchy pairs including .jpg screenshots, .json/.xml view hierarchies, and action logs.
  - *URL*: https://huggingface.co/datasets/mllmTeam/MobileViews

- **AMEX (Android Multi-annotation EXpo)**
  - *Description*: High-resolution screenshots from popular mobile apps with detailed element-level and instruction-level annotations.
  - *Data*: 104,000+ high-resolution screenshots, 711,000 element-level functions, 3,000 unique instructions with multi-step GUI action sequences.
  - *URL*: https://huggingface.co/datasets/Yuxiang007/AMEX

- **AndroidControl**
  - *Description*: Demonstrations of daily tasks across hundreds of Android apps, exploring data scale effects on agent performance.
  - *Data*: 15,283 task demonstrations with 14,548 unique tasks including high/low-level instructions, screenshots, and accessibility trees.
  - *URL*: https://huggingface.co/datasets/HarrytheOrange/parsed_AndroidControl

- **AndroidControl-Curated**
  - *Description*: Purified/corrected version of AndroidControl that fixes evaluation bias and label errors. The companion Magma-R1 trained on just 2,400 curated samples achieves strong performance.
  - *Data*: Curated subset of AndroidControl's ~90k samples (Easy + Hard subsets); exact curated count not published.
  - *URL*: https://arxiv.org/abs/2510.18488 ; https://huggingface.co/datasets/batwBMW/AndroidControl_Curated

- **B-MoCA**
  - *Description*: Benchmark for evaluating mobile control agents across diverse device configurations.
  - *Data*: 131 daily tasks and 60 real-world tasks across varied device configurations.
  - *URL*: https://github.com/gimme1dollar/b-moca

- **MobileAgentBench**
  - *Description*: User-friendly benchmark with tasks across open-source apps for testing mobile LLM agents.
  - *Data*: 100 tasks across 10 open-source Android apps, categorized by difficulty, with real-device execution support.
  - *URL*: https://MobileAgentBench.github.io

- **Mobile3M**
  - *Description*: Large-scale mobile app dataset for training GUI agents with real-world UI transitions.
  - *Data*: 3M UI pages and real-world transitions from 49 popular Chinese apps, with XML documents and directed graph structures in Parquet format.
  - *URL*: https://huggingface.co/datasets/xwk123/Mobile3M

- **OmniACT**
  - *Description*: Dataset for multimodal generalist agents performing tasks on desktop and web interfaces.
  - *Data*: 9,800+ image-instruction pairs with natural language tasks and PyAutoGUI-executable commands.
  - *URL*: https://arxiv.org/abs/2402.17553

- **VisualWebArena**
  - *Description*: A dataset for training agents to interact with web interfaces using visual inputs, built on top of WebArena.
  - *Data*: Image-based tasks with executable evaluations focusing on multimodal web interactions.
  - *URL*: https://github.com/web-arena-x/visualwebarena

- **WebCanvas**
  - *Description*: A dataset for training agents to interact with web-based environments, including drawing apps and other dynamic pages.
  - *Data*: Raw challenge data including HTML, screenshots, DOM trees, Axtrees, videos, and recorded actions.
  - *URL*: https://github.com/iMeanAI/WebCanvas

- **VisualWebBench**
  - *Description*: A benchmark for evaluating visual web interaction tasks and multimodal LLM web understanding.
  - *Data*: Image and text data from websites for evaluating multimodal LLM web understanding and grounding.
  - *URL*: https://github.com/VisualWebBench

- **CRAB**
  - *Description*: Cross-environment benchmark for multimodal agents supporting Ubuntu and Android tasks.
  - *Data*: 120 tasks in CRAB Benchmark-v0 with multimodal observations (screenshots) and Python-based task definitions.
  - *URL*: https://crab.camel-ai.org/

- **GUI-World**
  - *Description*: Comprehensive GUI dataset with videos and queries for evaluating multimodal LLM-based agents.
  - *Data*: 12K+ videos, 100K queries with annotated keyframes, detailed captions, and diverse QA types in JSON/Parquet formats.
  - *URL*: https://gui-world.github.io/

- **GUICourse (GUIEnv)**
  - *Description*: Large-scale page-caption pairs for training vision-based GUI agents across web and mobile.
  - *Data*: 10M page-caption pairs and 0.7M region-text QA pairs in JSON/Parquet, covering OCR, grounding, and navigation.
  - *URL*: https://github.com/yiye3/GUICourse

- **GUICourse (GUIAct)**
  - *Description*: Single-step and multi-step GUI action instructions for web and Android scenarios.
  - *Data*: 67K single-step and 15K multi-step action instructions in JSON/Parquet.
  - *URL*: https://github.com/yiye3/GUICourse

- **GUICourse (GUIChat)**
  - *Description*: Single-turn QAs and multi-turn dialogues for GUI interactions with bounding box annotations.
  - *Data*: 44K single-turn QAs and 6K multi-turn dialogues with text-rich images in JSON/Parquet.
  - *URL*: https://github.com/yiye3/GUICourse

- **AutoUI**
  - *Description*: Leverages AITW to evaluate Auto-GUI, an LLM-based task automation system for Android.
  - *Data*: Utilizes AITW's 715,000 episodes and 30,000 unique instructions with screenshots and actions.
  - *URL*: https://github.com/cooelf/Auto-GUI

- **AndroidWorld**
  - *Description*: An environment for building and benchmarking autonomous computer control agents on Android.
  - *Data*: 116 diverse tasks across 20 real-world Android apps, with dynamic task initialization for millions of variants.
  - *URL*: https://github.com/google-research/android_world

- **RICOSCA**
  - *Description*: Synthetic one-step commands dataset derived from the Rico dataset for Android app interaction.
  - *Data*: 295,476 synthetic one-step commands for 177,962 objects across 25,677 Android screens.
  - *URL*: https://huggingface.co/datasets/rootsautomation/RICO-SCA

- **WebVoyager**
  - *Description*: A dataset for training agents to navigate and interact with web environments using pixel-based observations.
  - *Data*: Browser screen perceptions as pixels with mouse/keyboard actions, tested on 15 real-world websites.
  - *URL*: https://arxiv.org/abs/2401.13919

- **ScreenAgent**
  - *Description*: A dataset for training vision-language model-driven computer control agents.
  - *Data*: Screen interaction data under Apache-2.0 license for computer control tasks.
  - *URL*: https://github.com/niuzaisheng/ScreenAgent

- **OpenDFM/MoGUI**
  - *Description*: A mobile GUI interaction dataset for conversational agents with navigation graph structure.
  - *Data*: 2.6M+ GUI data from 250,000+ apps, each with screenshot and .xml metadata and navigation graphs.
  - *URL*: https://huggingface.co/datasets/OpenDFM/MoGUI

- **OpenDFM/MoCon**
  - *Description*: A mobile GUI interaction dataset, part of the MoGUI and MoCon projects.
  - *Data*: Released Mar 1, 2024; specific data details in associated technical report.
  - *URL*: https://huggingface.co/datasets/OpenDFM/MoCon

- **OpenDFM/MobA-MobBench**
  - *Description*: A benchmark dataset for evaluating mobile phone agents, supporting English and Chinese.
  - *Data*: 50 tasks across 11 columns with task IDs, descriptions (EN/ZH), involved applications, scoring milestones, and expert steps.
  - *URL*: https://huggingface.co/datasets/OpenDFM/MobA-MobBench

- **WebUI (biglab/webui-all)**
  - *Description*: Large dataset of rendered web pages with automatically extracted metadata, created by crawling the web to enhance visual UI understanding.
  - *Data*: 400,000 web UIs; HuggingFace version is a filtered subset; raw dataset on Google Drive.
  - *URL*: https://huggingface.co/datasets/biglab/webui-all

- **AGUVIS**
  - *Description*: A unified pure vision-based framework for autonomous GUI agents operating across web, desktop, and mobile platforms.
  - *Data*: Stage 1 (Grounding): 4.2M samples; Stage 2 (Planning/Reasoning): 1.3M GUI agent trajectories with reasoning annotations.
  - *URL*: https://github.com/xlang-ai/aguvis

---

## 2023

- **UEyes**
  - *Description*: Eye-tracking dataset for understanding visual saliency across various user interfaces.
  - *Data*: Eye-tracking data from 62 participants, 1,980 UI screenshots, with raw gaze logs, saliency maps, and scan paths.
  - *URL*: https://github.com/YueJiang-nj/UEyes-CHI2023

- **Android in the Wild (AITW)**
  - *Description*: Large-scale dataset for Android device control across a broad range of tasks and apps.
  - *Data*: 715,142 episodes, 30,378 unique instructions across 159 apps and 198+ websites, with 5.6M+ RGB screenshots and action sequences in TFRecord format.
  - *URL*: https://github.com/google-research/google-research/tree/master/android_in_the_wild

- **GUI Odyssey**
  - *Description*: A dataset for evaluating GUI agents across diverse multi-app tasks and environments.
  - *Data*: 7,735 episodes from 6 devices, covering 6 multi-app task types, 201 apps, and 1,400 unique app combinations.
  - *URL*: https://github.com/OpenGVLab/GUI-Odyssey

- **Mobile-Env**
  - *Description*: A dataset for training agents to interact with mobile apps in simulated environments.
  - *Data*: WikiHow task set with screenshots, view hierarchies, and touch/type token actions in ProtoBuf 3 format.
  - *URL*: https://github.com/X-LANCE/Mobile-Env

- **Mind2Web**
  - *Description*: A dataset for training agents to interact with web pages using natural language across diverse real-world websites.
  - *Data*: 2,350 tasks across 137 real-world websites in 31 domains, with HTML inputs and action sequences (Click, Type, Select).
  - *URL*: https://osu-nlp-group.github.io/Mind2Web/

- **WebArena**
  - *Description*: A dataset for training agents to perform long-horizon tasks on realistic web pages.
  - *Data*: 812 long-term web tasks from 241 templates, with natural language intents, HTML/DOM trees, screenshots, and keyboard/mouse actions.
  - *URL*: https://webarena.dev/

- **Synapse**
  - *Description*: A dataset for training agents to perform tasks across multiple web applications using CoT reasoning.
  - *Data*: 100,000 synthetic demonstrations across 21 domains, with Python programs, natural language plans, CoT reasoning, and HTML snippets.
  - *URL*: https://ltzheng.github.io/Synapse

- **ASSISTGUI**
  - *Description*: A dataset for evaluating GUI agents across widely-used productivity software.
  - *Data*: 100 tasks across 9 productivity software with necessary project files for task execution.
  - *URL*: https://showlab.github.io/assistgui/

---

## 2022

- **META-GUI**
  - *Description*: Benchmark for GUI-based task-oriented dialogue systems across six domains.
  - *Data*: 1,125 dialogues (4,684 turns) and 18,337 action prediction data points with screenshots, XML view hierarchies, and GUI actions.
  - *URL*: https://x-lance.github.io/META-GUI-Leaderboard/

- **UGIF**
  - *Description*: A dataset for understanding user interactions with graphical interfaces in multiple languages.
  - *Data*: 523 multilingual natural language instructions with UI screen-action sequences, supporting 8 languages, including XML view hierarchies.
  - *URL*: https://arxiv.org/abs/2211.07615

- **WebShop**
  - *Description*: Dataset for training autonomous agents in online shopping environments.
  - *Data*: 1.18M real-world products, 12,087 crowdsourced text instructions, and 1,600 human demonstrations in OpenAI Gym format.
  - *URL*: https://webshop-pnlp.github.io

---

## 2021

- **UIBert (AppSim & RefExp)**
  - *Description*: A dataset for understanding and generating UI descriptions built on the Rico corpus.
  - *Data*: Built on Rico's 72,000 UI data points, with AppSim (similar UI element pairs) and RefExp (reference expressions for UI elements) in TFRecords.
  - *URL*: https://github.com/google-research-datasets/uibert

- **AndroidEnv**
  - *Description*: A simulated environment for testing Android GUI agents with extensible task definitions.
  - *Data*: 100 example tasks with RGB pixel observations, (x,y) action spaces, and support for custom task extensions.
  - *URL*: https://github.com/deepmind/android_env

- **Screen Annotation**
  - *Description*: Dataset for generating concise language descriptions of mobile screens.
  - *Data*: 22,417 mobile screenshots with 15,743 training, 2,364 validation, and 4,310 test annotations in CSV format, derived from Rico.
  - *URL*: https://github.com/google-research-datasets/screen2words

- **MoTIF (Mobile app Tasks with Iterative Feedback)**
  - *Description*: A dataset for training agents to perform tasks on mobile apps with user feedback and feasibility annotations.
  - *Data*: 6,100+ free-form natural language commands across 125 Android apps, with action coordinates, screenshots, and feasibility annotations.
  - *URL*: https://vigilworkshop.github.io/static/papers-2021/26.pdf

---

## 2020

- **PixelHelp**
  - *Description*: Multi-step instructions for common tasks on Google Pixel phones.
  - *Data*: 187 multi-step instructions across 4 task categories (general, Gmail, Chrome, Photos) with human-annotated step-by-step actions.
  - *URL*: https://arxiv.org/abs/2005.03776

- **ANDROIDHOWTO**
  - *Description*: A dataset for training agents to follow step-by-step instructions on Android devices.
  - *Data*: 32,436 data points from 9,893 unique "How-to" instructions, with 190K action and 172K object segments in JSON/TFRecords.
  - *URL*: https://github.com/debymf/generating_android_howto

---

## 2018

- **RICO**
  - *Description*: A foundational dataset of unique Android app UIs, widely used for mobile GUI research.
  - *Data*: 72,000 Android app UI screenshots with view hierarchies and annotations.
  - *URL*: https://www.kaggle.com/datasets/onurgunes1993/rico-dataset

---

This Awesome List is a comprehensive resource for GUI agent datasets, covering mobile, desktop, and web environments. Contributions are welcome to keep it updated with the latest advancements in computer interaction datasets!
