<h1 align="center">Pablo E. González</h1>

<p align="center">
  <em>Data Science &amp; Mathematics Engineering @ Tecnológico de Monterrey · Guadalajara, México</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-probabilistic%20modeling-2563eb?style=flat-square" alt="focus">
  <img src="https://img.shields.io/badge/heading%20toward-quantitative%20risk-1e40af?style=flat-square" alt="heading toward">
  <img src="https://img.shields.io/badge/currently-研究%20%2F%20research-64748b?style=flat-square" alt="currently">
</p>

---

I build models of systems that don't behave deterministically — surveys, clinical data, physical processes — and I care more about whether a model survives validation than whether it fits.

Most of what's here follows one thread: **quantifying uncertainty and reasoning under it.** Bayesian networks, sampling-based inference, numerical integration, inverse measurement problems. The destination is quantitative risk management; these are the stops along the way.

Every README below describes what the code actually does, including the defects I know about. If something is broken, it's written down.

---

## 🔬 Current work

Gravitational-wave glitch classification with a CNN on Gravity Spy / LIGO data, and a literature base toward a co-authored paper in optimization. Coursework this semester is stochastic optimization — Markov chains, exponential distributions.

## 🧠 Probabilistic modeling & inference

| Project | What it does | Stack |
|---|---|---|
| **[transporte-en-mx-mbn](https://github.com/pablogzrs/transporte-en-mx-mbn)** | Multinomial Bayesian networks on Mexico's national mobility survey (ENMT–UNAM). Three competing structural specifications compared by BIC/AIC, conditional queries by rejection sampling at 10⁶ replicates, and validation against observed frequencies plus a 500-replicate bootstrap. The model with the *worst* fit is the one kept for querying — its constraints were specified a priori, and the README explains why that matters. | `R` `bnlearn` `Quarto` |
| **[ERC-gbn](https://github.com/pablogzrs/ERC-gbn)** | Gaussian Bayesian network over a chronic kidney disease dataset. Structure learning by hill climbing, candidate DAGs compared by Gaussian BIC/AIC. *In progress.* | `R` `Python` `bnlearn` |
| **[premier-league-investment-analysis](https://github.com/pablogzrs/premier-league-investment-analysis)** | Does capital injection buy league performance? Newcastle vs. Everton across seven seasons, with correlation structure over squad value, net transfer spend, points and final standing. | `Python` `pandas` `seaborn` |

## 📐 Numerical & physical modeling

| Project | What it does | Stack |
|---|---|---|
| **[popocatepetl-eruption-simulator](https://github.com/pablogzrs/popocatepetl-eruption-simulator)** | Ballistic trajectories of volcanic ejecta under drag, integrated by Euler's method, plotted against the real distances to Ecatzingo and Amecameca. | `MATLAB` |
| **[capacitance-simulator](https://github.com/pablogzrs/capacitance-simulator)** | Capacitive liquid-level sensor. Inverts the parallel-plate capacitance equation to recover fill level from a measured capacitance, across six dielectrics — including a measured water response that lands a factor of ~4 below what the ideal model predicts. | `MATLAB` `App Designer` |

## 🧱 Earlier coursework

First- and second-year C++ work, kept for the record rather than presented as current.

| Project | What it does | Stack |
|---|---|---|
| **[jfk-airport-simulator](https://github.com/pablogzrs/jfk-airport-simulator)** | Turn-based airport traffic toy: five-slot airspace with FIFO eviction, probabilistic arrivals, UFO easter eggs. | `C++` |
| **[olympic-diving-simulator](https://github.com/pablogzrs/olympic-diving-simulator)** | Diving competition where the score distribution is conditioned on dive difficulty and the judge panel anchors to the first judge, so the scores are correlated by construction. | `C++` |
| **[media-catalog-system](https://github.com/pablogzrs/media-catalog-system)** | Movie and episode catalog: abstract base class, field-count parser, rating averages. | `C++` |

---

## 🛠️ Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/MATLAB-E16737?style=flat-square" alt="MATLAB">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/bnlearn-276DC3?style=flat-square" alt="bnlearn">
  <img src="https://img.shields.io/badge/Quarto-39729E?style=flat-square&logo=quarto&logoColor=white" alt="Quarto">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

**Methods:** Bayesian networks · structure learning · Monte Carlo inference · bootstrap validation · numerical integration · linear &amp; stochastic optimization · Markov chains · CNNs

---

<p align="center">
  <sub>Español · English · 中文 (HSK4, 学习中)</sub>
</p>
