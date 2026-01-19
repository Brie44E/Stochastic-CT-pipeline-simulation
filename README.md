# Stochastic-CT-pipeline-simulation


# Phase Transition Estimator

This repository contains the code used for my Master’s thesis at the University of St. Gallen (HSG).

The thesis investigates how historical data can be used to estimate transition probabilities between sequential development stages and to derive expected outcomes in multi-stage processes. The primary application explored in the thesis is drug development, but the underlying methods are more general and can be applied to other staged decision or innovation pipelines.

---

## Overview

The work focuses on estimating empirical transition probabilities between discrete stages using historical observations and combining these estimates into a coherent model of overall outcome likelihoods.

Key elements include:

* Stage-to-stage transition probability estimation
* Handling of censored and incomplete historical data
* Aggregation of conditional probabilities across multiple stages
* Scenario and sensitivity analysis based on historical transition behavior

The repository is intended to support transparency and reproducibility of the methodology rather than to serve as a production-ready software package.

## Methodological Notes

The estimation approach is based on historical frequency analysis of observed transitions between predefined stages. Key assumptions include:

* Stationarity of transition probabilities within defined time windows
* Independence of stage transitions conditional on reaching a given stage
* Consistent stage definitions across observations

These assumptions are discussed and critically evaluated in the written thesis.

---

## Data Availability

The original datasets used in the thesis cannot be shared publicly due to confidentiality constraints.

This repository therefore:

* Does **not** include raw data
* Includes all preprocessing, modeling, and analysis code
* Assumes that users provide their own data following the same schema

Where appropriate, example schemas and comments in the code indicate the expected data structure.

---

## Scope and Limitations

This repository:

* Is designed for academic transparency
* Prioritizes methodological clarity over software abstraction
* Does not aim to provide a general-purpose prediction tool

Results and interpretations should be understood in the context of the thesis and its assumptions.

---

## Citation

If you reference this work, please cite the corresponding Master’s thesis.

A formal citation file may be added in the future.

