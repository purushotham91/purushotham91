<h1 align="center">Purushotham Sirasapalli</h1>

<p align="center">
  <strong>CS + Math @ University at Buffalo | Robotics & Systems Researcher</strong>
</p>

<p align="center">
  <em>Available May 2026 — open to new-grad SWE / Robotics / Perf-eng / HFT roles</em>
</p>

<p align="center">
  <a href="mailto:purusirasap@gmail.com">purusirasap@gmail.com</a> &nbsp;&middot;&nbsp;
  <a href="https://linkedin.com/in/puru-sirasapalli">LinkedIn</a> &nbsp;&middot;&nbsp;
  <a href="https://gitlab.com/puru_s">GitLab</a> &nbsp;&middot;&nbsp;
  <a href="https://github.com/purushotham91">GitHub</a>
</p>

---

### About

I'm an undergrad researcher building systems that push computation to the edge, from lightweight metagenomic classifiers running on phones to decentralized swarm robots localizing signal sources without a central coordinator. I care about making algorithms work under real hardware constraints.

---

### Research

<table>
<tr>
<td width="50%" valign="top">

**ADAMS Lab** | _Swarm Robotics_
<sub>Dec 2024 – Present</sub>

- Led development of a decentralized swarm system for signal source localization with **4 physical robots**, validated with **50 agents** in simulation
- Paper submitted to **IROS 2026**
- Designed distributed inference with Bayesian Optimization & Gaussian Processes
- Trained RL policy for aerial target tracking, achieving **5x improvement** over PID baselines at **10 m/s**

</td>
<td width="50%" valign="top">

**SCORE Lab** | _Metagenomics_
<sub>May 2024 – Present</sub>

- Built **[Coriolis-Lite](https://gitlab.com/SCoRe-Group/smarten/-/tree/master/coriolis-lite)** (primary author), a lightweight C++20 metagenomic classifier using FM-indexes via sdsl-lite for memory-efficient classification on mobile devices
- Designed external-memory caching subsystem for **[SKiM](https://gitlab.com/SCoRe-Group/SKiM)** (Bioinformatics 2025) — two-threadpool I/O + page-aligned layout, indexes full NCBI RefSeq (~65k genomes) in **~17 GB RAM**, runs on Jetson at **6x speedup** over mmap-based baseline
- Building **[SKiMet](https://gitlab.com/SCoRe-Group/smarten/-/tree/SKiMet/skimet)** (in development) — a C++23 distributed classifier with gRPC + Intel TBB pipeline, integrating SKiM's compressed index into a server/client architecture for resource-constrained robotics/embedded targets
- Benchmarked hashing & caching across **63M keys**, replacing hash-based index with minimal perfect hashing

</td>
</tr>
</table>

---

### Selected Work

- **[Coriolis-Lite](https://gitlab.com/SCoRe-Group/smarten/-/tree/master/coriolis-lite)** *(primary author)* — C++20 metagenomic classifier. sdsl-lite FM-Index, multi-threaded, NSF-supported. Targets mobile/edge devices.
- **Decentralized Signal-Source Localization for Swarms** — ROS2 + Python + PyTorch. Distributed GP surrogates with online updates across the swarm, robust under RF / LoRa / WiFi conditions. **4 physical TurtleBots, 50 agents in simulation.** IROS 2026 submission.
- **RL Aerial-Target Tracking** — PyTorch + ROS2 + Gazebo. End-to-end RL policy that beats PID baselines by **5×** at **10 m/s** target velocity.
- **SKiMet** *(in development)* — C++23 distributed metagenomic classifier on the SMARTEn framework. gRPC + Intel TBB pipeline, server/client split, AArch64 / Jetson targets.

---

### Skills

**Languages** — depth, not breadth

![C/C++](https://img.shields.io/badge/-C%2FC%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)

**Systems & Tooling**

![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/-CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![ROS2](https://img.shields.io/badge/-ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/-Gazebo-000000?style=flat-square&logo=gazebo&logoColor=white)

**ML / Scientific**

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit--learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

---

### Experience

- **Software Engineering Intern** @ Foundry Medical Technologies — Embedded control logic in C for a medical ventilator across adult and pediatric modes; safety-critical firmware on resource-constrained hardware.
- **Student Leader** @ 3 Pillar Catering, UB — Managed 10+ staff for events of up to **1,000 guests**.

---

<p align="center">
  <sub>B.S. Computer Science, Minor in Mathematics | University at Buffalo | GPA: 3.5 | Graduating May 2026</sub>
</p>
