# InSAR Edge-Risk Unwrapping

Project repository for **A Solver-Aligned Hybrid Framework for InSAR Phase Unwrapping via Edge Ambiguity-Risk Learning**.

## Overview

This work combines learned edge-level ambiguity-risk prediction with classical InSAR phase-unwrapping solvers. A symmetric predictor uses wrapped phase to estimate local event-risk scores, which are mapped to weights and supplied to PUMA-style graph cuts, minimum-cost flow (MCF), and SNAPHU through solver-specific adapters. The same trained predictor is reused across the three solver interfaces without retraining.

## Code Availability

The source code and pretrained model will be made publicly available in this repository upon publication of the paper.
