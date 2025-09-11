# 📘 Awesome Safe Reinforcement Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources on **Safe Reinforcement Learning (Safe RL)** – including papers, code, benchmarks, tutorials, and articles.  
Safe RL focuses on ensuring safety during training and deployment, by balancing reward optimization with constraints like risk, safety, or robustness.  

---

## 📑 Table of Contents
- [Introduction](#introduction)  
- [Papers](#papers)  
- [Code & Frameworks](#code--frameworks)  
- [Benchmarks & Environments](#benchmarks--environments)  
- [Tutorials & Courses](#tutorials--courses)  
- [Articles & Blogs](#articles--blogs)  
- [Applications](#applications)  
- [Contributing](#contributing)  
- [License](#license)  

---

## 🔹 Introduction
Safe RL is critical for deploying reinforcement learning in the real world – in **autonomous driving, robotics, drones, finance, and healthcare** – where unsafe exploration can cause irreversible damage.  

This list compiles **research papers, implementations, and learning resources** to accelerate work in the field.  

---

## 📄 Papers
### Foundational
- **Constrained Policy Optimization (CPO)** – Achiam et al., 2017.  
- **Lyapunov-based Safe RL** – Chow et al., 2018.  
- **Constrained MDPs & Safe Exploration** – Altman, 1999 (classic reference).  

### Recent & Notable
- **Safe Policy Optimization with Local Generalization** – NeurIPS 2023.  
- **Safety Gymnasium: Benchmarking Safe Exploration** – NeurIPS 2023.  
- **OmniSafe: Infrastructure for Safe RL** – ICML 2023.  

*(expand with year-sorted list later)*  

---

## 💻 Code & Frameworks
- [OmniSafe](https://github.com/PKU-Alignment/omnisafe) – PyTorch-based Safe RL framework with multiple algorithms.  
- [FSRL](https://github.com/PKU-Alignment/fsrl) – Safe RL in Tianshou, lightweight and practical.  
- [Safe-RL-Baselines](https://github.com/chenxianyu10/Safe-RL-Baselines) – Implementations of Safe RL algorithms.  
- [Safety Starter Agents](https://github.com/openai/safety-starter-agents) – OpenAI baseline implementations.  

---

## 🧪 Benchmarks & Environments
- [Safety Gymnasium](https://github.com/PKU-Alignment/safety-gymnasium) – successor to OpenAI’s Safety Gym.  
- [Safe Control Gym](https://github.com/utiasDSL/safe-control-gym) – safe control benchmarks in robotics.  
- [Safe Policy Optimization Benchmark](https://github.com/PKU-Alignment/safe-policy-optimization) – NeurIPS 2023 benchmark suite.  
- [OpenAI Safety Gym](https://github.com/openai/safety-gym) – early environment for safe exploration.  

---

## 📚 Tutorials & Courses
- [Safe RL Course – Topics in RL (PKU)](https://saferl-team.github.io/) – lectures + curated papers.  
- [Safe RL Overview (Lilian Weng blog)](https://lilianweng.github.io/) – accessible intro to Safe RL.  
- [Safe RL Workshop @ ICML/NeurIPS] – slides and talks (link collections).  

---

## 📰 Articles & Blogs
- **Why Safe RL Matters for Robotics** – Medium (various posts).  
- **Safe RL in Healthcare Applications** – arXiv insights.  
- **Towards Reliable RL Deployment** – Berkeley AI blog.  

---

## 🤖 Applications
- **Autonomous Driving** – ensuring safety constraints in exploration.  
- **Robotics** – preventing unsafe collisions during training.  
- **Healthcare** – treatment policies with safety guarantees.  
- **Finance** – risk-aware trading.  

---

## 🤝 Contributing
Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.  
We welcome:
- New papers with short summaries  
- Benchmarks and environments  
- Blog posts and tutorials  
- Practical implementations  

---

## 📜 License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)  
