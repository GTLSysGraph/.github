<h1 align="center">
  <img src="https://raw.githubusercontent.com/GTLSysGraph/.github/main/profile/assets/htai-lab.gif" width="100%" alt="HTAI-Lab, High-Throughput Computing Systems Group at the Institute of Computing Technology, Chinese Academy of Sciences">
</h1>

<p align="center">
  <strong>中国科学院计算技术研究所 · 高通量计算机研究中心 · 高通量计算系统组</strong>
  <br>
  High-Throughput Computer Research Center · ICT, CAS
  <br>
  <a href="#about"><strong>🏛️ About</strong></a> ·
  <a href="#research"><strong>🔬 Research</strong></a> ·
  <a href="#projects"><strong>📚 Projects</strong></a> ·
  <a href="https://github.com/orgs/GTLSysGraph/repositories"><strong>💻 Repositories</strong></a>
</p>

---

<a name="about"></a>

## 🏛️ About the group

We are the **High-Throughput Computing Systems Group** at the **High-Throughput Computer Research Center**, Institute of Computing Technology, Chinese Academy of Sciences. We study computing systems and AI algorithms for large-scale data workloads. Our public projects span dynamic graph processing, robust graph representation learning, and industrial recommendation. [About the research center](https://english.ict.cas.cn/rese/divi/cs/202302/t20230209_326889.html)

我们是**中国科学院计算技术研究所高通量计算机研究中心的高通量计算系统组**。我们面向大规模数据处理和智能应用，研究高通量计算系统与 AI 算法。当前公开工作涵盖动态图存储与分析、鲁棒图学习和工业推荐。 [研究中心介绍](https://www.ict.cas.cn/jssgk/zzjg/kyxt/gtljsj/js/)

<a name="research"></a>

## 🔬 Research

| Area | Questions we study |
| --- | --- |
| **High-throughput computing and acceleration** | How can storage layout, parallel execution, and hardware acceleration be designed together for data that changes continuously? |
| **Graph learning and robustness** | How can pre-training, masking, prompt tuning, and semantic refinement produce useful representations when graph data is noisy or heterophilic? |
| **AI algorithms and intelligent applications** | How can learning methods adapt to sparse signals and shifting distributions in production? Our broader interests include reinforcement learning and AI agents. |

<a name="projects"></a>

## 📚 Public research and tools

- 🗄️ **(IEEE TKDE 2026)** [A Comprehensive Survey on Dynamic Graph Processing: Storage and Analytics](https://github.com/GTLSysGraph/DynGraphSurvey#readme). A survey of how dynamic graphs are stored, updated, and analyzed on CPUs and GPUs.
- 🛡️ **(ICLR 2025)** [GPromptShield: Elevating Resilience in Graph Prompt Tuning Against Adversarial Attacks](https://github.com/GTLSysGraph/GPromptShield#readme). Introduces two complementary defenses to make graph prompt tuning more robust to perturbed inputs.
- 🧩 **(DASFAA 2026)** [SemFuse: Aligning LLM Semantics with Graph Topology for Heterophilic Learning](https://github.com/GTLSysGraph/SemFuse#readme). Uses LLM-based edge refinement and two-view graph learning to improve node classification on heterophilic graphs.
- 🧼 **(Neurocomputing 2025)** [SPMGAE: Self-purified masked graph autoencoders release robust expression power](https://github.com/GTLSysGraph/SPMGAE#readme). Learns robust node representations through graph purification, mirror-guided encoding, and feature and structure reconstruction.
- 🎛️ **(SDM 2025)** [Equipping Graph Autoencoders: Revisiting Masking Strategies from a Robustness Perspective](https://github.com/GTLSysGraph/FilterMGAE#readme). Introduces reliability-ranked masking and decoupled feature reconstruction for noisy graphs.
- ✈️ **(IEEE ICDM 2026)** [FSLNet: Episodic Few-Shot Adaptation for Industrial Recommender Systems](https://github.com/GTLSysGraph/FSLNet#readme). The paper companion describes how recent interaction prototypes help predict conversions in industrial travel recommendations.

### 🧰 Research toolkit

- [ALOHA Graph Foundry](https://github.com/GTLSysGraph/ALOHA#readme). A workbench for graph autoencoders and graph contrastive learning, with shared training entry points, dataset adapters, and experiment logs.

For implementation questions or corrections to the reading lists, use the relevant repository’s issue tracker.
