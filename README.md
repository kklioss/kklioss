![Karl Li — Algorithms, Statistics, and Machine Learning](assets/research-banner.png)

<p align="center">
  <strong>Mathematics & Computer Science @ University of Michigan</strong> · Business minor
  <br />
  <a href="#research-interests">Research interests</a> ·
  <a href="#featured-open-source-work--smile">SMILE</a> ·
  <a href="#selected-research">Research</a> ·
  <a href="#professional-experience">Experience</a> ·
  <a href="#engineering--community">Engineering & community</a> ·
  <a href="https://www.linkedin.com/in/karl-li-a47963255">LinkedIn</a>
</p>

---

I am an undergraduate researcher interested in **how to make rigorous decisions under uncertainty, especially when observations, time, and computation are limited**. My work spans theoretical algorithms, statistical inference, and machine learning, with an emphasis on developing methods that are both mathematically principled and practically useful.

I am particularly excited by research that connects **proofs and guarantees** with **implementable algorithms and systems**. Alongside research collaborations with faculty in mathematics, operations research, and finance, I am a **maintainer of [SMILE](https://github.com/haifengl/smile)**, an open-source machine learning framework, where I build algorithms and local AI infrastructure.

### Research interests

| | |
| :--- | :--- |
| **Sequential decision-making** | Hypothesis testing, optimal stopping, adaptive experimentation |
| **Algorithms & optimization** | Online algorithms, approximation guarantees, resource allocation |
| **Statistical machine learning** | Learning under uncertainty, Bayesian modeling, reliable inference |
| **Efficient AI** | Adaptive allocation of computation across training, inference, and learning |

### Featured open-source work · SMILE

**[SMILE — Statistical Machine Intelligence & Learning Engine](https://github.com/haifengl/smile)**  
*Open-source maintainer & contributor · Machine learning, algorithms, and AI systems*

SMILE is a high-performance, open-source machine learning framework for the JVM, spanning statistical learning, optimization, manifold learning, and language-model inference. As a **maintainer**, I contribute across its algorithmic foundations and AI systems, connecting my research interests in mathematical methods with tools other people can use.

- **Local inference for open-weight LLMs.** Developed a high-performance **LibTorch-based inference engine** for locally running open-weight language models, including **Llama 3.1 and Qwen**. Worked on the surrounding inference/application stack using **C++, Java, Scala, and React**, including model integration and a streaming chat interface.
- **Optimization and machine learning algorithms.** Implemented **Prim's minimum spanning tree algorithm**, **Held–Karp dynamic programming**, **Christofides' approximation algorithm**, and **branch-and-bound** methods for the traveling salesperson problem, along with **UMAP** for nonlinear dimensionality reduction.
- **Research tooling and accessibility.** Contributed to SMILE's research-facing tools, including the local-first direction of **Agent Studio**, which aims to make AI-assisted data analysis, model training, and experimentation accessible without requiring paid cloud inference or institutional-scale computing infrastructure.

My motivation is to help make powerful statistical and AI tooling available to students and researchers who may only have access to **personal laptops and limited computing budgets**.

**[Explore the SMILE source code](https://github.com/haifengl/smile)** · **[SMILE website](https://www.aihalo.dev/)**

### Selected research

**01 · Tight Analysis for Online Generalized Network Design with Power Functions**  
*With Prof. Viswanath Nagarajan · **Accepted, SIAM Symposium on Simplicity in Algorithms (SOSA 2027)***

Developed and analyzed online algorithms for network-design problems with heterogeneous, nonlinear power costs. **I led the technical development end to end**, including the algorithmic approach, sharper competitive analysis, and primary manuscript drafting. The work improves prior competitive guarantees for online resource allocation under convex costs.

**02 · Beyond Wald's Approximate SPRT: Overshoot, Conditional Neyman–Pearson Reallocation, and an Implementable Sequential Testing Procedure**  
*With Prof. Yuqiong Wang · Under review, IEEE Transactions on Information Theory*

Designed an implementable family of sequential hypothesis tests that accounts for likelihood-ratio overshoot and reallocates unused error probability across stages. **I led the method development, theoretical work, numerical evaluation, and manuscript drafting.** In our experiments, the procedure used fewer samples than Wald's approximate SPRT in **35 of 36 settings**, with reductions of up to **27.5%**.

**03 · Optimal Stopping with Random Horizon under Partial Observation**  
*With Juno Fang, Sammy Singh, and Prof. Yuqiong Wang · Under review, NeurIPS AI Workshop*

Studied optimal stopping when the available decision horizon is random and the underlying state is only partially observed. **I developed the nonmyopic components of the work**, focusing on decisions that account for future information and downstream rewards rather than just immediate payoffs.

**04 · Congressional Trading and Information Asymmetry — Research with Prof. Nejat Seyhun**  
*University of Michigan · Ongoing empirical finance research*

Working with **Prof. Nejat Seyhun**, I developed an **end-to-end automated, AI-assisted research pipeline** for analyzing publicly disclosed congressional trading activity. The system transforms fragmented financial disclosures into structured data and identifies trading patterns for empirical investigation of potential insider-trading behavior. This project combines data engineering, machine learning, and quantitative financial research; flagged activity is a research signal, **not a legal finding**.

**05 · [Climate Change, Epidemics, Fiscal Breakdown, and the Collapse of the Great Ming](https://doi.org/10.31235/osf.io/rwe32)**  
*Independent research · [Preprint (2024)](https://doi.org/10.31235/osf.io/rwe32)*

Investigated the interaction of environmental shocks, epidemics, and fiscal institutions in the collapse of the Ming dynasty, integrating historical scholarship and interdisciplinary evidence. This project reflects my broader interest in using analytical methods to connect questions across disciplines.

### Professional experience

| Organization | Role | Focus |
| :--- | :--- | :--- |
| **Citadel** · 2026 | Quantitative Research Intern | Alpha research, alternative data, revenue forecasting, and systematic trading research |
| **Amazon Web Services (AWS AI)** · 2025 | Automated Reasoning Intern | Formal reasoning and methods for improving the reliability of AI systems |
| **Cmind** · 2024 | Quantitative Research & Software Development Intern | Machine learning and NLP for earnings prediction across 3,600+ companies; predictive signals and model development |

My industry work has strengthened how I approach research: start with a precise question, develop a testable hypothesis, build the right tools, and evaluate results carefully.

### Engineering & community

**Teaching assistant — EECS 498: Bayesian Methods for Machine Learning**  
Support instruction in Bayesian machine learning at the **University of Michigan**, helping students engage with probabilistic modeling, inference, and computational methods through coursework and technical guidance.

### Technical toolkit

| Category | Technologies |
| :--- | :--- |
| **Programming** | Python, C++, Java, Julia, Swift, SQL, JavaScript |
| **Machine learning & research** | PyTorch, Pandas, XGBoost, Bayesian inference, optimization, numerical experimentation |
| **Systems & development** | React, LibTorch, Git, Linux, AWS, Jupyter, relational databases |

<details>
<summary><strong>Earlier software projects</strong></summary>

- [CookieMonster](https://github.com/kklioss/CookieMonster) — Swift application.
- [Scarsdale Schools Bulletin Board](https://github.com/kklioss/ssbb) — JavaScript-based bulletin board project.
- [Scarsdale High School Trivia](https://github.com/kklioss/trivia) — Swift application.

</details>

---

<p align="center">
  <i>Interested in research conversations and collaboration at the intersection of algorithms, statistics, and learning.</i>
  <br />
  <a href="https://github.com/kklioss">GitHub</a> · <a href="https://www.linkedin.com/in/karl-li-a47963255">LinkedIn</a>
</p>
