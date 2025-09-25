# 📘 Awesome Safe Reinforcement Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
## Work In Progress. 
This repo is WIP, expect more changes etc. 

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
## Top Must Read Papers


## Foundational Works
1. **Altman, E. (1999). *Constrained Markov Decision Processes*.**  
   Classic theoretical foundation of constrained decision-making.  

2. **GarcÃ­a, J., & FernÃ¡ndez, F. (2015). *A Comprehensive Survey on Safe RL*.**  
   Early survey organizing approaches to safe exploration and constraints.  

3. **Moldovan, T., & Abbeel, P. (2012). *Safe Exploration in MDPs*.**  
   Introduced methods to explore safely while avoiding catastrophic failures.  

4. **Kakade, S. & Langford, J. (2002). *Approximately Optimal Approximate RL*.**  
   Introduces policy gradient methods with performance guarantees (basis for later safe RL).  

---

## Algorithmic Advances
5. **Achiam, J. et al. (2017). *Constrained Policy Optimization (CPO)*.**  
   First practical algorithm solving Constrained MDPs with guarantees.  

6. **Chow, Y. et al. (2018). *Lyapunov-based Safe RL*.**  
   Introduces Lyapunov functions for constraint satisfaction.  

7. **Dalal, G. et al. (2018). *Safe Exploration in Continuous Action Spaces*.**  
   Proposes safety layer to correct unsafe actions in continuous domains.  

8. **Bharadhwaj, H. et al. (2020). *Conservative Safety Critics for Exploration*.**  
   Improves exploration safety via conservative value estimates.  

9. **Thananjeyan, B. et al. (2021). *Recovery RL*.**  
   Framework for learning recovery policies that ensure constraint satisfaction.  

10. **Zhang, R. et al. (2021). *Safety Constraints in Deep RL via Trust Regions*.**  
    Trust region approach with explicit safety guarantees.  

---

## Benchmarks & Infrastructure
11. **Ray, A. et al. (2019). *Safety Gym (OpenAI)*.**  
    First widely-used benchmark for safe exploration.  

12. **Ji, J. et al. (2023). *Safety Gymnasium*.**  
    Modern, unified benchmark suite for safe RL, successor to Safety Gym.  

13. **Stooke, A. et al. (2020). *Implementation Matters in Deep RL*.**  
    Shows reproducibility issues, crucial for safe RL baselines.  

14. **Stooke, A. et al. (2021). *Safe Control Gym*.**  
    Robotics-focused safe control benchmarks.  

15. **Stooke, A. et al. (2023). *OmniSafe*.**  
    Infrastructure/framework implementing many Safe RL algorithms.  

---

## Applications
16. **Thomas, P. et al. (2015). *High Confidence Off-Policy Evaluation*.**  
    Importance sampling with safety guarantees â€“ relevant in healthcare/finance.  

17. **Huang, S. et al. (2018). *Learning Safe Policies for Autonomous Driving*.**  
    Demonstrates Safe RL in self-driving simulation.  

18. **Turchetta, M. et al. (2020). *Safe Exploration for Interactive Robotics*.**  
    Human-robot interaction with safety considerations.  

---

## Surveys & Overviews
19. **GarcÃ­a, J., & FernÃ¡ndez, F. (2015). *Safe RL Survey* (re-listed).**  
    Still a must-read reference for categorization of methods.  

20. **Pecka, M., & Svoboda, T. (2014). *Safe Exploration Techniques*.**  
    Survey focusing on safe exploration approaches.   

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
- [Safe-RL-Baselines](https://github.com/chauncygu/Safe-Reinforcement-Learning-Baselines) – Implementations of Safe RL algorithms.

- [Safety Control Gym Implementations](https://github.com/utiasDSL/safe-control-gym/tree/main) 
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
Contributions are welcome! You are welcome to submit a pull request for the suggestions for new papers, codes or other useful links.  
I welcome:
- New papers with short summaries  
- Benchmarks and environments  
- Blog posts and tutorials  
- Practical implementations  

---

## 📜 License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)  
