---
permalink: /research/
title: false
author_profile: true
---

<h2>(Real-Time) Electricity Market Design <span class="cluster-tag cluster-tag--current">Current</span></h2>

The growing penetration of weather-dependent renewable resources, particularly wind and solar, increases net-load variability and short-term forecast uncertainty. System operators face the challenge of managing this cost-effectively and reliably within a merit-order-based market design. I study the management of storage, the incorporation of uncertainty into market simulation models, and the effects on price formation, with practical implications for RTOs/ISOs' operational and market design considerations — especially how merit-order-based dispatch fares when opportunity cost, rather than heat rate and fuel cost, drives price formation.

### Simulation Framework

<img src="/images/research/blockdiagram-msm.png" alt="Market simulation model block diagram" class="diagram-img">

For full documentation, see the Energy Market Simulation Framework (EMSF) repository <a href="https://github.com/PowerPSU/EMSF" title="EMSF on GitHub"><i class="fab fa-github" aria-hidden="true"></i></a>, developed by a team in the <a href="https://www.eme.psu.edu/directory/mort-d-webster">Mort Webster</a> group at Penn State (<a href="https://github.com/orgs/PowerPSU/repositories">PowerPSU</a>).

## Publications

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

<h2>Earlier Research <span class="cluster-tag cluster-tag--prior">M.S. Research, 2018–2021</span></h2>

During my M.S., I worked on distributed algorithms for microgrid coordination and power-electronic converter design for renewable integration.

### Distributed Algorithms for Microgrids

Microgrids with a high share of distributed energy resources (DER) — rooftop solar, storage, and flexible loads — require coordination among many small, privately-owned agents, where relying on a central coordinator to gather generation and demand data raises both privacy and scalability concerns. My earlier work used distributed optimization methods, building on the Alternating Direction Method of Multipliers (ADMM) and dynamic consensus algorithms, so that agents in a microgrid can jointly solve resource-allocation problems like economic dispatch by communicating only with their neighbors.

- S. Wasti, P. Ubiratan, S. Afshar, and V. Disfani, "[Distributed Dynamic Economic Dispatch using Alternating Direction Method of Multipliers](https://www.energy-proceedings.org/distributed-dynamic-economic-dispatch-using-alternating-direction-method-of-multipliers/)," *Applied Energy Symposium: MIT A+B*, August 2020.
- S. Wasti, P. Macedo, S. Afshar, J. Griffin, V. R. Disfani, and P. Siano, "[Distributed Dynamic Algorithm for Energy Management in Smart Grids](https://doi.org/10.1016/B978-0-323-91698-1.00008-X)," in *Decentralized Frameworks for Future Power Systems*, Academic Press, 2022.

### Power Systems and Power Electronics

The increasing penetration of inverter-based and distributed resources is changing the physical behavior of the grid, from how it responds to disturbances to how energy is captured and converted at the hardware level. My early work explored this challenge from two angles: distributed control algorithms that help maintain system stability without relying on centralized, wide-area communication, and power-electronic converter topologies that improve energy capture and reliability, validated through simulation studies.

- P. Macedo, S. Wasti, and V. Disfani, "[Distributed Inter-Area Oscillation Damping Control via Dynamic Average Consensus Algorithm](https://doi.org/10.1109/SmartGridComm47815.2020.9302945)," *IEEE SmartGridComm*, November 2020.
- F. Mohamed, S. Wasti, S. Afshar, P. Macedo, and V. Disfani, "[MMC-Based Distributed Maximum Power Point Tracking for Photovoltaic Systems](https://doi.org/10.1109/PESGM41954.2020.9282015)," *IEEE PES General Meeting*, 2020.

See the [Publications](/publications/) page for the complete list.
