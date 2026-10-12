<div align="center">

# @colornia

**Embedded Systems · Robotics · AI Agents · Engineering Evaluation**

[![GitHub](https://img.shields.io/badge/GitHub-colornia-181717?style=flat-square&logo=github)](https://github.com/colornia)

</div>

## About

I build systems at the boundary of embedded engineering and AI. My work focuses on turning open-ended ideas into testable systems: decomposing tasks, implementing reliable control or agent workflows, designing verification procedures, and tracing failure cases back to concrete causes.

I prefer work that ends with something measurable—a reproducible test, a reviewable data diff, or a system that can be evaluated under real constraints.

## Selected work

### [OpenSquad](https://github.com/colornia/opensquad) · An AI teammate inside Minecraft

A practical agent that joins a Minecraft server as another player and works through in-game chat. It can follow a player, gather and deliver resources, fight nearby hostile mobs, and keep user-controlled local memory. Open-ended chat can use an external model, while the basic mode works without an API key.

- Built explicit action flows, interruption handling, local memory, setup diagnostics, and bilingual documentation.
- Automated checks cover server entry, chat, collection, item delivery, and combat-related state transitions.
- Designed privacy boundaries so ordinary chat is not stored and saved memories can be deleted by the player.

### [VulnGym contributions](https://github.com/Tencent/VulnGym) · Agent evaluation and security data

Contributed to Tencent's real-world benchmark for white-box vulnerability-hunting agents.

- [PR #36](https://github.com/Tencent/VulnGym/pull/36): validated **408 entries / 2,889 annotation nodes** against upstream source, delivered **13 automatic fixes** and **26 human-review cases** with evidence links.
- [PR #62](https://github.com/Tencent/VulnGym/pull/62): separated configuration vulnerabilities into static-missing and active-bypass cases; delivered an idempotent generator and an independent verifier with **6 checks**.
- Focused on reproducible evidence chains instead of unreviewable model conclusions.

### CVRP neural solver · Learning-based combinatorial optimization

Built an Attention Encoder–Decoder with POMO multi-start rollout in PyTorch.

- Trained under a **4 GB GPU-memory constraint** with mixed precision and batch-size tuning.
- Reached **100% feasible solutions on 1,500 test instances**.
- Achieved roughly **200× the inference speed of OR-Tools** with an average cost gap of about **+1.15%**.

## Engineering stack

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32">
  <img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
  <img src="https://img.shields.io/badge/MATLAB-EF6C00?style=flat-square" alt="MATLAB">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/SolidWorks-D32F2F?style=flat-square" alt="SolidWorks">
  <img src="https://img.shields.io/badge/AI%20Coding%20Agents-5B5FC7?style=flat-square" alt="AI Coding Agents">
</p>

- **Embedded and control:** STM32, PWM, ADC/DMA, UART, watchdogs, PCB design, hardware-in-the-loop debugging.
- **AI and optimization:** PyTorch, attention models, reinforcement learning, agent workflows, evaluation design.
- **Mechanical engineering:** mechanism design, motion analysis, and SolidWorks.

## Direction

I am especially interested in engineering and research roles where AI must interact with code, hardware, or a measurable workflow—particularly robotics, embedded systems, intelligent machines, and agent evaluation.
