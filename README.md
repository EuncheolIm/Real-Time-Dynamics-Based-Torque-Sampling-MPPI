# Real-Time Dynamics-Based Torque-Sampling MPPI for Compliant and Force-Aware Manipulation

Project page for the IEEE/RSJ IROS 2026 paper.

**Authors:** Euncheol Im, Taehyun Kim, Yonghwan Oh, Myo-Taeg Lim, Yisoo Lee†
(† corresponding author) — KIST, Korea University.

## Overview

A torque-sampling MPPI framework that solves full rigid-body dynamics inside a
real-time MPC loop, enabling compliant and force-aware manipulation at a 166 Hz
solver update rate with a 0.18 s prediction horizon on a 7-DoF Franka FR3.

## Local preview

```bash
cd Real-Time-Dynamics-Based-Torque-Sampling-MPPI
python3 -m http.server 8000
# open http://localhost:8000
```

## Assets

Videos (in place):

- `static/videos/Total_Video_materials_V5.mp4` — teaser (full materials)
- `static/videos/hybrid_force_freespace.mp4` — free-space hybrid motion–force control
- `static/videos/hybrid_force_contact_with_surface.mp4` — curved-surface contact
- `static/videos/dynamic_obstacle_avoidance.mp4` — dynamic obstacle avoidance
- `static/videos/compare_with_baseline.mp4` — vs. Single-Instance Sampling MPPI (T-RO 2025)

Figures (in place, converted from PDF):

- `static/images/structure.png` — full framework / control structure (from `Structure.pdf`)
- `static/images/prbdl.png` — GPU-parallelized dynamics solver block (from `prbdl.pdf`)

## TODO before publishing

- Real links: **Paper** (DOI/arXiv), **Video** (YouTube), footer PDF icon — currently `#` placeholders.

Template borrowed from [Nerfies](https://nerfies.github.io).
