---
permalink: /
title: "Hello there, I'm Promise!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate in the Computer Science Department at Cornell University (Cornell Tech), advised by [Prof. Angelique Taylor](https://www.angeliquemtaylor.com/) in the AirLab. My research is in **robotics, human-robot interaction (HRI), and embodied AI**: I build robots and multi-agent systems that detect their own failures, recover gracefully, and coordinate fairly with human teams in safety-critical settings such as healthcare.

Much of my work centers on **robot failure perception and recovery**. I built [REPAIR-Bench](https://github.com/promiseve), a benchmark of 214 human-robot interaction trials with synchronized multimodal signals (facial action units, head pose, speech, and post-interaction affect), where hierarchical recurrent modeling improved failure detection over single-session baselines (strict F1: 0.80 vs. 0.68). I also built the [RFM-HRI](https://github.com/promiseve) multimodal dataset of robot failure, user reaction, and recovery preferences (THRI 2026, accepted), and fine-tuned Mistral-7B with QLoRA for user-centered recovery prediction (Hit@5 = 0.76).

I also design **multi-agent reinforcement learning** methods that make robot teams coordinate efficiently and fairly. This includes [Fair-GNE](https://arxiv.org/pdf/2511.14135), a generalized Nash equilibrium-seeking framework using Lagrangian dual ascent for automatic penalty learning (JFI 0.89 vs. 0.33 over fixed-penalty baselines while maintaining 86% task success), and [FairSkillMARL](https://arxiv.org/pdf/2508.18708) with the **MARLHospital** simulator for evaluating fairness-efficiency trade-offs in multi-agent healthcare automation. My work spans real-world robot deployments, including crash-cart robots studied with 115 healthcare workers at Weill Cornell Medicine.

Before Cornell, I completed my M.Sc. in Computer Science at [Princeton University](https://www.cs.princeton.edu/), advised by [Prof. Jaime Fernández Fisac](https://ece.princeton.edu/people/jaime-fernandez-fisac), where I investigated emergent persuasiveness and safety failures in large language models (GPT-3/4). I also spent a summer as an AI Safety intern at [Siemens Technology](https://www.siemens.com/global/en.html), building explainable-AI frameworks (GNNExplainer on graph attention networks) and multimodal safety monitors for robotic warehouses.

**Research interests:** Robotics & Human-Robot Interaction, Embodied AI, Multimodal Perception, Robot Failure Detection & Recovery, Multi-Agent Reinforcement Learning, Vision-Language Models, AI Safety.

I am actively seeking **robotics research internships** for Summer 2027. Feel free to reach out.
