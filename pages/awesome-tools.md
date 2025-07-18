---
title: Awesome Tracking Tools
# layout: home
nav_order: 4
description: ""
# permalink: /
---

# {{ page.title }}

{: .note-title }
> Coming Soon!
>
> To contribute to our awesome list, please open an issue or PR on our [website repo](https://github.com/live-image-tracking-tools/live-image-tracking-tools.github.io).

A curated list of open‑source and commercial software, libraries, datasets, and resources for live‑cell tracking, lineaging, and trajectory analysis in bioimage data.

> **Legend**  
> 🐍 = Python 🔬 = Fiji/ImageJ 📦 = Commercial 💻 = Web/Other

## Libraries

- **[btrack](https://github.com/quantumjot/btrack)** 🐍 — Bayesian multi‑object tracker for crowded scenes.
- **[trackpy](https://github.com/soft-matter/trackpy)** 🐍 — Flexible particle tracking toolkit for 2D/3D trajectories.
- **[Motile](https://github.com/funkelab/motile_tracker)** 🐍 — Integer‑linear‑programming library for globally optimized tracking.
- **[LapTrack](https://github.com/yfukai/laptrack)** 🐍 — Linear‑assignment‑problem based tracker with tunable costs.
- **[TrackAstra](https://github.com/weigertlab/trackastra)** 🐍 — Transformer‑based cell tracker for segmented masks.
- **[DeepCell‑tracking](https://github.com/vanvalenlab/deepcell-tracking)** 🐍 — Deep learning cell tracking and lineage building.
- **[STracking](https://github.com/sylvainprigent/napari-stracking)** 🐍🔬 — Modular tracking pipelines with napari GUI.
- **[PyUAT](https://github.com/JuBiotech/PyUAT)** 🐍 — Uncertainty‑Aware Tracking for microbial cells.
- **[Ultrack](https://github.com/royerlab/ultrack)** 🐍🔬 — Scalable 2D/3D tracking under segmentation uncertainty.

## Applications / GUIs

- **[TrackMate](https://github.com/trackmate-sc/TrackMate)** 🔬 — Everyday object tracking plugin for Fiji.
- **[Mastodon](https://github.com/mastodon-sc)** 🔬 — Next‑generation interactive tracking for large datasets.
- **[ilastik](https://www.ilastik.org/)** 💻 — Interactive machine‑learning workflows including tracking.
- **[CellProfiler + Tracer](https://cellprofiler.org/tracer)** 🐍🔬 — High‑throughput analysis with trajectory QC.
- **[Cell‑ACDC](https://github.com/SchmollerLab/Cell_ACDC)** 🐍 — Real‑time segmentation & cell cycle‑aware tracking GUI.
- **[CellTracker](https://github.com/WangLabTHU/CellTracker)** 🐍 — End‑to‑end GUI toolbox for segmentation and tracking.
- **[Lineage Mapper](https://github.com/usnistgov/Lineage-Mapper)** 🔬 — Overlap‑based tracker producing detailed lineages.
- **[CellMAPtracer](https://github.com/ocbe-uio/CellMAPtracer)** 📊 — MATLAB GUI for long‑term proliferative cell tracking.
- **[Imaris](https://imaris.oxinst.com/products/imaris-for-cell-biologists)** 📦 — Commercial 3D/4D visualization & tracking suite.
- **[arivis Vision4D](https://www.zeiss.com/microscopy/en/products/software/arivis-pro.html)** 📦 — Scalable big‑data tracking with VR proofreading.
- **[DeepSea](https://github.com/abzargar/DeepSea)** 🐍 — Residual U‑Net based joint segmentation & tracking.
- **[ELEPHANT](https://github.com/elephant-track)** 🔬🐍 — Incremental deep‑learning 3D tracking on Mastodon.
- **[LIM Tracker](https://github.com/LIMT34/LIM-Tracker)** 🔬 — Seamless auto, pattern‑matching & manual tracking plugin.
- **[Usiigaci](https://github.com/oist/Usiigaci)** 🐍 — Mask‑R‑CNN + trackpy pipeline for label‑free tracking.
- **[PhagoSight](https://github.com/phagosight/phagosight)** 📊 — MATLAB toolbox for immune‑cell tracking in 3D.
- **[MetaMorph](https://imagxcell.com/metamorph/)** 📦 — Long‑standing commercial acquisition & tracking suite.
- **[NIS‑Elements](https://www.nisoftware.net/NikonSaleApplication/Help/Docs-AR/eng_ar/tracking.advanced.html)** 📦 — Nikon software module for 2D/3D object tracking.
- **[MoMA](https://github.com/fjug/MoMA)** 🔬 — Analyzer for mother‑machine bacterial lineage movies.

## Annotators & Editors

- **[DeepCell Label (Caliban)](https://github.com/vanvalenlab/deepcell-label)** 💻 — Web‑based segmentation + tracking labeler.
- **[MTrackJ](https://imagej.net/plugins/mtrackj)** 🔬 — Manual multi‑dimensional motion tracking.
- **[Traxtile](https://github.com/braunb/traxtile-public)** 🐍 — Interactive GUI for reviewing & fixing tracks.
- **[CeLaVi](https://academic.oup.com/nar/article/49/W1/W80/6270768)** 💻 — Interactive web lineage tree visualizer.

## Benchmarks & Metrics

- **[Cell Tracking Challenge](https://celltrackingchallenge.net/)** 💻 — Gold‑standard benchmark datasets & metrics.
- **[traccuracy](https://github.com/live-image-tracking-tools/traccuracy)** 🐍 — Python implementation of CTC metric suite.

## Tutorials & Guides

- **[Tracking in napari](https://focalplane.biologists.com/2023/06/01/tracking-in-napari/)** — Blog walkthrough of napari tracking plugins.
- **[EPFL Image Analysis Field Guide – Tracking](https://imaging.epfl.ch/field-guide/sections/detection_and_tracking/index.html)** — Practical notebook on object detection & tracking.
- **[TrackMate documentation](https://imagej.net/plugins/trackmate/)** — Comprehensive protocols for TrackMate.
- **[CellProfiler Tracking tutorial](https://cellprofiler.org/tracer)** — Step‑by‑step building of CellProfiler pipelines.
- **[ilastik tracking workflow tutorial](https://www.ilastik.org/documentation/tracking)** — Official guide for automatic tracking in ilastik.

## Datasets

- **[Cell Tracking Challenge datasets](https://celltrackingchallenge.net/datasets/)** — 2D/3D annotated sequences for benchmarking.
- **[DeepSea dataset](https://deepseas.org/datasets/)** — 47 time‑lapse sequences across three cell types.
- **[Phase‑Contrast Myoblast Lineage dataset](https://osf.io/ysaq2/)** — 48 long‑term phase‑contrast movies with ground truth.

## Utilities & Formats

- **[GEFF](https://github.com/live-image-tracking-tools/geff)** 🐍 — Standardized graph exchange format for tracking data.
- **[CellTracksColab](https://github.com/CellMigrationLab/CellTracksColab)** 🐍 — Colab notebooks for consolidating & analyzing tracks.
- **[inTRACKtive](https://github.com/royerlab/inTRACKtive)** 💻 — Browser‑based interactive exploration of large lineage data.

