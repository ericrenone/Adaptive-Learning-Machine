# Dual-Path Convergence: KL Drift vs Gain Control

Real-time visualization comparing two distinct optimization strategies that both minimize free energy through different mechanisms.

## Overview

This simulation demonstrates how gradient descent can achieve the same objective (minimizing KL divergence) through two fundamentally different paths:

- **Purification Path**: Direct geometric correction toward the target
- **Annealing Path**: Adaptive gain scaling that decays learning sensitivity


## What It Shows

The visualization tracks three key metrics across 100 optimization steps:

1. **Information Drift (KL Divergence)** - Distance from true distribution
2. **Prediction Loss** - Mean squared error on sampled data  
3. **Sensitivity Parameter α** - Adaptive learning gain (annealing path only)




