<div align="center">

# ⚡ BISWADEEP (BiswadeepInfinity)

<a href="https://github.com/BiswadeepInfinity">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=System+Design+%26+ML+Research+Engineer;Graph+Neural+Networks+%26+Continuous-Time+AI;ANN%2C+CNN%2C+GNN+%26+Statistical+Forecasting;Python+%26+C+Systems+Specialist;Real-Time+Data+Pipelines+%26+Game+Tech+Origins" alt="Typing SVG" />
</a>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=BiswadeepInfinity&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/BiswadeepInfinity?label=Followers&style=flat-square&color=38bdf8" alt="Followers" />
  <img src="https://img.shields.io/github/stars/BiswadeepInfinity?label=Stars&style=flat-square&color=f59e0b" alt="Stars" />
</p>

[![GitHub](https://img.shields.io/badge/GitHub-BiswadeepInfinity-181717?style=for-the-badge&logo=github)](https://github.com/BiswadeepInfinity)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)

</div>

---

## 🧩 About Me

I am a **System Designer and Machine Learning Research Engineer** working at the intersection of deep learning theory, mathematical modeling, and low-latency systems architecture.

My technical foundation began in **Unreal Engine game development** programming in **C** and **Visual Scripting (Blueprints)**, where computational efficiency, cache coherence, and hardware resource boundaries determine viability. As I expanded into artificial intelligence and research, this systems background gave me a distinct edge: while conventional ML often treats hardware and memory as infinite resources, I architect models from a first-principles systems perspective.

I bridge mathematical AI foundations—spanning **Graph Neural Networks (GNNs), CNNs, ANNs, and statistical learning (ARIMA, ensemble methods, clustering)**—with low-level systems engineering in **Python** and **C** to build high-throughput, memory-bounded, production-ready machine learning solutions.

I also leverage collaborative design tools like **Figma and Miro** to map out system architectures, mathematical flows, and data lifecycles with cross-functional teams prior to implementation.

### Research & Engineering Focus
- **Graph Neural Networks & Temporal Modeling** — Formulating continuous-time state-space models (SSMs), closed-form complex rotation operators, and parallel associative prefix scans that eliminate redundant graph traversals.
- **Deep Learning Architectures** — Developing and tuning GNNs, CNNs, and ANNs for structured, spatial, and relational datasets.
- **Classical & Statistical ML** — Applying Linear/Logistic Regression, Random Forests, Decision Trees, KNN, K-Means Clustering, and ARIMA time-series forecasting.
- **Memory-Bounded Systems & Pathfinding** — Designing sortingless spatial search architectures (CVRS) and custom data structures that prevent algorithmic memory explosion.
- **Real-Time AI Telemetry Pipelines** — Building ultra-fast data ingestion pipelines feeding streaming datasets into planetary-scale AI models (GraphCast architectures).

---

## 🛠️ Technical Stack

### Primary Languages
- **Python** — Deep learning (PyTorch, PyG), scientific computing, statistical modeling, data pipelines
- **C** — Low-level memory management, high-performance algorithm implementation, systems design
- **Java** — Object-oriented systems, backend infrastructure, enterprise application architecture
- **JavaScript** — Full-stack web platforms, client-side dynamics, API routing
- **SQL** — Relational database modeling, query optimization, analytics pipelines
- **Unreal Engine Visual Scripting (Blueprints)** — Real-time event flows, interactive logic, simulation mechanics

### Machine Learning, Deep Learning & Mathematics
- **Deep Learning:** Graph Neural Networks (GNNs), Convolutional Neural Networks (CNNs), Artificial Neural Networks (ANNs), Continuous-Time SSMs
- **Classical Machine Learning:** Linear Regression, Logistic Regression, Decision Trees, Random Forests, K-Nearest Neighbors (KNN), Clustering (K-Means, Hierarchical)
- **Time-Series & Forecasting:** ARIMA, Multi-Harmonic Fourier Encodings, Autoregressive Dynamics
- **Frameworks & Libraries:** `PyTorch`, `PyTorch Geometric (PyG)`, `NumPy`, `SciPy`, `pandas`, `Scikit-Learn`

### Systems, Design & Collaboration
- **Supporting Languages:** `C++`, `TypeScript`
- **Design & Prototyping:** `Figma`, `Miro`, `Canva`, `System Architecture Diagramming`, `UI/UX Wireframing`
- **Infrastructure & Workflow:** Git, Linux / Windows, Docker, Agile / Sprint Planning, AI-assisted development (vibe coding & prompt engineering), Discord, Slack, Google Workspace, Microsoft 365.

---

## 🚀 Research & Featured Projects

### 🧠 [Time-Parameter for Graph Neural Networks (RT-GNN)](https://github.com/BiswadeepInfinity/Time-Parameter-for-GNN)
> *Research project resolving the training memory bottleneck in temporal graph neural networks.*
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/BiswadeepInfinity/Time-Parameter-for-GNN)

- **Closed-Form Continuous-Time Rotation**: Bypasses recursive neighborhood traversals via complex state operators $T_{\Delta t}(z) = z \cdot \exp((-\lambda + i\omega)\Delta t)$, maintaining the semigroup property $T(a) \circ T(b) = T(a+b)$.
- **Logarithmic Parallel Prefix Scans**: Replaces sequential Backpropagation Through Time (BPTT), cutting memory and time scaling from $O(K)$ down to $O(\log K)$ via associative prefix scans.
- **Benchmark Performance**: Outperformed recurrent baselines (TGN, DyRep) processing over **19,300+ edges/sec** on CPU while scoring **0.475+ Test MRR** on Stanford/TGB Wikipedia benchmarks.
- **Mathematical Invariant Verification**: Wrote an automated testing suite of **35 test gates** certifying causality, contractive norm decay, and autograd gradient flow.

---

### ⚡ Clustered Vertex Representative Search (CVRS)
> *Memory-bounded spatial pathfinding architecture inspired by sortingless shortest-path theory.*
[![Architecture](https://img.shields.io/badge/Research-Pathfinding_Architecture-blue?style=flat-square)](#)

- **Sortingless Search Paradigm**: Leveraged Duan et al.'s theoretical breakthroughs to eliminate priority-queue sorting overhead inherent to classical Dijkstra and A*.
- **Hierarchical Representative Clustering**: Implemented in C: clusters dense spatial topologies into representative nodes, preventing memory explosion and frame-time spikes in multi-agent game environments (Unreal Engine).

---

### ⛈️ [Weather Intelligence as a Service (WIaaS)](https://github.com/BiswadeepInfinity/-Weather-Intelligence-as-a-Service-WIaaS-)
> *High-performance data ingestion pipeline feeding streaming weather data into planetary AI models.*
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/BiswadeepInfinity/-Weather-Intelligence-as-a-Service-WIaaS-)

- **Predictive Risk Modeling**: Ingests real-time meteorological feeds to forecast power grid failures, crop hazards, and logistics risks using GraphCast deep learning architecture.
- **High-Throughput Streaming Ingestion**: Engineered an asynchronous data movement layer feeding global geospatial grids directly into hardware-accelerated model inference pipelines.

---

### 🍿 [Infinity Socials](https://github.com/BiswadeepInfinity/Infinity-Socials)
> *Full-stack pop-culture review, rating, and socialization web platform.*
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/BiswadeepInfinity/Infinity-Socials)

- **Collaborative UX & Systems Design**: Prototyped user journey flows, wireframes, and relational schemas in Figma and Miro prior to implementation.
- **Full-Stack Architecture**: Built a complete web application with authentication, session lifecycles, and relational database schema in SQL for user interaction and rating graphs.

---

## 📈 Activity & Contribution Visuals

<div align="center">

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

## 📊 Analytics & Coding Stats

<div align="center">

### ⚡ Activity Trend
<img src="https://github-readme-activity-graph.vercel.app/graph?username=BiswadeepInfinity&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Activity Graph" />

<br/>

### 🎯 Overview & Languages
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=BiswadeepInfinity&theme=tokyonight" width="49%" alt="Profile Details" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=BiswadeepInfinity&theme=tokyonight" width="49%" alt="Language Breakdown" />

<br/>

### 🔥 Streak & Repository Summary
<img src="https://github-readme-stats.vercel.app/api?username=BiswadeepInfinity&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="49%" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=BiswadeepInfinity&theme=tokyonight&hide_border=true" width="49%" alt="Streak Stats" />

</div>

---

<div align="center">
  <sub>Bridging mathematical machine learning research with low-latency systems engineering.</sub>
</div>
