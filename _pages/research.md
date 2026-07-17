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
