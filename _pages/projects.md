---
title: 'Projects'
layout: single
permalink: /projects/
author_profile: true
excerpt: 'Below are the projects I am currently working on and those I have completed, with links to the papers and source code where they are publicly available.'
header:
  overlay_image: /images/Profile-picture.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
---

## Current Projects

- <small>**Algorithm Development and Calibration/Validation of the BIOMASS Above-Ground Biomass (AGB) Product** (ESA BIOMASS mission, Chalmers University of Technology, Sep 2026 – Present): I develop retrieval algorithms that estimate global forest above-ground biomass from P-band synthetic aperture radar (SAR). This product is the observational basis for carbon stock assessment and forest-related climate mitigation monitoring. My work covers:</small>
  - <small>building processing and inference pipelines over multi-temporal, multi-polarisation SAR stacks, including speckle handling, geometric and radiometric correction, feature extraction and retrieval;</small>
  - <small>calibrating and validating the operational product against in situ and airborne reference data, with quantified uncertainty attached to every retrieved estimate;</small>
  - <small>applying spatiotemporal machine learning, physics-informed architectures and uncertainty quantification to SAR-based biomass estimation, within an international ESA mission consortium.</small>

## Completed Projects

### Physics-Informed Modelling & Uncertainty Quantification

- <small>**NeuroDDAF: Neural Dynamic Diffusion-Advection Fields with Evidential Fusion** (PhD / TU Delft collaboration, 2025 – 2026): This is a physics-informed air quality forecasting framework. It couples graph representations of ground observation networks with explicit diffusion and advection transport dynamics and neural ODE components. Evidential fusion returns calibrated uncertainty as a first-class output, so predictions stay physically consistent rather than merely well fitted. (**[Preprint](https://arxiv.org/abs/2604.01175)**) (**[Code](https://github.com/Prasanjit-Dey/NeuroDDAF)**)</small>

- <small>**Satellite-Based Air Quality Forecasting with Physical Transport Constraints** (Visiting Research Scientist, TU Delft, Geoscience and Remote Sensing, May – Aug 2025): I worked on this with Dr. Angela Meyer, leading development of a coupled dynamics-and-learning framework for urban air quality. I integrated deep learning with physical transport constraints, worked with large-scale satellite and meteorological datasets, and implemented uncertainty-aware PM2.5 and NO<sub>2</sub> forecasting. The collaboration continues as a joint publication partnership.</small>

- <small>**AirGRU: A Physics-Informed Model for PM2.5 Prediction** (PhD project, 2026): A physics-informed recurrent model for PM2.5 forecasting, presented at iEMSs 2026 in Dublin.</small>

### Foundation Models & LLMs for Time Series

- <small>**GPT4AP: Meteorology-Driven Multi-Task Forecasting LLM** (PhD project): A lightweight LLM-based framework for multi-task forecasting of atmospheric air pollutants, driven by meteorological inputs. It supports few-shot, zero-shot and long-horizon prediction, and it is evaluated on transfer into data-scarce regions without dense monitoring, not only on in-distribution data. (**[Preprint](https://arxiv.org/abs/2603.29974)**)</small>

- <small>**One-for-All: Lightweight Parameter-Efficient LLM Adaptation for Time Series Forecasting** (PhD project, 2024): A lightweight fine-tuning framework that adapts pretrained LLMs for structured temporal forecasting at low computational cost. It uses Gaussian rank-stabilised low-rank adapters (rsLoRA) to improve stability and generalisation across diverse time-series datasets, while training only a fraction of the parameters that conventional fine-tuning needs. (**[Preprint](https://arxiv.org/abs/2603.29756)**) (**[Code](https://github.com/Prasanjit-Dey/One_for_All)**)</small>

### Satellite Remote Sensing & Air Quality

- <small>**Monitoring and Short-term Forecasting of Atmospheric Air Pollutants Using Deep Neural Networks** (PhD project, TU Dublin, Sep 2022 – Jun 2026): This was my doctoral research programme, funded by the Research Ireland D-REAL Centre. I developed transformer, graph and generative architectures for multistep spatiotemporal forecasting of PM2.5, NO<sub>2</sub> and O<sub>3</sub>, fusing satellite retrievals, ground observation networks and ERA5 reanalysis. The work explicitly treated structured missing data, such as persistent cloud cover, and was supported by multi-terabyte data pipelines with distributed, mixed-precision training on HPC. The project produced the models listed below.</small>
  - <small>**PollutionNet**: a vision transformer framework for climatological assessment of NO<sub>2</sub> and SO<sub>2</sub> using satellite-ground data fusion. (**[Paper](https://doi.org/10.1007/s00704-026-06376-8)**)</small>
  - <small>**Efficient Vision Transformer for O<sub>3</sub>**: near-surface ozone prediction that stays robust when satellite observations are missing. (**[Paper](https://doi.org/10.1109/igarss55030.2025.11244019)**)</small>
  - <small>**FewShot-Airnet**: temporal 2D-variation modelling for air pollution forecasting with few-shot learning. (**[Paper](https://doi.org/10.1109/igarss55030.2025.11243753)**)</small>
  - <small>**NES-VIT-NET**: a nested vision transformer network for near-surface NO<sub>2</sub> estimation. (**[Paper](https://doi.org/10.1109/igarss53475.2024.10640856)**)</small>
  - <small>**CombineDeepNet**: a deep network for multistep prediction of near-surface PM2.5 concentration. (**[Paper](https://doi.org/10.1109/JSTARS.2023.3333269)**)</small>
  - <small>**GMNF-VAE**: a Gaussian-mixture nested factorial variational autoencoder for multivariate air pollution prediction. (**[Paper](https://doi.org/10.1109/LGRS.2024.3416343)**)</small>
  - <small>**NeSNet**: a deep network for estimating near-surface pollutant concentrations from satellite data. (**[Paper](https://doi.org/10.1109/JSTARS.2023.3244719)**)</small>
  - <small>**NeSDeepNet** and **BiLSTM-BiGRU**: fusion networks for multistep forecasting of near-surface air pollutants. (**[Paper 1](https://doi.org/10.1109/piers59004.2023.10221327)**) (**[Paper 2](https://doi.org/10.1109/igarss52108.2023.10282742)**)</small>

- <small>**TinyNina: Edge-AI Satellite Super-Resolution for Air Quality Monitoring** (PhD project): A resource-efficient edge-AI framework that uses intra-image satellite super-resolution to enable sustainable, low-cost air quality monitoring. (**[Preprint](https://arxiv.org/abs/2604.04445)**)</small>

- <small>**Deep Learning for Environmental Prediction from Satellite and Radar Data** (Junior Research Fellow, NIT Jamshedpur, Dec 2020 – Aug 2022): I designed deep learning models for air quality and time-series prediction from satellite, radar and meteorological data, applying computer vision techniques for spatial feature extraction. The work also covered data curation, quality control and pipeline engineering for large geospatial datasets, plus experimental benchmarking.</small>

### Collaborative Remote Sensing Projects

- <small>**Water Body Classification Using Spectral Indices**: an attention-based ResNet for accurate water body classification from spectral indices. (**[Paper](https://doi.org/10.1109/cisp-bmei64163.2024.10906094)**)</small>
- <small>**Use-Net**: a satellite data-based framework for optimising billboard placement in urban areas. (**[Paper](https://doi.org/10.1109/igarss53475.2024.10641669)**)</small>
- <small>**Spatial-Temporal-TES**: short-term temperature forecasting from reanalysis data. (**[Paper](https://doi.org/10.1109/ei259745.2023.10512739)**)</small>
- <small>**Rainfall Prediction**: a multidimensionality reduction approach to rainfall forecasting. (**[Paper](https://doi.org/10.1109/piers59004.2023.10221498)**)</small>

### IoT, Mine Safety & Computer Vision (CSIR-CIMFR, Dec 2018 – Oct 2020)

- <small>**Digital Mine Using Internet of Things (IoT)**: As Research Engineer, I was technical lead for a deployed IoT-based predictive protection system for underground mines. I built the Digital Mine software with Django and Python and took the system from requirements and design through sensor calibration, drift compensation and field validation to operational handover. The system included:</small>
  - <small>gas monitoring and prediction (CH<sub>4</sub>, NO<sub>2</sub>, SO<sub>2</sub> and others) using deep learning (**[Paper](https://doi.org/10.1016/j.psep.2021.06.005)**) (**[Paper](https://doi.org/10.1007/s00500-021-06261-8)**);</small>
  - <small>fire status and explosibility prediction for sealed-off areas (**[Paper](https://doi.org/10.1016/j.psep.2020.12.019)**);</small>
  - <small>IoT-based miner tracking, miner health monitoring, strata monitoring and machine health prediction.</small>

  <small>I presented the findings to a national ministry, safety regulators and mine operators. The work led to the granted Indian patent *Digital Mine Using Internet of Things* (No. 580680, 2026).</small>

- <small>**Secure Wireless Voice Communication for Underground Mines**: a deep CNN-based secure voice communication system built with Raspberry Pi, MATLAB and Simulink. (**[Paper](https://doi.org/10.1007/s12652-020-02700-w)**)</small>

- <small>**Secure Machine Learning for Encrypted IoT Data**: decision tree twin support vector machine training and classification on encrypted IoT data via a blockchain platform. (**[Paper](https://doi.org/10.1002/cpe.6264)**)</small>

- <small>**Vision Enhancement for Foggy Weather using Computer Vision**: improving visibility in fog using real-time image stitching (OpenCV), real-time vision enhancement algorithms and YOLO-based object detection. Potential applications include autonomous driving, surveillance and safety systems.</small>

### Earlier Projects

- <small>**Location Tracking System for Indoor Environment (LTIE)**: an indoor location tracking system, granted as Indian Patent No. 465850 (2023).</small>
- <small>**WLAN-Based Energy-Efficient Smart City Design**: an energy-efficient smart city network design using WLAN. (**[Paper](https://doi.org/10.1007/s00542-017-3530-6)**)</small>

<small>Update: 2026/09/23</small>
