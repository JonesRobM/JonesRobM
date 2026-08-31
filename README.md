# Robert M. Jones, PhD

**Applied AI Scientist** — physics-grounded machine learning for defence and national security.

Theoretical and computational physicist by training (King's College London, The Alan Turing Institute), specialising in nonlinear and chiral light–matter interactions, and still maintaining scientific software in that field. I build ML systems that respect physical constraints: simulation, uncertainty quantification, and evaluation tooling that tells you when a model is wrong.

[ORCID](https://orcid.org/0000-0002-5422-3088) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=Zyqv3N8AAAAJ) · [LinkedIn](https://www.linkedin.com/in/robert-jones-a12b25129/)

---

## Selected work

**Applied AI — evaluation, tooling, uncertainty**

| Project | Summary |
|---|---|
| [**PhysBound**](https://github.com/JonesRobM/physbound) | MCP server that lints RF and physical-layer calculations against hard physical limits (Shannon, Friis, radar range). Catches LLM physics hallucinations. On PyPI and the MCP Registry; CI + coverage. |
| [**RagOnAStick**](https://github.com/JonesRobM/RagOnAStick) | Retrieval evaluation harness for UK MoD Joint Doctrine publications. Seven retriever/chunking configurations benchmarked (recall@k, MRR, nDCG) with MLflow logging. No generation — just measurement. |
| [**Chrono-Sentinel**](https://github.com/JonesRobM/Chrono-Sentinel) | Transformer-based time-series anomaly detection on the Numenta Anomaly Benchmark, with Monte Carlo Dropout uncertainty quantification and calibration analysis. |

**Scientific software — simulation and physics-constrained ML**

| Project | Summary |
|---|---|
| [**Sapphire**](https://github.com/JonesRobM/Sapphire) | Post-processing environment for the structural characterisation of metallic nanoparticles and nanoalloys from MD trajectories — CNA signatures, coordination and aGCN, chemical ordering, change-point detection of melting transitions. Lead author; published in *Faraday Discussions* **242** (2023), `pip install sapphire-nano`, DOI-archived, CI + docs + executable tutorials. |
| [**Lumina**](https://github.com/JonesRobM/Lumina) | Rust framework for electromagnetic simulation of nanostructures via the Coupled Dipole Approximation. GPU-accelerated, O(N)-memory GMRES, Ewald-summed periodic systems, SHG/THG. 136 tests. |
| [**Metamaterials_PINN**](https://github.com/JonesRobM/Metamaterials_PINN) | Physics-informed neural networks for electromagnetic problems in metamaterials — Maxwell-constrained training with reproducible configs and tests. |

Also public: [energy-demand forecasting](https://github.com/JonesRobM/EnergyConsumption) across 10 US regions (LSTM/GRU/TFT vs gradient-boosted baselines), and unmaintained PhD-era code for HHG data processing, DFT tooling and nanoparticle dynamics.

---

## Background

- **Applied AI Scientist**, Whitespace (2026–present) — applied ML for defence and national-security problems.
- **Data Scientist**, The Alan Turing Institute (2025–2026) — ML and statistical modelling on HPC for AI research, and radio-frequency digital signal processing in defence and national-security contexts.
- **Postdoctoral Research Associate**, King's College London (2023–2025) — chiral and nonlinear light–matter interactions; computational and analytical frameworks for quantum-chemistry prediction.

**Education:** PhD Physics, KCL (2022) · MSc Non-Equilibrium Systems, KCL (2019) · MPhys Theoretical Physics, Leeds (2018)

---

## Technical

**Languages:** Python (PyTorch), Rust, C++, Fortran, SQL
**Scientific computing:** MPI, CUDA, OpenMP, HPC schedulers
**Engineering:** Docker, CI/CD (GitHub Actions), pytest, MLflow, packaging and release (PyPI), Linux, LaTeX
