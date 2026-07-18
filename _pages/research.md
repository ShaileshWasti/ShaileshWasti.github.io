---
permalink: /research/
title: false
author_profile: true
---

## (Real-Time) Electricity Market Design

The evolving resource mix increases net-load variability and short-term forecast uncertainty. System operators face the challenge of managing this cost-effectively and reliably within a merit-order-based market design. I study the management of storage, the incorporation of uncertainty into market simulation models, and the effects on price formation, with practical implications for RTOs/ISOs' operational and market design considerations — especially how merit-order-based dispatch fares when opportunity cost, rather than heat rate and fuel cost, drives price formation.

### Simulation Framework

<img src="/images/research/blockdiagram-msm.png" alt="Market simulation model block diagram" class="diagram-img">

For full documentation, see the Energy Market Simulation Framework (EMSF) repository <a href="https://github.com/PowerPSU/EMSF" title="EMSF on GitHub"><i class="fab fa-github" aria-hidden="true"></i></a>, developed by a team in the <a href="https://www.eme.psu.edu/directory/mort-d-webster">Mort Webster</a> group at Penn State (<a href="https://github.com/orgs/PowerPSU/repositories">PowerPSU</a>).

### Publications

<div class="pub-entry" markdown="1">

**Energy Storage State-of-Charge Management in Real-Time Markets.**
S. Wasti, A. Retna Kumar, S. Varghese, A. Giacomoni, and M. D. Webster
*2025 IEEE Power & Energy Society General Meeting (PESGM)*, July 27–31, 2025

<div class="pub-links">
<a class="pub-btn" href="https://ieeexplore.ieee.org/abstract/document/11225837" target="_blank" rel="noopener"><i class="fas fa-external-link-alt" aria-hidden="true"></i> IEEE Xplore</a>
<a class="pub-btn" href="/files/papers/Wasti_PESGM2025_SoC_Management.pdf" target="_blank" rel="noopener"><i class="fas fa-file-pdf" aria-hidden="true"></i> PDF</a>
</div>

<details class="pub-toggle"><summary>ABS</summary>
<p>The evolving resource mix will likely increase net load variability and forecast errors. While numerous studies show that grid-scale energy storage resources (ESRs) can mitigate reliability issues, they often assume perfect foresight of net load when optimizing their State-of-Charge (SoC). In practice, electricity markets operate on a rolling horizon, frequently updating short-term load forecasts. At each market clearing, operators must allocate SoC between immediate and later needs under forecast uncertainty. Through simulations of operator-managed ESRs within PJM's real-time markets under a future resource mix, we demonstrate that both a greedy strategy that prioritizes smoothing load volatility as it occurs and a conservative strategy that holds energy for peak load arbitrage can exacerbate reliability issues. We propose an SoC management framework that balances between the greedy and conservative strategies, improving reliability by absorbing near-term net load shocks while maintaining SoC for expected peak load beyond the horizon of real-time processes.</p>
</details>

<details class="pub-toggle"><summary>BIB</summary>
<pre>@inproceedings{wasti2025storage,
  title={Energy Storage State-of-Charge Management in Real-Time Markets},
  author={Wasti, S. and Retna Kumar, A. and Varghese, S. and Giacomoni, A. and Webster, M. D.},
  booktitle={2025 IEEE Power \& Energy Society General Meeting (PESGM)},
  year={2025}
}</pre>
</details>

</div>

## Distributed Algorithms for Microgrids

Microgrids with a high share of distributed energy resources (DER) — rooftop solar, storage, and flexible loads — require coordination among many small, privately-owned agents, where relying on a central coordinator to gather generation and demand data raises both privacy and scalability concerns. My earlier work used distributed optimization methods, building on the Alternating Direction Method of Multipliers (ADMM) and dynamic consensus algorithms, so that agents in a microgrid can jointly solve resource-allocation problems like economic dispatch by communicating only with their neighbors.

### Publications

<div class="pub-entry" markdown="1">

**Distributed Dynamic Economic Dispatch using Alternating Direction Method of Multipliers.**
S. Wasti, P. Ubiratan, S. Afshar, and V. Disfani
*Applied Energy Symposium: MIT A+B (APEN-MIT)*, August 12–14, 2020

<div class="pub-links">
<a class="pub-btn" href="https://www.energy-proceedings.org/distributed-dynamic-economic-dispatch-using-alternating-direction-method-of-multipliers/" target="_blank" rel="noopener"><i class="fas fa-external-link-alt" aria-hidden="true"></i> Published</a>
<a class="pub-btn" href="/files/papers/Wasti_APEN2020_DistributedED.pdf" target="_blank" rel="noopener"><i class="fas fa-file-pdf" aria-hidden="true"></i> PDF</a>
</div>

<details class="pub-toggle"><summary>ABS</summary>
<p>With the proliferation of distributed energy resources and the volume of data stored due to advancement in metering infrastructure, energy management in power system operation needs distributed computing. In this paper, we propose a fully distributed Alternating Direction Method of Multipliers (ADMM) algorithm to solve the distributed economic dispatch (ED) problem, where the optimization problem is fully decomposed between participating agents. In our proposed framework, each agent estimates the dual variable and the average of the total power mismatch of the network using dynamic average consensus, which replaces the dual updater in the traditional ADMM with a distributed alternative. Unlike other distributed ADMM, the proposed method does not rely on any specific assumption and captures the real-time demand change. The algorithm is validated successfully via case studies for IEEE 30-bus and 300-bus test systems with the penetration of solar photovoltaic.</p>
</details>

<details class="pub-toggle"><summary>BIB</summary>
<pre>@inproceedings{wasti2020distributed,
  title={Distributed Dynamic Economic Dispatch using Alternating Direction Method of Multipliers},
  author={Wasti, S. and Ubiratan, P. and Afshar, S. and Disfani, V.},
  booktitle={Proceedings of Applied Energy Symposium: MIT A+B},
  year={2020}
}</pre>
</details>

</div>

<div class="pub-entry" markdown="1">

**Distributed Online Algorithms for Energy Management in Smart Grids.**
S. Wasti
*M.S. Thesis, University of Tennessee at Chattanooga*, December 2020

<div class="pub-links">
<a class="pub-btn" href="https://scholar.utc.edu/cgi/viewcontent.cgi?article=1845&context=theses" target="_blank" rel="noopener"><i class="fas fa-external-link-alt" aria-hidden="true"></i> Thesis</a>
</div>

<details class="pub-toggle"><summary>ABS</summary>
<p>The 21st-century electric power grid is transitioning from a centralized structure designed for bulk-power transfer to a distributed paradigm that integrates the variable renewable energy (VRE) resources spatially distributed across the grid. This work proposes algorithmic solutions for distributed economic dispatch based on the Subgradient method and the Alternating Direction Method of Multipliers (ADMM), both designed to be agnostic to any initialization vector. The proposed distributed online solutions leverage a dynamic average consensus algorithm to track the time-variant, linearly coupled constraint that allows an abrupt change in power demand of the network because of the high penetration of VRE resources. The problems are modeled as discrete dynamic systems to investigate the stability and convergence of the algorithm. The update procedures are designed such that the iterates converge to the optimal solution of the original optimization problem, steered by the gain parameter corresponding to the second largest eigenvalue of the system matrix.</p>
</details>

<details class="pub-toggle"><summary>BIB</summary>
<pre>@mastersthesis{wasti2020thesis,
  title={Distributed Online Algorithms for Energy Management in Smart Grids},
  author={Wasti, Shailesh},
  school={University of Tennessee at Chattanooga},
  year={2020},
  month={December}
}</pre>
</details>

</div>
