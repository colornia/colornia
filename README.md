<div align="center">

# @colornia

**Mechanical systems, embedded intelligence, and AI agents.**

I build testable systems that connect model reasoning with code, simulation, and real engineering constraints.

[![GitHub](https://img.shields.io/badge/GitHub-colornia-181717?style=flat-square&logo=github)](https://github.com/colornia)

</div>

---

## About

I work across mechanical engineering, embedded systems, and AI. I am interested in problems where an intelligent system must do more than produce a plausible answer: it must understand constraints, take actions, recover from failure, and leave behind evidence that can be checked.

My preferred workflow is simple: decompose the problem, build the smallest testable system, verify it under real constraints, and trace failure cases back to concrete causes.

## What I Build

```text
Intelligent Machines
├── Mechanism and motion analysis
├── Embedded control and sensing
└── Hardware-oriented verification

AI Agent Systems
├── Task planning and tool execution
├── State, memory, and interruption handling
└── Human-agent interaction in open environments

Engineering Evaluation
├── Reproducible test cases and evidence chains
├── Automated verification with human-review boundaries
└── Failure-case analysis under explicit constraints
```

## Featured Projects

### [OpenSquad](https://github.com/colornia/opensquad) · An AI teammate inside Minecraft

OpenSquad turns an AI agent into a teammate that joins a Minecraft server as another player and works through in-game chat. It can follow a player, gather and deliver resources, fight nearby hostile mobs, and maintain user-controlled local memory. Open-ended chat can use an external model, while the basic mode works without an API key.

The project is organized around explicit action flows rather than unrestricted text generation. It includes interruption handling, setup diagnostics, bilingual documentation, and automated checks for server entry, chat, collection, item delivery, and combat-related state transitions. Privacy boundaries are part of the design: ordinary chat is not stored, and saved memories can be deleted by the player.

### [VulnGym Contributions](https://github.com/Tencent/VulnGym) · Evaluation data for security agents

Contributions to Tencent's real-world benchmark for white-box vulnerability-hunting agents, with an emphasis on verifiable data rather than unreviewable model conclusions.

- [PR #36](https://github.com/Tencent/VulnGym/pull/36) validated **408 entries / 2,889 annotation nodes** against upstream source, producing **13 automatic fixes** and **26 human-review cases** with evidence links.
- [PR #62](https://github.com/Tencent/VulnGym/pull/62) separated configuration vulnerabilities into static-missing and active-bypass cases, with an idempotent generator and an independent verifier covering **6 checks**.

Together, these contributions reflect the evaluation workflow I care about: define the task precisely, preserve the evidence chain, automate what can be checked, and expose uncertain cases for review.

## More Projects

| Project | Focus | Result |
| --- | --- | --- |
| **CVRP Neural Solver** | Attention Encoder–Decoder with POMO multi-start rollout in PyTorch | **100% feasible solutions** on 1,500 test instances; about **200× OR-Tools inference speed** with an average cost gap of approximately **+1.15%** |
| **Embedded and Robotic Systems** | STM32/Arduino control, sensing, communication, mechanism design, and hardware-in-the-loop debugging | Engineering practice centered on measurable behavior, fault handling, and iterative verification |

## Current Focus

- Extending OpenSquad from individual task execution toward clearer role separation and multi-agent coordination.
- Exploring agent workflows that connect language-model reasoning with code, simulation, logs, and physical constraints.
- Designing engineering evaluation tasks with reproducible inputs, automated checks, and explicit failure-case taxonomies.
- Building systems whose behavior can be inspected and improved, rather than judged only by the fluency of their output.

## Tech Stack

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
</p>

**Embedded and control:** STM32, PWM, ADC/DMA, UART, watchdogs, PCB design, and hardware-in-the-loop debugging  
**AI and optimization:** PyTorch, attention models, reinforcement learning, agent workflows, and evaluation design  
**Mechanical engineering:** mechanism design, motion analysis, and SolidWorks

---

<div align="center">

**Build systems that can be tested. Make failures explainable.**

<sub>Intelligent Machines · AI Agents · Engineering Evaluation</sub>

</div>
