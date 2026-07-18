---
permalink: /publications/
title: false
author_profile: true
---

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

<div class="pub-entry" markdown="1">

**Distributed Dynamic Algorithm for Energy Management in Smart Grids.**
S. Wasti, P. Macedo, S. Afshar, J. Griffin, V. R. Disfani, and P. Siano
Chapter 12 in *Decentralized Frameworks for Future Power Systems*, Academic Press, 2022, pp. 319–343

<div class="pub-links">
<a class="pub-btn" href="https://doi.org/10.1016/B978-0-323-91698-1.00008-X" target="_blank" rel="noopener"><i class="fas fa-external-link-alt" aria-hidden="true"></i> ScienceDirect</a>
</div>

<details class="pub-toggle"><summary>ABS</summary>
<p>Historically, the electric power grid has been dominated by fossil fuel-based power plants, where a central entity called the energy management system controls and optimizes resources. With the growth of renewable energy sources, distributed algorithms are projected as alternative paradigms to handle large optimization problems given the sheer volume of data and its privacy. This chapter studies the mathematical foundations for different decentralized and distributed algorithms applicable in power systems for convex functions to solve an economic dispatch problem. In the proposed algorithm, each agent updates the time-varying estimate of average power mismatch and the market price via dynamic average consensus in a distributed fashion and finds consensus on those variables. The problem is modeled as a discrete-time linear system, and the stability and convergence of the distributed subgradient algorithm are investigated. Finally, the efficacy of the algorithm is demonstrated in the IEEE 39 bus network.</p>
</details>

<details class="pub-toggle"><summary>BIB</summary>
<pre>@incollection{wasti2022distributed,
  title={Distributed dynamic algorithm for energy management in smart grids},
  author={Wasti, S. and Macedo, P. and Afshar, S. and Griffin, J. and Disfani, V. R. and Siano, P.},
  booktitle={Decentralized Frameworks for Future Power Systems},
  publisher={Academic Press},
  year={2022},
  pages={319--343},
  isbn={9780323916981},
  doi={10.1016/B978-0-323-91698-1.00008-X}
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

<div class="pub-entry" markdown="1">

**Distributed Inter-Area Oscillation Damping Control via Dynamic Average Consensus Algorithm.**
P. Macedo, S. Wasti, and V. Disfani
*2020 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)*, November 11–13, 2020, Tempe, AZ, USA

<div class="pub-links">
<a class="pub-btn" href="https://doi.org/10.1109/SmartGridComm47815.2020.9302945" target="_blank" rel="noopener"><i class="fas fa-external-link-alt" aria-hidden="true"></i> IEEE Xplore</a>
</div>

<details class="pub-toggle"><summary>ABS</summary>
<p>Massive deployment of distributed energy resources (DER) through zero-inertia power electronic converters has made the power grid vulnerable to frequency instabilities and in particular inter-area oscillations. Low-frequency oscillations are of major concerns as they have the potential to limit maximum power transfer, and even cause blackouts. This paper presents a novel distributed control algorithm called distributed frequency deviation control (DFDC) based on local frequency deviation from the estimate of the average frequency of the network. The efficacy of the control unit is demonstrated via modal analyses and time-domain simulations. The results show that all the inter-area oscillation modes are damped for all the test cases without affecting the other dynamic modes of the system.</p>
</details>

<details class="pub-toggle"><summary>BIB</summary>
<pre>@inproceedings{macedo2020distributed,
  title={Distributed Inter-Area Oscillation Damping Control via Dynamic Average Consensus Algorithm},
  author={Macedo, P. and Wasti, S. and Disfani, V.},
  booktitle={2020 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)},
  year={2020},
  doi={10.1109/SmartGridComm47815.2020.9302945}
}</pre>
</details>

</div>

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

**MMC-Based Distributed Maximum Power Point Tracking for Photovoltaic Systems.**
F. Mohamed, S. Wasti, S. Afshar, P. Macedo, and V. Disfani
*2020 IEEE Power & Energy Society General Meeting (PESGM)*, August 2–6, 2020, Montreal, QC, Canada

<div class="pub-links">
<a class="pub-btn" href="https://doi.org/10.1109/PESGM41954.2020.9282015" target="_blank" rel="noopener"><i class="fas fa-external-link-alt" aria-hidden="true"></i> IEEE Xplore</a>
</div>

<details class="pub-toggle"><summary>ABS</summary>
<p>This paper proposes a novel topology for grid connected photovoltaic (PV) system based on modular multilevel converter (MMC). In this topology, a PV array is connected to capacitors of each submodule (SM) of the MMC through a DC-DC boost converter with maximum power point tracking (MPPT) control. This topology will maximize the efficiency of the system in the case of partial shading conditions, as it can regulate the SM capacitor voltages independently from each other to realize distributed MPPT. A model predictive control is used to track the AC output current, balance the SMs capacitor voltages, and to mitigate the circulating current. The proposed PV generation topology with 7-level MMC system validity has been verified by simulations via MATLAB/Simulink toolbox under normal operation, partial shading and PV array failure.</p>
</details>

<details class="pub-toggle"><summary>BIB</summary>
<pre>@inproceedings{mohamed2020mmc,
  title={MMC-Based Distributed Maximum Power Point Tracking for Photovoltaic Systems},
  author={Mohamed, F. and Wasti, S. and Afshar, S. and Macedo, P. and Disfani, V.},
  booktitle={2020 IEEE Power \& Energy Society General Meeting (PESGM)},
  year={2020},
  doi={10.1109/PESGM41954.2020.9282015}
}</pre>
</details>

</div>

For a complete list, see my <a href="https://scholar.google.com/citations?user=5ckMkHkAAAAJ&hl=en&oi=ao" target="_blank" rel="noopener">Google Scholar</a> profile.
