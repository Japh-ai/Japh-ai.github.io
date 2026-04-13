---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
[Download PDF version](/files/1pg_cv.pdf){: .btn .btn--inverse}

{% include base_path %}

Education
======
* **Ph.D. in Seismology & Machine Learning**, Charles University, Prague, Czech Republic, 2021 – Present
  * Supervisor: Christian Sippl. ERC project MILESTONE.
  * Thesis focused on deep learning for time-series data: earthquake detection, phase association, and earthquake early warning.
* **M.Sc. in Earth Sciences — Applied Geophysics**, CICESE, Ensenada, Mexico, 2017 – 2019
  * Thesis: Structure of a sector of the North Altar Basin, Sonora, with 2D seismic reflection data.
* **B.Sc. in Geosciences Engineering**, Instituto Tecnológico de Ciudad Madero, Tamaulipas, Mexico, 2012 – 2017

Work experience
======
* **2021 – Present**: Researcher (Ph.D. candidate)
  * Institute of Geophysics, Czech Academy of Sciences, Prague, Czech Republic
  * Designed and trained deep-learning models (RNNs, CNNs, Transformers) for time-series classification, clustering, and regression on multi-sensor seismic data.
  * Built end-to-end data pipelines converting raw waveforms into ML-ready datasets; applied augmentation techniques to improve domain robustness.
  * Re-implemented and extended a Transformer-based probabilistic EEW model in PyTorch from TensorFlow.
  * Built custom evaluation pipelines (precision–recall, AUC, F1, lead-time metrics) and benchmarking frameworks.
  * Applied transfer learning and fine-tuning on limited real-world datasets; ensured reproducibility via Hydra and Git.
  * Supervisor: Christian Sippl

* **Oct – Dec 2023**: Visiting Research Fellow
  * Universidad de Concepción, Concepción, Chile
  * Applied deep-learning models to refine earthquake catalogues of Northern Chile, including benchmarking of multiple algorithms under realistic noise conditions.

* **2020 – 2021**: IT Trainee
  * Tata Consultancy Services, Mexico
  * Supported Java/JavaScript web applications on Linux and Windows servers.

* **2017 – 2019**: Data Processing & Interpretation Geophysicist
  * CICESE, Ensenada, Mexico
  * Processed and interpreted 2D reflection seismic data; characterised tectonostratigraphic features and correlated major faults with well-log data.
  * Results published in Pure & Applied Geophysics (2022).
  * Supervisor: Mario González-Escobar

Skills
======
* **Languages**: Python, SQL, Bash
* **ML / DL**: PyTorch, Scikit-learn, NumPy, Pandas, Matplotlib — Deep Learning (CNNs, Transformers, RNNs), Time-Series Modeling & Analysis, Transfer Learning, Data Augmentation, Model Benchmarking, Probabilistic Modeling
* **Data Engineering & HPC**: Data Pipelines, Large-scale Dataset Processing, Slurm, GPU Training, Linux, HPC Clusters
* **MLOps & Experiment Management**: Hydra, Git
* **Tools**: VS Code, LaTeX, ObsPy

Relevant Training
======
* Practical Deep Learning on HPC (CSC, LUMI Supercomputer, Finland, 2025)
* Introduction to Deep Learning with PyTorch (2024)
* AI & ML for Geosciences (Barcelona Supercomputing Center, 2024)
* Machine Learning (Stanford/Coursera, 2020)
* Data Science with Python (SciData, 2020)
* ML Essentials for Seismic Interpretation (Geophysical Insights, 2019)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Field Experience
======
* **Broadband Array Deployment**, Finland, 2025 — 35-station broadband array deployment (co-authored GFZ dataset).
* **Seismic Stations**, Chile, 2023 — Field deployment of seismic stations in Northern Chile.
* **MT Surveys**, Norway, 2021 — Magnetotelluric data acquisition near Røros.

Languages
======
* Spanish (Native)
* English (Fluent — TOEFL iBT 95)
