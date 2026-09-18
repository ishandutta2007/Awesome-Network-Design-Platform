# Awesome-Network-Design-Platform

## Top Network Design Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Supply Chain Network Design, Facility Location, Flow Optimization, Scenario Modeling, Digital Twins & Strategic Network Planning*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Supply Chain Network Design**. These systems help organizations determine the optimal number, location, and capacity of facilities (plants, DCs, warehouses), transportation flows, and inventory policies across multi-echelon networks—balancing cost, service, risk, and sustainability.



**Examples** include Coupa Supply Chain Design (formerly LLamasoft), anyLogistix, GAINS, CAST Aurora, Optilogic Cosmic Frog, Blue Yonder Network Design, ToolsGroup, Logility, and Dassault-related network design offerings (the category leaders).



**Open-source emphasis**: Full-featured commercial network design platforms with large-scale optimization, simulation, digital twins, and enterprise data integration are almost exclusively proprietary. Open-source activity centers on discrete-event simulation libraries, linear/integer programming examples, academic models, and general optimization toolkits. This section lists every significant relevant project and building block found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Coupa Supply Chain Design (powered by LLamasoft)](https://www.coupa.com/products/supply-chain-design/)**  

  Enterprise supply chain design and planning platform (originating from LLamasoft Supply Chain Guru) for network optimization, scenario modeling, and strategic design.



- **[anyLogistix](https://www.anylogistix.com/)**  

  Supply chain design and planning software combining optimization and discrete-event simulation for network design, inventory, transportation, and risk analysis.



- **[Optilogic Cosmic Frog](https://optilogic.com/)**  

  Cloud-native network design platform emphasizing rapid model building, optimization, simulation, and AI-assisted scenario exploration.



- **[Blue Yonder Network Design, ToolsGroup, Logility, GAINS](https://blueyonder.com/)**  

  Enterprise supply-chain planning suites that include network design, multi-echelon inventory, and strategic optimization capabilities.



- **[CAST Aurora and other specialized design tools](https://www.castsoftware.com/)**  

  Solutions focused on supply chain network modeling, flow optimization, and strategic design analytics.



- **[Dassault / other network design offerings](https://www.3ds.com/)**  

  Platform and industry solutions that support supply chain network design within broader digital-twin or operations ecosystems.



- **[Other commercial network design & optimization platforms](https://www.coupa.com/)**  

  Additional tools for facility location, transportation network design, and end-to-end supply chain strategy.



## Open-Source GitHub Projects



- **[SupplyNetPy](https://github.com/SupplyChainSimulation/SupplyNetPy)**  

  Python library for modeling, discrete-event simulation, design exploration, and optimization of supply chain networks and inventory systems (built on SimPy).



- **[Linear / integer programming network optimization examples](https://github.com/search?q=supply+chain+network+optimization+OR+facility+location+PuLP)**  

  Educational and research repositories formulating facility location, multi-echelon flow, and cargo/network routing problems with open solvers (PuLP, CBC, OR-Tools, etc.).



- **[Supply chain simulation frameworks](https://github.com/search?q=supply+chain+simulation+OR+discrete+event+supply+chain)**  

  Open discrete-event and agent-based simulation projects used to evaluate network configurations, inventory policies, and disruption scenarios.



- **[Carbon-aware & multi-objective network optimization](https://github.com/search?q=carbon+supply+chain+optimization+OR+green+network+design)**  

  Research code combining cost and emissions objectives for route and network design using ML and meta-heuristics.



- **[General optimization & OR toolkits](https://github.com/search?q=OR-Tools+OR+PuLP+network+design)**  

  Open solvers and modeling layers (Google OR-Tools, PuLP, Pyomo, etc.) frequently used to implement custom network design models.



- **[Topology & flow optimization engines (adjacent domains)](https://github.com/search?q=network+topology+optimization)**  

  Open engines from related domains (e.g., power-grid topology optimization) that illustrate scalable network optimization techniques.



- **[Data preparation & GIS helpers](https://github.com/search?q=supply+chain+GIS+OR+location+optimization)**  

  Open tools for geocoding, distance matrices, and spatial analysis that support network design data pipelines.



- **[Academic multi-echelon & location models](https://github.com/search?q=facility+location+OR+multi-echelon+network+design)**  

  Research implementations of classic and modern facility-location and multi-echelon design formulations.



### Additional Strong Open-Source Options



- **Simulation + optimization loops**: SupplyNetPy or custom SimPy models wrapped with open solvers for scenario evaluation.

- **LP/MILP facility-location models**: Explicit formulations solved with CBC, HiGHS, or OR-Tools for smaller-to-medium networks.

- **Meta-heuristics**: Genetic algorithms, simulated annealing, and other open implementations for large combinatorial network design problems.

- **Digital-twin style simulation**: Discrete-event models of end-to-end flows for what-if analysis.

- **Visualization**: Open GIS and network visualization libraries for mapping candidate networks.

- Research-to-prototype path: Build and validate models with open tools, then evaluate commercial platforms for enterprise scale, data integration, and collaborative scenario management.



**Frameworks for building custom systems**:  

There is no mature, full-featured open-source equivalent to commercial network design platforms (Coupa/LLamasoft, anyLogistix, Optilogic Cosmic Frog, Blue Yonder, etc.).  

Practical building blocks include **SupplyNetPy** and other simulation libraries, **open OR solvers** (PuLP, OR-Tools, Pyomo), and academic facility-location / multi-echelon models.  

These are valuable for education, research, and prototyping on modest networks.  

Enterprise network design requires scalable solvers, rich scenario management, data integration from ERP/TMS/WMS, risk and sustainability modeling, and collaborative workflows—capabilities that commercial platforms have industrialized.  

Most organizations use commercial network design software for strategic decisions and may leverage open-source components for research, benchmarking, or specialized extensions.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Network design decisions involve large capital and operational commitments. Models must be validated with accurate cost, demand, capacity, and service data; results are sensitive to assumptions and data quality.

- Open-source simulation and optimization tools offer transparency and learning value but generally lack the scalability, support, data connectors, and production hardening of commercial network design platforms. Evaluate computational requirements, data readiness, and organizational expertise carefully before relying on custom implementations for major strategic decisions.



---



**Made for supply chain strategists, network designers, operations researchers, and planners optimizing global and regional networks.**  

Let's advance open methods and research for supply chain network design while recognizing the specialized solvers, digital-twin capabilities, and enterprise features that leading commercial platforms deliver.
