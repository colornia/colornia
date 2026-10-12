<div align="center">

# Ning Xu · 徐宁

**Mechanical Engineering M.S. @ Zhejiang University**

Embedded Systems · Robotics · AI Agents · Engineering Evaluation

[![Email](https://img.shields.io/badge/Email-22571093%40zju.edu.cn-1f6feb?style=flat-square&logo=gmail&logoColor=white)](mailto:22571093@zju.edu.cn)
[![GitHub](https://img.shields.io/badge/GitHub-colornia-181717?style=flat-square&logo=github)](https://github.com/colornia)

</div>

## About me

I build systems at the boundary of mechanics, firmware, and AI. My current work covers dielectric elastomer actuator (DEA) control for morphing structures, STM32 firmware reliability, AI-assisted engineering workflows, and evaluation data for software agents.

I prefer work that ends with something measurable: a bench waveform, a reproducible test, or a reviewable data diff.

我目前在浙江大学攻读机械工程硕士，关注介电弹性体驱动、变形结构、嵌入式控制，以及 AI Agent 在真实工程研发中的应用。

## Selected work

### [OpenSquad](https://github.com/colornia/opensquad) · An AI teammate inside Minecraft

A practical agent that joins a Minecraft server as another player and works through the in-game chat. It can follow a player, gather and deliver resources, fight nearby hostile mobs, and keep user-controlled local memory. Open-ended chat can use an external model, while the basic mode works without an API key.

- Built explicit action flows, interruption handling, local memory, setup diagnostics, and bilingual documentation.
- Automated checks cover server entry, chat, collection, item delivery, and combat-related state transitions.
- Designed privacy boundaries so ordinary chat is not stored and saved memories can be deleted by the player.

### [VulnGym contributions](https://github.com/Tencent/VulnGym) · Agent evaluation and security data

Contributed to Tencent's real-world benchmark for white-box vulnerability-hunting agents.

- [PR #36](https://github.com/Tencent/VulnGym/pull/36): validated **408 entries / 2,889 annotation nodes** against upstream source, delivered **13 automatic fixes** and **26 human-review cases** with evidence links.
- [PR #62](https://github.com/Tencent/VulnGym/pull/62): separated configuration vulnerabilities into static-missing and active-bypass cases; delivered an idempotent generator and an independent verifier with **6 checks**.
- Focused on reproducible evidence chains instead of unreviewable model conclusions.

### DEA high-voltage control for a morphing UAV flap · Research project

Developing an STM32L432KCUx-based control system for a dielectric elastomer actuator, including boost control, PWM modulation, dual-channel switching and discharge, ADC feedback, Bluetooth communication, and fail-safe logic.

- Measured **about 2,000 V at 20% duty** using a 100:1 high-voltage probe and oscilloscope.
- Set a **25% firmware soft limit**, a material-side safety red line near **2,640 V**, a **3 s communication timeout**, and an approximately **2 s watchdog reset**.
- Used a repository-level coding agent to connect source code, Keil configuration, build logs, change records, and bench observations into a review–patch–build–test loop.

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
- **Mechanical engineering:** mechanism design, motion analysis, morphing structures, SolidWorks.

## Direction

I am especially interested in engineering and research roles where AI must interact with code, hardware, or a measurable workflow—particularly robotics, embedded systems, intelligent machines, and agent evaluation.

## Contact

- Email: [22571093@zju.edu.cn](mailto:22571093@zju.edu.cn)
- GitHub: [@colornia](https://github.com/colornia)
