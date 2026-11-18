<div align="center">

# Biswadeep
### Systems & Neurotech Engineer

<!-- Clean Typing Tagline -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Systems+Engineering+%26+Neurotechnology;Python+(Primary)+%26+C+(Systems)+Specialist;C.+elegans+Synapse+Prediction;Flagship+Projects%3A+RT-GNN+%26+CVRS+Pathfinding" alt="Typing SVG" />

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=BiswadeepInfinity&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/BiswadeepInfinity?label=Followers&style=flat-square&color=38bdf8" alt="Followers" />
  <img src="https://img.shields.io/github/stars/BiswadeepInfinity?label=Stars&style=flat-square&color=f59e0b" alt="Stars" />
</p>

[![GitHub](https://img.shields.io/badge/GitHub-BiswadeepInfinity-181717?style=flat-square&logo=github)](https://github.com/BiswadeepInfinity)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:your.email@example.com)

</div>

---

## About Me

I work at the intersection of **low-level systems engineering** and **neurotechnology / computational neurocognition**. My core interest is understanding biological computation—how neural networks process, store, and route information.

While developing a continuous-time synapse prediction model for the *C. elegans* connectome, I hit a major bottleneck with existing temporal Graph Neural Networks: modeling continuous-time synaptic interactions and spike intervals caused severe memory explosion due to recursive graph traversals. To solve this, I created **RT-GNN (Time-Parameter for GNN)**, using continuous-time complex rotation operators to track synaptic state transitions in closed form with logarithmic scaling.

My systems work is also grounded in real-time simulation and game engines:
- **CVRS (Clustered Vertex Representative Search)** — a sortingless spatial pathfinding architecture implemented in C for Unreal Engine 5, eliminating priority-queue bottlenecks and bounding memory during multi-agent navigation.

I primarily program in **Python** (machine learning, PyTorch, PyG) and **C** (memory optimization, data structures), with working experience in **Java**, **JavaScript**, **SQL**, and **Unreal Engine Visual Scripting (Blueprints)**. Prior to implementation, I use **Figma** and **Miro** for system architecture mapping and collaborative workflows.

---

## Technical Stack

### Primary Languages
- **Python** *(Primary / Major)* — ML pipelines, PyTorch, PyG, continuous-time graph models, statistical modeling
- **C** *(Next Major / Systems)* — Low-level memory management, high-performance algorithm implementation (CVRS), spatial data structures
- **Java** — Object-oriented architecture, backend services
- **JavaScript** — Full-stack web applications, APIs
- **SQL** — Relational database modeling, query optimization
- **Unreal Engine Visual Scripting (Blueprints)** — Gameplay logic, event systems, simulation mechanics

### Machine Learning & Neurotech
- **Deep Learning & Neurotech:** Continuous-Time Graph Neural Networks (RT-GNN), Synapse Prediction (*C. elegans* Connectome), CNNs, ANNs, State-Space Models
- **Classical ML & Statistics:** Linear/Logistic Regression, Decision Trees, Random Forests, KNN, K-Means Clustering, Hierarchical Clustering
- **Time-Series & Forecasting:** ARIMA, Multi-Harmonic Encodings
- **Libraries:** PyTorch, PyTorch Geometric, Scikit-Learn, NumPy, SciPy, pandas, Matplotlib

### Supporting Tools & Workflow
- **Languages:** C++
- **Design & Prototyping:** Figma, Miro, Canva
- **Infrastructure:** Git, Linux, Windows, Docker, Agile / Scrum

---

## Co-Flagship Projects

### 🧠 1. [Time-Parameter for Graph Neural Networks (RT-GNN)](https://github.com/BiswadeepInfinity/Time-Parameter-for-GNN)
> *Continuous-time temporal graph model motivated by C. elegans synapse prediction.*  
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/BiswadeepInfinity/Time-Parameter-for-GNN)

- **Origin**: Designed to solve the continuous-time memory bottleneck when modeling synaptic connections in *C. elegans*.
- **Closed-Form Continuous-Time Rotation**: Bypasses recursive graph expansions through complex state operators $T_{\Delta t}(z) = z \cdot \exp((-\lambda + i\omega)\Delta t)$, maintaining the semigroup property $T(a) \circ T(b) = T(a+b)$.
- **Logarithmic Parallel Prefix Scans**: Replaces sequential Backpropagation Through Time (BPTT), cutting scaling from $O(K)$ down to $O(\log K)$ via associative prefix scans.
- **Benchmark Performance**: Scored **0.4755 ± 0.0215 Test MRR** on Stanford TGB Wikipedia benchmarks while processing over **19,300+ edges/sec** on CPU without label leakage.
- **Verification**: Backed by **35 automated test gates** certifying causality, contractive decay, and autograd gradient preservation.

---

### 🗺️ 2. Clustered Vertex Representative Search (CVRS)
> *High-performance spatial pathfinding architecture for multi-agent simulation.*  
[![Research](https://img.shields.io/badge/Research-Pathfinding_Architecture-blue?style=flat-square)](#)

- **Bypassing the Sorting Barrier**: Inspired by Ran Duan et al.'s research on sortingless shortest-path algorithms, CVRS eliminates the priority-queue (min-heap) sorting barrier that causes memory explosion in traditional Dijkstra and A* searches.
- **Hierarchical Representative Partitioning**: Partitions dense spatial graphs into clustered representative vertices, bounding the active search space to local sub-graphs and cutting per-agent memory footprint by over 70%.
- **High-Performance C Engine**: Implemented custom data structures in low-level **C** using Data-Oriented Design (DOD) to maximize cache locality under heavy multi-agent concurrency.
- **Unreal Engine 5 Integration**: Designed for direct integration with Unreal Engine navigation mesh runtimes without frame-rate drops.

---

## Supporting Projects

### ⛈️ [Weather Intelligence as a Service (WIaaS)](https://github.com/BiswadeepInfinity/-Weather-Intelligence-as-a-Service-WIaaS-)
> *Streaming data ingestion pipeline feeding weather feeds into deep learning models.*  
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/BiswadeepInfinity/-Weather-Intelligence-as-a-Service-WIaaS-)

- Streaming pipeline ingesting real-time global weather data into planetary AI models (GraphCast architecture) for risk forecasting.

---

### 🍿 [Infinity Socials](https://github.com/BiswadeepInfinity/Infinity-Socials)
> *Full-stack review, rating, and socialization web platform.*  
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/BiswadeepInfinity/Infinity-Socials)

- Designed user flows and wireframes in Figma and built full-stack web application with relational SQL database schema.

---

## Activity & Visuals

<div align="center">

### 🧱 Contribution Matrix
<picture>
  <img src="https://raw.githubusercontent.com/BiswadeepInfinity/BiswadeepInfinity/main/profile-3d-contrib/profile-gitblock.svg" alt="Gitblock Stats &amp; Neon Grid" width="100%">
</picture>

<br/><br/>

### 🎮 Contribution Activity Snake
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/BiswadeepInfinity/BiswadeepInfinity/main/dist/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/BiswadeepInfinity/BiswadeepInfinity/main/dist/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake" src="https://raw.githubusercontent.com/BiswadeepInfinity/BiswadeepInfinity/main/dist/github-contribution-grid-snake-dark.svg">
</picture>

<br/><br/>

### 🧊 3D Isometric Contribution Graph
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/BiswadeepInfinity/BiswadeepInfinity/main/profile-3d-contrib/profile-night-rainbow.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/BiswadeepInfinity/BiswadeepInfinity/main/profile-3d-contrib/profile-green-animate.svg">
  <img alt="3D Contribution Graph" src="https://raw.githubusercontent.com/BiswadeepInfinity/BiswadeepInfinity/main/profile-3d-contrib/profile-night-rainbow.svg">
</picture>

</div>

---

## Analytics & Coding Stats

<div align="center">

### ⚡ Activity Trend
<img src="https://github-readme-activity-graph.vercel.app/graph?username=BiswadeepInfinity&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Activity Graph" />

<br/>

### 🎯 Development Profile & Commit Cadence
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=BiswadeepInfinity&theme=tokyonight" width="49%" alt="Profile Details" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=BiswadeepInfinity&theme=tokyonight" width="49%" alt="Productive Time" />

<br/>

### 🔥 Streak Summary
<img src="https://github-readme-stats.vercel.app/api?username=BiswadeepInfinity&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="49%" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=BiswadeepInfinity&theme=tokyonight&hide_border=true" width="49%" alt="Streak Stats" />

</div>
