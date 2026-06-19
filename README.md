# RECURIA Core

## Overview

RECURIA is a mathematically grounded feature engineering framework designed to model instability, transitions, and dynamic state changes in complex systems.

Rather than optimizing a domain-specific model, RECURIA investigates whether a common mathematical representation of instability can generalize across healthcare, environmental systems, transportation, energy forecasting, and retail demand prediction.

The framework was evaluated across multiple domains using standard machine learning baselines and reproducible pipelines.

---

## Research Question

Can a common mathematical representation of instability and transition dynamics provide useful predictive structure across fundamentally different systems?

---

## Core Mathematical Quantities

### Instability Magnitude

η represents the local magnitude of change within a system.

### Oscillatory Transition State

r = η(sinθ + cosθ)

This quantity combines instability and directional phase information.

### Curvature

r'' captures acceleration and curvature of system behavior.

### Transition Interaction Term

m = ηrr''

This interaction term is intended to characterize moments of transition, instability accumulation, and structural change.

---

## Domains Evaluated

### Healthcare

* Clinical Deterioration Prediction
* Multiple Sclerosis Conversion
* Autoimmune Disorder Classification

### Environmental Systems

* Groundwater Stress Forecasting
* Solar Activity Prediction

### Demand Forecasting

* Retail Demand Forecasting
* Bike-Sharing Demand Forecasting
* Residential Energy Forecasting

---

## Repository Structure

```text
src/
notebooks/
results/
data/
```

---

## Research Philosophy

The objective of RECURIA is not to replace machine learning models.

Instead, it explores whether mathematically interpretable features can provide useful structure for understanding transitions in complex systems.

---

## Author

Ishmaelina Okorley

Research interests:

* Mechanistic Interpretability
* AI Safety
* Dynamic Systems
* Time-Series Analysis
* Feature Engineering
* Healthcare AI
