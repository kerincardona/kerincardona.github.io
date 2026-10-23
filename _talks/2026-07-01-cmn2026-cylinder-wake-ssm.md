---
title: "State-Space Models Outperform UNet and ConvLSTM in Long-Horizon Autoregressive Prediction of Cylinder Wake Flows"
collection: talks
type: "Talk"
talk_type: "Talk"
permalink: /talks/2026-07-01-cmn2026-cylinder-wake-ssm
venue: "Congress on Numerical Methods in Engineering (CMN 2026)"
date: 2026-07-01
location: "Gijón, Spain"
---

Benchmark of convolutional UNet, ConvLSTM and Mamba-based (MambaUNet) models on two-dimensional cylinder wake flow at Re = 200, across three downscaling factors and several random seeds. All three reach similar one-step accuracy, but their autoregressive rollouts diverge: UNet errors explode over 15 steps, while the state-space model stays stable across seeds.
