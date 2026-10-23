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

Presented with Jordi Cipriano (CIMNE BEE Group) under the slide title *Physics-Regularized State-Space Models for Space-Time Super-Resolution of Vortex-Dominated Flows*.

A shared encoder-decoder with one interchangeable temporal stage (UNet, ConvLSTM, Transformer, Mamba) is trained with a divergence penalty and tested on a moving-cylinder wake benchmark (Decuyper, De Troyer & Runacres, VUB, 2024). The physics penalty brings the velocity divergence below the data's own discretization floor. Without a temporal stage, multi-step reconstruction collapses. The selective state-space stage gives the lowest error.
