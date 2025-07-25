# Awesome CUA / GUI Agent Datasets for Computer and Phone Use

A curated list of datasets for training GUI agents—AI systems that automate interactions with graphical user interfaces on computers, phones, and browsers. These datasets support tasks like clicking, typing, and navigating visual elements, making them essential for researchers and developers advancing AI agent training and GUI automation. Sorted by year (most recent first), each entry includes the dataset name, a brief description, data summary, and a URL where available.

---

## 2025

- **Aria-UI/Aria-UI_Data**  
  - *Description*: A comprehensive collection of GUI grounding data covering web, mobile, and desktop interfaces, designed for versatile grounding instruction understanding and context-aware grounding.  
  - *Data*: Web Data (2.9M instructions, 173k images), Mobile Data (1.1M instructions, 104k images from AMEX), Desktop Data (150k instructions, 7.8k images from Ubuntu).  
  - *URL*: [https://huggingface.co/datasets/Aria-UI/Aria-UI_Data](https://huggingface.co/datasets/Aria-UI/Aria-UI_Data)

- **Multimodal-Mind2Web**  
  - *Description*: A multimodal version of Mind2Web, pairing HTML documents with corresponding website screenshots to support the development of general-purpose web agents.  
  - *Data*: 7,775 actions from 1,009 training tasks; 1,339 actions from 177 test tasks (same website), 1,019 actions from 142 test tasks (new website), 4,060 actions from 694 test tasks (new domain). Includes HTML and screenshot data.  
  - *URL*: https://huggingface.co/datasets/osunlp/Multimodal-Mind2Web

- **GUIMid**  
  - *Description*: A consolidated mid-training dataset designed to enhance the foundational agentic capabilities of Vision Language Models (VLMs) for Graphical User Interface (GUI) tasks, by leveraging data from adjacent, non-GUI domains.  
  - *Data*: 300,000 samples, combining MathInstruct (150k), CodeI/O (20k), Olympiad Math (50k), and Multi-modal Math (80k).  
  - *URL*: [https://github.com/hkust-nlp/GUIMid](https://github.com/hkust-nlp/GUIMid)  

- **STEVE (Windows OS dataset)**  
  - *Description*: A private Windows OS dataset for UI grounding, collected through a Windows virtual machine, OmniParser, screenshots, and accessibility tree data. It aims to train VLMs specialized in UI grounding.  
  - *Data*: 10,000 desktop images and 80,000 UI elements, augmented with publicly available AITW data.  
  - *URL*: [https://github.com/FanbinLu/STEVE](https://github.com/FanbinLu/STEVE)  

- **Aguvis Data Collection (xlangai/aguvis-stage1 & xlangai/aguvis-stage2)**  
  - *Description*: A large-scale cross-platform dataset of GUI agent trajectories featuring multimodal grounding and reasoning annotations, including inner monologue. Stage 1 focuses on computer/mobile grounding, while Stage 2 is for computer/mobile/desktop trajectory training.  
  - *Data*: The full dataset viewer is currently unavailable, but previews show image filenames and conversations with human instructions and GPT-generated `pyautogui` actions. Associated with arXiv:2412.04454.  
  - *URL*: [https://huggingface.co/datasets/xlangai/aguvis-stage1](https://huggingface.co/datasets/xlangai/aguvis-stage1), [https://huggingface.co/datasets/xlangai/aguvis-stage2](https://huggingface.co/datasets/xlangai/aguvis-stage2)  

- **OS-Genesis**  
  - *Description*: An interaction-driven pipeline that synthesizes high-quality, diverse GUI agent trajectory data without human supervision or predefined tasks, by using reverse task synthesis and a trajectory reward model.  
  - *Data*: Includes raw collected triples (`<s_pre, a, s_post>`), complete trajectory data on HuggingFace, screenshots, and texts with State-of-Mind (SoM) information. Contains both Mobile and Web data with specific Google Drive links for screenshots and JSON data.  
  - *URL*: [https://github.com/OS-Copilot/OS-Genesis](https://github.com/OS-Copilot/OS-Genesis)  

- **Mobile-R1 (PG23/Mobile-R1)**  
  - *Description*: A high-quality dataset for training and utilizing VLM-based mobile agents, specifically focusing on Chinese mobile applications.  
  - *Data*: 1,007 trajectories across 28 different mobile applications, with 3,924 total steps. Includes screenshots and `data.jsonl` with full interaction trajectories, action history, instructions, system prompts, image dimensions, and detailed action parameters.  
  - *URL*: [https://mobile-r1.github.io/Mobile-R1/](https://mobile-r1.github.io/Mobile-R1/)  

- **ShowUI_desktop**  
  - *Description*: A vision–language–action dataset designed to improve desktop GUI element grounding across diverse applications, featuring rich bounding-box and keypoint annotations.  
  - *Data*: ~7,500 desktop screenshots spanning 15 applications; 8,000 element annotations with appearance, spatial-relation, and intent queries; relative bounding boxes and action keypoints for each element.  
  - *URL*: [https://huggingface.co/datasets/Voxel51/ShowUI_desktop](https://huggingface.co/datasets/Voxel51/ShowUI_desktop)  

- **GUI-Robust**  
  - *Description*: A comprehensive dataset explicitly crafted to evaluate GUI agent performance under seven real-world anomaly conditions (e.g., occlusion, dynamic content changes). It employs a semi-automated collection paradigm combining RPA-tool recordings and MLLM-assisted annotation.  
  - *Data*: 10,000+ action sequences with seven anomaly types, task descriptions, stepwise instructions, screenshots, and grounding metadata; generated via a human-in-the-loop pipeline that reduces annotation time by 19×.  
  - *URL*: [https://github.com/chessbean1/GUI-Robust](https://github.com/chessbean1/GUI-Robust)  

- **VideoGUI**  
  - *Description*: A multi-modal benchmark sourced from professional instructional videos, focusing on visually intensive, multi-step software tasks. It evaluates agents across hierarchical levels—high-level planning, middle-level planning, and atomic action execution.  
  - *Data*: 86 complex tasks (avg. 22.7 actions each), 463 subtasks, 2.7K manually annotated actions with precise element locations, covering 11 software applications such as Adobe Photoshop and Stable Diffusion WebUI; includes video-derived screenshots and action transcripts.  
  - *URL*: [https://github.com/showlab/videogui](https://github.com/showlab/videogui)  

- **Mind2Web 2**  
  - *Description*: Mind2Web 2, a benchmark of 130 realistic, high-quality, and long-horizon tasks that require real-time web browsing and extensive information synthesis, constructed with over 1000 hours of human labor. To address the challenge of evaluating time-varying and complex answers, we propose a novel Agent-as-a-Judge framework
  - *Data*: Mind2Web 2, a benchmark of 130 realistic, high-quality, and long-horizon tasks.
  - *URL*: https://huggingface.co/datasets/osunlp/Mind2Web-2

- **Online-Mind2Web**  
  - *Description*: An online version of Mind2Web, featuring 300 high-quality tasks from 136 popular websites across domains like clothing, food, housing, and transportation, designed to evaluate web agent performance in real-world online environments.  
  - *Data*: 300 tasks from 136 websites, with fields including task_id (str), website (str), task_description (str), and reference_length (int).  
  - *URL*: https://github.com/OSU-NLP-Group/Online-Mind2Web

- **LearnGUI**  
  - *Description*: A dataset for studying illustration-based learning in mobile GUI agents, enhancing performance in unseen scenarios.  
  - *Data*: 2,252 offline and 101 online tasks across 73 apps, with high-quality human demonstrations, screenshots, and action sequences.  
  - *URL*: [https://huggingface.co/datasets/lgy0404/LearnGUI](https://huggingface.co/datasets/lgy0404/LearnGUI)

- **AndroidInteraction**  
  - *Description*: Focuses on user interaction needs and notifications in phone UI automation, enabling agent-initiated interactions.  
  - *Data*: Over 750 demonstrations across 250+ apps, including action-observation pairs with screenshots and accessibility metadata.  
  - *URL*: [https://arxiv.org/abs/2503.19537](https://arxiv.org/abs/2503.19537)

- **WorldGUI**  
  - *Description*: An interactive benchmark for desktop GUI automation, supporting tasks across multiple applications from any starting point.  
  - *Data*: 611 tasks across 10 desktop and web apps, with user queries, instructional videos, and project files.  
  - *URL*: [https://github.com/showlab/WorldGUI](https://github.com/showlab/WorldGUI)

- **DeskVision**  
  - *Description*: Large-scale desktop region captioning dataset for advanced GUI agents, improving visual element understanding.  
  - *Data*: Large-scale desktop GUI dataset with rich annotations for diverse UI systems and elements, using automated captioning.  
  - *URL*: [https://arxiv.org/abs/2503.11170](https://arxiv.org/abs/2503.11170)

- **GUI-Lasagne**  
  - *Description*: Multi-level, large-scale dataset for training agents like SpiritSight, focusing on GUI understanding and grounding.  
  - *Data*: 5.73M samples, 2.24M screenshots, 57.8M elements, with a 3-tier structure for image-text alignment and navigation.  
  - *URL*: [https://arxiv.org/abs/2503.03196](https://arxiv.org/abs/2503.03196)

- **TongUI / GUI-Net**  
  - *Description*: Builds generalized GUI agents by learning from multimodal web tutorials across multiple OS.  
  - *Data*: 143K (or 1M) trajectory data points across 5 OS and 200+ apps, with multimodal web instructions, text, and screenshots.  
  - *URL*: [https://tongui-agent.github.io/](https://tongui-agent.github.io/)

- **ScreenSpot-Pro**  
  - *Description*: Benchmark for GUI grounding in high-resolution professional environments, ideal for multimodal LLMs.  
  - *Data*: 1,581 task data points across 23 industries, with high-resolution full-screen images, natural language instructions, and bounding box annotations.  
  - *URL*: [https://huggingface.co/datasets/Voxel51/ScreenSpot-Pro](https://huggingface.co/datasets/Voxel51/ScreenSpot-Pro)

- **WebGames**  
  - *Description*: A dataset for training agents to play web-based games, focusing on interactive GUI tasks.  
  - *Data*: Over 50 unique interactive challenges in JSONL format, with 160px × 210px environments and text-based goals.  
  - *URL*: [https://github.com/convergence-ai/webgames](https://github.com/convergence-ai/webgames)

- **Explorer**  
  - *Description*: The largest-scale web trajectory dataset to date, dynamically exploring web pages to create contextually relevant tasks.  
  - *Data*: 94K successful web trajectories, 49K unique URLs, and 720K screenshots, generated by a multi-agent LLM pipeline.  
  - *URL*: [https://arxiv.org/abs/2502.11357](https://arxiv.org/abs/2502.11357)

- **InSTA**  
  - *Description*: An Internet-scale dataset for training GUI-based web agents, generated entirely through an automated LLM pipeline without human annotations.  
  - *Data*: Covers 150k diverse websites sourced from Common Crawl and includes rich web navigation tasks, trajectories in Playwright API calls, and evaluations using LLM-based judges.  
  - *URL*: [https://huggingface.co/datasets/data-for-agents/insta-150k-v3](https://huggingface.co/datasets/data-for-agents/insta-150k-v3)

- **GUIRoboTron-Speech**  
  - *Description*: The first end-to-end autonomous GUI agent that directly accepts speech instructions and on-device screenshots to predict actions. It generates high-quality speech instructions by converting existing text instructions using a random timbre text-to-speech (TTS) model.  
  - *Data*: Not explicitly summarized in the snippet, but the paper states "Our code and datasets are available at this https URL."  
  - *URL*: [https://arxiv.org/abs/2506.11127](https://arxiv.org/abs/2506.11127)

- **VideoCAD**  
  - *Description*: A large-scale synthetic dataset for learning UI interactions and 3D reasoning from CAD software. It consists of annotated video recordings of CAD operations.  
  - *Data*: Over 41K annotated video recordings of CAD operations, offering significantly higher complexity in UI interaction learning for real-world engineering tasks (up to 20x longer time horizon than other datasets).  
  - *URL*: [https://arxiv.org/html/2505.24838v1](https://arxiv.org/html/2505.24838v1)

- **HM-SYNC**  
  - *Description*: A comprehensive multimodal dataset capturing human interactions with advanced manufacturing machinery (WAAM machine). It focuses on human-machine interaction (HMI) in an industrial setting.  
  - *Data*: Approximately 3.87 hours of segmented interaction sequences (209,230 frames from each camera perspective) collected over 6 months, including 1228 unique interactions. Each frame contains a depth image, 32 skeleton joint coordinates in 3D, action labels (15 fundamental, 2 general human actions), interaction location labels (8 high-contact points), user IDs, camera view labels, action numbers, and timestamps. Data is in PNG (depth images) and array (3D joint data) formats.  
  - *URL*: [https://asmedigitalcollection.asme.org/mechanicaldesign/article/147/4/044504/1212303/HM-SYNC-A-Multimodal-Dataset-of-Human-Interactions](https://asmedigitalcollection.asme.org/mechanicaldesign/article/147/4/044504/1212303/HM-SYNC-A-Multimodal-Dataset-of-Human-Interactions)

- **AutomotiveUI-Bench-4K**  
  - *Description*: An open-source dataset for understanding and interacting with automotive infotainment systems, enabling seamless adaptation across different UI designs. It serves as a validation benchmark for automotive UI.  
  - *Data*: 998 images with 4,208 annotations focusing on interaction with in-vehicle infotainment (IVI) systems. Image sources are primarily photographs of IVI displays (due to screenshot limitations) and some direct screenshots (e.g., Android Auto). Annotation classes include "Test Action" (bounding box + imperative command) and "Expected Result" (bounding box + expected outcome + Pass/Fail status). Covers 15 automotive brands/OEMs (2018-2025 models). IVI UI in German and English, annotations in English.  
  - *URL*: [https://paperswithcode.com/dataset/automotiveui-bench-4k](https://paperswithcode.com/dataset/automotiveui-bench-4k)


---

## 2024


- **Mind2Web-Live**  
  - *Description*: This dataset focuses on dynamic evaluation using "key nodes," which represent critical intermediate states in web tasks.  
  - *Data*: 542 tasks with 4,550 detailed annotation steps, annotated by human experts.  
  - *URL*: [https://huggingface.co/datasets/iMeanAI/Mind2Web-Live](https://huggingface.co/datasets/iMeanAI/Mind2Web-Live)

- **WebVLN**  
  - *Description*: This dataset expands on web GUI tasks by combining navigation with question-answering. It provides agents with text-based queries that guide them to locate relevant web pages and extract information.  
  - *Data*: 8,990 navigation paths and 14,825 QA pairs, leveraging both HTML and visual content from websites.  
  - *URL*: [https://drive.google.com/drive/folders/1Gzm44P5QBxvBYUU4BiYW-WlxbiB5M19K?usp=sharing](https://drive.google.com/drive/folders/1Gzm44P5QBxvBYUU4BiYW-WlxbiB5M19K?usp=sharing)

- **WebLINX**  
  - *Description*: This dataset focuses on conversational GUI agents, particularly emphasizing real-world web navigation through multi-turn dialogue.  
  - *Data*: Over 2,300 expert demonstrations with over 100,000 interactions across 155 real-world websites, including DOM trees and screenshots.  
  - *URL*: [https://huggingface.co/datasets/McGill-NLP/WebLINX](https://huggingface.co/datasets/McGill-NLP/WebLINX)

- **AgentTrek**  
  - *Description*: This dataset synthesizes high-quality trajectory data by leveraging web tutorials.  
  - *Data*: 4,902 trajectories with task metadata, step-by-step instructions, action sequences, visual observations, and reproducible native traces.  
  - *URL*: [https://agenttrek.github.io/](https://agenttrek.github.io/)

- **MultiUI**  
  - *Description*: A large-scale dataset designed to enhance GUI agents’ text-rich visual understanding. It utilizes structured accessibility trees to generate high-quality multimodal instructions.  
  - *Data*: 7.3 million multimodal instruction samples collected from 1 million websites, covering key web UI tasks such as element grounding, action prediction, and interaction modeling.  
  - *URL*: [https://huggingface.co/datasets/neulab/MultiUI](https://huggingface.co/datasets/neulab/MultiUI)

- **ScreenAI**  
  - *Description*: Extends the scope of data collection to include both mobile and desktop interfaces, covering tasks such as screen annotation, question-answering, and navigation.  
  - *Data*: Hundreds of millions of annotated samples.  
  - *URL*: [https://github.com/google-research-datasets/screen_qa](https://github.com/google-research-datasets/screen_qa)

- **VisualAgentBench**  
  - *Description*: A groundbreaking cross-platform benchmark designed to assess GUI agents in both mobile and web settings, emphasizing interaction-focused tasks.  
  - *Data*: Not explicitly summarized in the survey, but uses environments like Android Virtual Device and WebArena-Lite.  
  - *URL*: [https://github.com/THUDM/VisualAgentBench](https://github.com/THUDM/VisualAgentBench)

- **VGA**  
  - *Description*: A Vision Question Answering (VQA) dataset designed to minimize "hallucinations" in VLMs for GUI understanding by balancing attention between image and text inputs. It aims to enhance the model's accuracy in extracting information from images and aligning with human intent.  
  - *Data*: 63.8k high-quality VQA examples, developed using a "Referent Method," focusing on responses tied to visual content. Based on the Rico dataset.  
  - *URL*: [https://github.com/Linziyang1999/VGA-visual-GUI-assistant](https://github.com/Linziyang1999/VGA-visual-GUI-assistant)

- **GUI-Robust**  
  - *Description*: A comprehensive dataset explicitly crafted to evaluate GUI agent performance under seven real-world anomaly conditions (e.g., occlusion, dynamic content changes). It employs a semi-automated collection paradigm combining RPA-tool recordings and MLLM-assisted annotation.  
  - *Data*: 10,000+ action sequences with seven anomaly types, task descriptions, stepwise instructions, screenshots, and grounding metadata; generated via a human-in-the-loop pipeline that reduces annotation time by 19×.  
  - *URL*: [https://github.com/chessbean1/GUI-Robust](https://github.com/chessbean1/GUI-Robust)  

- **VideoGUI**  
  - *Description*: A multi-modal benchmark sourced from professional instructional videos, focusing on visually intensive, multi-step software tasks. It evaluates agents across hierarchical levels—high-level planning, middle-level planning, and atomic action execution.  
  - *Data*: 86 complex tasks (avg. 22.7 actions each), 463 subtasks, 2.7K manually annotated actions with precise element locations, covering 11 software applications such as Adobe Photoshop and Stable Diffusion WebUI; includes video-derived screenshots and action transcripts.  
  - *URL*: [https://github.com/showlab/videogui](https://github.com/showlab/videogui)  

- **MobileViews**  
  - *Description*: Large-scale mobile GUI dataset with over 600,000 screenshot-view hierarchy pairs from 20,000+ Android apps.  
  - *Data*: 600,000+ screenshot-view hierarchy pairs, including .jpg screenshots, .json/.xml view hierarchies, and action logs in .zip/.parquet formats.  
  - *URL*: [https://huggingface.co/datasets/mllmTeam/MobileViews](https://huggingface.co/datasets/mllmTeam/MobileViews)

- **AMEX (Android Multi-annotation EXpo)**  
  - *Description*: Over 104,000 high-resolution screenshots from 110 popular mobile apps with detailed annotations.  
  - *Data*: 104,000+ high-resolution screenshots, 711,000 element-level functions, and 3,000 unique instructions with multi-step GUI action sequences.  
  - *URL*: [https://huggingface.co/datasets/Yuxiang007/AMEX](https://huggingface.co/datasets/Yuxiang007/AMEX)

- **AndroidControl**  
  - *Description*: 15,283 demonstrations of daily tasks across 833 Android apps, exploring data scale effects.  
  - *Data*: 15,283 task demonstrations with 14,548 unique tasks, including high/low-level instructions, screenshots, and accessibility trees in TFRecords.  
  - *URL*: [https://huggingface.co/datasets/HarrytheOrange/parsed_AndroidControl](https://huggingface.co/datasets/HarrytheOrange/parsed_AndroidControl)

- **B-MoCA**  
  - *Description*: Benchmark for evaluating mobile control agents across diverse device configurations.  
  - *Data*: 131 daily tasks and 60 real-world tasks across varied device configurations, with interactive environment data.  
  - *URL*: [https://github.com/gimme1dollar/b-moca](https://github.com/gimme1dollar/b-moca)

- **MobileAgentBench**  
  - *Description*: User-friendly benchmark with 100 tasks across 10 open-source apps for testing mobile LLM agents.  
  - *Data*: 100 tasks across 10 open-source Android apps, categorized by difficulty, with real-device execution support.  
  - *URL*: [https://MobileAgentBench.github.io](https://MobileAgentBench.github.io)

- **Mobile3M**  
  - *Description*: A dataset for mobile app understanding with 3 million examples for training GUI agents.  
  - *Data*: 3M UI pages and real-world transitions from 49 popular Chinese apps, with XML documents and directed graph structures in Parquet format.  
  - *URL*: [https://huggingface.co/datasets/xwk123/Mobile3M](https://huggingface.co/datasets/xwk123/Mobile3M)

- **OmniACT**  
  - *Description*: Dataset for multimodal generalist agents performing tasks on desktop and web interfaces.  
  - *Data*: Over 9,800 image-instruction pairs, with natural language tasks and PyAutoGUI-executable commands.  
  - *URL*: [https://arxiv.org/abs/2402.17553](https://arxiv.org/abs/2402.17553)

- **VisualWebArena**  
  - *Description*: A dataset for training agents to interact with web interfaces using visual inputs.  
  - *Data*: Built on WebArena, includes image-based tasks with executable evaluations, focusing on multimodal web interactions.  
  - *URL*: [https://github.com/web-arena-x/visualwebarena](https://github.com/web-arena-x/visualwebarena)

- **WebCanvas**  
  - *Description*: A dataset for training agents to interact with web-based creative tools like drawing apps.  
  - *Data*: Raw challenge data including HTML, screenshots, DOM trees, Axtrees, videos, and recorded actions for online web environments.  
  - *URL*: [https://github.com/iMeanAI/WebCanvas](https://github.com/iMeanAI/WebCanvas)

- **VisualWebBench**  
  - *Description*: A benchmark for evaluating visual web interaction tasks.  
  - *Data*: Image and text data from websites, designed for evaluating multimodal LLM web understanding and grounding.  
  - *URL*: [https://github.com/VisualWebBench](https://github.com/VisualWebBench)

- **CRAB**  
  - *Description*: Cross-environment benchmark for multimodal agents, supporting Ubuntu and Android tasks.  
  - *Data*: 120 tasks in CRAB Benchmark-v0, with multimodal observations (screenshots) and Python-based task definitions/evaluations.  
  - *URL*: [https://crab.camel-ai.org/](https://crab.camel-ai.org/)

- **GUI-World**  
  - *Description*: Comprehensive GUI dataset with over 12K videos and 100K queries for evaluating multimodal LLM-based agents.  
  - *Data*: 12K+ videos, 100K queries with annotated keyframes, detailed captions, and diverse QA types in JSON/Parquet formats.  
  - *URL*: [https://gui-world.github.io/](https://gui-world.github.io/)

- **GUICourse (GUIEnv)**  
  - *Description*: Features 10M page-caption pairs for training vision-based GUI agents across web and mobile.  
  - *Data*: 10M page-caption pairs and 0.7M region-text QA pairs in JSON/Parquet, covering OCR, grounding, and navigation.  
  - *URL*: [https://github.com/yiye3/GUICourse](https://github.com/yiye3/GUICourse)

- **GUICourse (GUIAct)**  
  - *Description*: Contains 67K single-step and 15K multi-step instructions for GUI actions.  
  - *Data*: 67K single-step and 15K multi-step action instructions in JSON/Parquet, spanning web and Android scenarios.  
  - *URL*: [https://github.com/yiye3/GUICourse](https://github.com/yiye3/GUICourse)

- **GUICourse (GUIChat)**  
  - *Description*: Offers 44K single-turn QAs and 6K multi-turn dialogues for GUI interactions.  
  - *Data*: 44K single-turn QAs and 6K multi-turn dialogues with text-rich images and bounding box annotations in JSON/Parquet.  
  - *URL*: [https://github.com/yiye3/GUICourse](https://github.com/yiye3/GUICourse)

- **AutoUI**  
  - *Description*: Leverages AITW to evaluate Auto-GUI, an LLM-based task automation system for Android.  
  - *Data*: Utilizes AITW’s 715,000 episodes and 30,000 unique instructions with natural language instructions, screenshots, and actions.  
  - *URL*: [https://github.com/cooelf/Auto-GUI](https://github.com/cooelf/Auto-GUI)

- **AndroidWorld**  
  - *Description*: An environment for building and benchmarking autonomous computer control agents.  
  - *Data*: 116 diverse tasks across 20 real-world Android apps, with dynamic task initialization for millions of variants.  
  - *URL*: https://github.com/google-research/android_world

- **RICOSCA**  
  - *Description*: A dataset for Android app security analysis.  
  - *Data*: 295,476 synthetic one-step commands for 177,962 objects across 25,677 Android screens, derived from Rico dataset.  
  - *URL*: https://huggingface.co/datasets/rootsautomation/RICO-SCA

- **WebVoyager**  
  - *Description*: A dataset for training agents to navigate and interact with web environments.  
  - *Data*: Browser screen perceptions as pixels, with mouse/keyboard actions, tested on real-world websites like Amazon and GitHub.  
  - *URL*: [https://arxiv.org/abs/2401.13919](https://arxiv.org/abs/2401.13919)

- **ScreenAgent**  
  - *Description*: A dataset for training agents to interact with screen-based interfaces.  
  - *Data*: Details not fully specified, but includes data for vision-language model-driven computer control under Apache-2.0 license.  
  - *URL*: [https://github.com/niuzaisheng/ScreenAgent](https://github.com/niuzaisheng/ScreenAgent)

- **OpenDFM/MoGUI**  
  - *Description*: A dataset for mobile GUI interaction, forming part of the MoGUI and MoCon projects. It aims to provide data for conversational agents on mobile GUIs.  
  - *Data*: "MoGUI😈 data" released Feb 29, 2024. Specific data summary refers to an associated technical report.  
  - *URL*: [https://huggingface.co/datasets/OpenDFM/MoGUI](https://huggingface.co/datasets/OpenDFM/MoGUI)  

- **OpenDFM/MoCon**  
  - *Description*: A dataset for mobile GUI interaction, also part of the MoGUI and MoCon projects.  
  - *Data*: "MoCon🛡️ data" released Mar 1, 2024. Specific data summary refers to an associated technical report. Dataset viewer currently disabled.  
  - *URL*: [https://huggingface.co/datasets/OpenDFM/MoCon](https://huggingface.co/datasets/OpenDFM/MoCon)  

- **OpenDFM/MobA-MobBench**  
  - *Description*: A benchmark dataset designed for evaluating mobile phone agents, supporting both English and Chinese languages.  
  - *Data*: 50 tasks (rows) across 11 columns, including task IDs, types, descriptions (EN/ZH), involved applications, preparation steps, scoring milestones, and human expert steps. The dataset size is small (<1KB).  
  - *URL*: [https://huggingface.co/datasets/OpenDFM/MobA-MobBench](https://huggingface.co/datasets/OpenDFM/MobA-MobBench)  

- **WebUI (biglab/webui-all)**  
  - *Description*: A large dataset of rendered web pages associated with automatically extracted metadata, created by crawling the web to enhance visual UI understanding with web semantics.  
  - *Data*: Contains 400,000 web UIs. The Hugging Face version is a filtered subset of the original dataset. The raw dataset is available on Google Drive.  
  - *URL*: [https://huggingface.co/datasets/biglab/webui-all](https://huggingface.co/datasets/biglab/webui-all)  

---

## 2023

- **UEyes**  
  - *Description*: Eye-tracking dataset for understanding visual saliency across various user interfaces.  
  - *Data*: Eye-tracking data from 62 participants, 1,980 UI screenshots, with raw gaze logs (.csv), saliency maps (.png), and scan paths (.png).  
  - *URL*: [https://github.com/YueJiang-nj/UEyes-CHI2023](https://github.com/YueJiang-nj/UEyes-CHI2023)


- **Android in the Wild (AITW)**  
  - *Description*: Large-scale dataset with 715,142 episodes for Android device control across 30,378 unique instructions.  
  - *Data*: 715,142 episodes, 30,378 unique instructions across 159 apps and 198+ websites, with 5.6M+ RGB screenshots and action sequences in TFRecord format.  
  - *URL*: [https://github.com/google-research/google-research/tree/master/android_in_the_wild](https://github.com/google-research/google-research/tree/master/android_in_the_wild)


- **GUI Odyssey**  
  - *Description*: A dataset for evaluating GUI agents across diverse tasks and environments.  
  - *Data*: 7,735 episodes from 6 devices, covering 6 multi-app task types, 201 apps, and 1,400 unique app combinations.  
  - *URL*: [https://github.com/OpenGVLab/GUI-Odyssey](https://github.com/OpenGVLab/GUI-Odyssey)

- **Mobile-Env**  
  - *Description*: A dataset for training agents to interact with mobile apps in simulated environments.  
  - *Data*: WikiHow task set with screenshots, view hierarchies, and touch/type token actions in ProtoBuf 3 format.  
  - *URL*: [https://github.com/X-LANCE/Mobile-Env](https://github.com/X-LANCE/Mobile-Env)

- **Mind2Web**  
  - *Description*: A dataset for training agents to interact with web pages using natural language.  
  - *Data*: 2,350 tasks across 137 real-world websites in 31 domains, with HTML inputs and action sequences (Click, Type, Select).  
  - *URL*: [https://osu-nlp-group.github.io/Mind2Web/](https://osu-nlp-group.github.io/Mind2Web/)

- **WebArena**  
  - *Description*: A dataset for training agents to perform tasks on web pages.  
  - *Data*: 812 long-term web tasks from 241 templates, with natural language intents, HTML/DOM trees, screenshots, and keyboard/mouse actions.  
  - *URL*: [https://webarena.dev/](https://webarena.dev/)

- **Synapse**  
  - *Description*: A dataset for training agents to perform tasks across multiple applications.  
  - *Data*: 100,000 synthetic demonstrations across 21 domains, with Python programs, natural language plans, CoT reasoning, and HTML snippets.  
  - *URL*: [https://ltzheng.github.io/Synapse](https://ltzheng.github.io/Synapse)

- **ASSISTGUI**  
  - *Description*: A dataset for evaluating GUI agents in assistive technology contexts.  
  - *Data*: 100 tasks across 9 widely-used productivity software, with necessary project files for task execution.  
  - *URL*: [https://showlab.github.io/assistgui/](https://showlab.github.io/assistgui/)

---

## 2022

- **META-GUI**  
  - *Description*: Benchmark for GUI-based task-oriented dialogue systems with 1,125 dialogues across six domains.  
  - *Data*: 1,125 dialogues (4,684 turns) and 18,337 action prediction data points with screenshots, XML view hierarchies, and GUI actions.  
  - *URL*: [https://x-lance.github.io/META-GUI-Leaderboard/](https://x-lance.github.io/META-GUI-Leaderboard/)

- **UGIF**  
  - *Description*: A dataset for understanding user interactions with graphical interfaces.  
  - *Data*: 523 multilingual natural language instructions with UI screen-action sequences, supporting 8 languages, including XML view hierarchies.  
  - *URL*: https://arxiv.org/abs/2211.07615

- **WebShop**  
  - *Description*: Dataset for training autonomous agents in online shopping with 1.18 million real-world products.  
  - *Data*: 1.18M real-world products, 12,087 crowdsourced text instructions, and 1,600 human demonstrations in OpenAI Gym format.  
  - *URL*: [https://webshop-pnlp.github.io](https://webshop-pnlp.github.io)

---

## 2021

- **UIBert (AppSim & RefExp)**  
  - *Description*: A dataset for understanding and generating UI descriptions.  
  - *Data*: Built on Rico’s 72,000 UI data points, with AppSim (similar UI element pairs) and RefExp (reference expressions for UI elements) in TFRecords.  
  - *URL*: [https://github.com/google-research-datasets/uibert](https://github.com/google-research-datasets/uibert)

- **AndroidEnv**  
  - *Description*: A simulated environment for testing Android GUI agents.  
  - *Data*: 100 example tasks with RGB pixel observations, (x,y) action spaces, and support for custom task extensions.  
  - *URL*: [https://github.com/deepmind/android_env](https://github.com/deepmind/android_env)
    
- **Screen Annotation**  
  - *Description*: Dataset for generating concise language descriptions of mobile screens.  
  - *Data*: 22,417 mobile screenshots with 15,743 training, 2,364 validation, and 4,310 test annotations in CSV format, derived from Rico.  
  - *URL*: [https://github.com/google-research-datasets/screen2words](https://github.com/google-research-datasets/screen2words)

- **MoTIF (Mobile app Tasks with Iterative Feedback)**  
  - *Description*: A dataset for training agents to perform tasks on mobile apps with user feedback.  
  - *Data*: Over 6,100 free-form natural language commands across 125 Android apps, with action coordinates, screenshots, and feasibility annotations.  
  - *URL*: [https://vigilworkshop.github.io/static/papers-2021/26.pdf](https://vigilworkshop.github.io/static/papers-2021/26.pdf)

---

## 2020

- **PixelHelp**  
  - *Description*: Features 187 multi-step instructions for common tasks on Google Pixel phones.  
  - *Data*: 187 multi-step instructions across 4 task categories (general, Gmail, Chrome, Photos) with human-annotated step-by-step actions.  
  - *URL*: https://arxiv.org/abs/2005.03776
    
- **ANDROIDHOWTO**  
  - *Description*: A dataset for training agents to follow step-by-step instructions on Android devices.  
  - *Data*: 32,436 data points from 9,893 unique “How-to” instructions, with 190K action and 172K object segments in JSON/TFRecords.  
  - *URL*: [https://github.com/debymf/generating_android_howto](https://github.com/debymf/generating_android_howto)
    
---

## 2018

- **RICO**  
  - *Description*: Contains 72,000 unique Android app UIs, a foundational dataset for mobile GUI research.  
  - *Data*: 72,000 Android app UI screenshots with view hierarchies and annotations, widely used for mobile GUI studies.  
  - *URL*: [https://www.kaggle.com/datasets/onurgunes1993/rico-dataset](https://www.kaggle.com/datasets/onurgunes1993/rico-dataset)

---

This Awesome List is a comprehensive resource for GUI agent datasets, covering mobile, desktop, and web environments. Contributions are welcome to keep it updated with the latest advancements in computer interaction datasets!
