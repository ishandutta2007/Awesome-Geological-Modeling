# Awesome-Geological-Modeling

## Top Geological Modeling Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on 3D Implicit & Explicit Geological Modelling, Resource Estimation, Structural Geology & Subsurface Interpretation*

**Last updated: September 2026**



This repository tracks notable **SaaS/desktop platforms** and **open-source projects** for **Geological Modeling**. These systems build 3D geological models from drillholes, structural data, and geophysics for mining, exploration, petroleum, and geotechnical applications.



**Examples** include Leapfrog Geo (Seequent), Datamine Studio RM, Micromine Origin, Petrel, Move (Petroleum Experts), RockWorks, GeoModeller, Maptek Vulcan, and GEOVIA (the category leaders).



**Open-source emphasis**: Production mining and petroleum geological modelling is dominated by commercial software. The strongest open option is **GemPy** for implicit 3D structural modelling, plus supporting Python geoscience libraries. This section lists the best available open resources and is realistic about the commercial gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Leapfrog Geo (Seequent)](https://www.seequent.com/)**  

  Industry-leading implicit 3D geological modelling platform widely used in mining and exploration for rapid model building, structural interpretation, and collaboration (including cloud hybrid workflows via Seequent Evo).



- **[Datamine Studio RM](https://www.dataminesoftware.com/)**  

  Comprehensive resource modelling and mine planning suite with strong geological modelling, estimation, and evaluation tools.



- **[Micromine Origin](https://www.micromine.com/)**  

  Integrated exploration and geological modelling platform covering data management, 3D modelling, and resource workflows.



- **[Petrel (SLB)](https://www.software.slb.com/)**  

  Leading subsurface modelling and interpretation platform for petroleum geology, geophysics, and reservoir characterization.



- **[Move by Petroleum Experts](https://www.petex.com/)**  

  Structural geology and kinematic modelling software used for tectonic restoration, fault analysis, and geological model building.



- **[RockWorks](https://www.rockware.com/)**  

  Desktop geological and environmental modelling software popular for borehole data, cross-sections, and 3D visualization.



- **[GeoModeller](https://www.intrepid-geophysics.com/)**  

  3D geological modelling platform supporting implicit and explicit methods, often used with geophysical inversion workflows.



- **[Maptek Vulcan](https://www.maptek.com/)**  

  Mine design and geological modelling suite with strong tools for structural frameworks, resource modelling, and mine planning.



- **[GEOVIA (Dassault Systèmes)](https://www.3ds.com/)**  

  Geology and mine planning solutions within the Dassault portfolio for modelling, design, and operations.



- **[Other commercial geoscience suites](https://www.example.com/)**  

  Additional specialized tools for petroleum, mining, and geotechnical geological modelling.



## Open-Source GitHub Projects

- **[GemPy](https://github.com/gempy-project/gempy)**  

  Leading open-source Python library for 3D implicit structural geological modelling—builds complex models from interface and orientation data, with support for faults, folds, unconformities, and probabilistic uncertainty analysis.



- **[GemGIS and related geospatial helpers](https://github.com/)**  

  Open Python tools that integrate GIS data with GemPy and other geomodelling workflows.



- **[PyGSLIB and geostatistics open libraries](https://github.com/)**  

  Open-source geostatistical toolkits used for resource estimation and spatial analysis alongside geological models.



- **[QGIS geology and 3D plugins](https://github.com/qgis/QGIS)**  

  Open desktop GIS with plugins and processing tools useful for geological mapping, cross-sections, and data preparation.



- **[VTK / PyVista visualization stacks](https://github.com/)**  

  Open 3D visualization libraries commonly used to render and explore geological models produced by GemPy or custom codes.



- **[SimPEG and geophysical inversion open tools](https://github.com/)**  

  Open frameworks for geophysical modelling and inversion that can be coupled with geological models.



- **[pyGIMLi and related geophysics libraries](https://github.com/)**  

  Open geophysical modelling and inversion tools used in integrated geoscience workflows.



- **[Drillhole and borehole open data tools](https://github.com/)**  

  Libraries for parsing, validating, and visualizing drillhole and well data as input to modelling.



- **[Academic and research geomodelling codes](https://github.com/)**  

  University and research-group repositories implementing implicit or explicit modelling algorithms.



- **[Stochastic and uncertainty open frameworks](https://github.com/)**  

  Tools that support Monte Carlo and Bayesian approaches to geological model uncertainty (often used with GemPy).



### Additional Strong Open-Source Options

- Using **GemPy** as the primary open path for implicit 3D structural modelling and teaching/research.

- Combining GemPy models with **QGIS**, **PyVista**, and open geostatistics for end-to-end open workflows.

- Preparing data in open GIS/geostats tools and exporting to commercial packages (Leapfrog, Vulcan, etc.) when production sign-off is required.

- Accepting that full mine-resource estimation suites, petroleum reservoir modelling, certified workflows, and enterprise collaboration still favor commercial platforms (Leapfrog/Seequent, Datamine, Micromine, Petrel, Vulcan, GEOVIA, etc.).

- Focusing open-source efforts on transparency, reproducibility, and uncertainty quantification.



**Frameworks for building custom systems**: Load interface/orientation data → build implicit models with GemPy → visualize with PyVista/VTK → add geostatistics or inversion with open libraries → export grids or surfaces to commercial software when needed. Suitable for research, teaching, and early-stage exploration. Most operating mines and petroleum assets rely on commercial geological modelling platforms for production decisions.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Geological models underpin resource estimates and engineering decisions. Open-source tools require competent geological interpretation and validation. This list is not professional geoscience or reserve-reporting advice.



---

**Made for geologists, resource modellers, and geoscience software teams.**

Let's keep geological modelling reproducible, transparent, and as open as practical.
