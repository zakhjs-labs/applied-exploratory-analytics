# A/B Testing

This section of the repository contains a full pipeline for A/B testing — from initial data exploration to advanced statistical techniques for experiment analysis and optimization.

## Contents

### 🧹 01. Data Exploration

-   `01_data_exploration_pizza_store.ipynb`  
    Exploratory analysis of session-level data from an online pizza store. Includes conversion funnels, top-selling products, time-to-purchase metrics, and retention analysis.

### 🧱 02. A/B Testing Platform

-   `02_ab_testing_platform.ipynb`  
    Architectural prototype of a modular A/B testing system, focusing on the `DataService` component.

### 🧪 03. Hypothesis Testing

-   `03_hypothesis_testing.ipynb`  
    Core statistical tests used in A/B testing: t-tests, z-tests, proportions testing, and test assumptions.

### 📏 04. Minimum Detectable Effect (MDE)

-   `04_mde.ipynb`  
    Calculation of the smallest effect size detectable given fixed sample size, alpha, and power.

### 🧰 05. Test Design

-   `05_design_testing.ipynb`  
    Practical guidance on selecting test duration, sample size, and choosing between one- vs two-tailed tests.

### 📊 06. Bootstrap & Confidence Intervals

-   `06_bootstrap_and_ci.ipynb`  
    Non-parametric bootstrap methods to estimate confidence intervals for various metrics.

### 🎯 07. Variance Reduction

-   `07_variance_reduction.ipynb`  
    Techniques such as pre-experiment covariates and regression adjustment to increase test sensitivity.

### 🧬 08. Stratification

-   `08_stratification.ipynb`  
    Stratified sampling to ensure balanced experiment groups and reduce variability.

### 🔧 09. CUPED

-   `09_cuped.ipynb`  
    Implementation of the CUPED technique to reduce variance using pre-experiment metrics.

### 🧪 10. Multiple Testing

-   `10_multiple_testing.ipynb`  
    Controlling false discovery rate (FDR) and family-wise error rate (FWER) with methods like Bonferroni and Benjamini-Hochberg.

### 🔀 11. Split System

-   `11_split_system.ipynb`  
    Group splitting strategies: randomization, hash-based assignment, and considerations for consistency and bias.

### 📐 12. Linearization

-   `12_linearization.ipynb`  
    Transforming ratio metrics (e.g. revenue per user) into linearized forms for valid hypothesis testing.

---

## 🔧 Platform Components (In Progress)

The final goal is to build a reusable A/B testing framework composed of:

-   `DataService` — manages access to raw experiment data
-   `MetricsService` — computes experiment metrics
-   `ExperimentsService` — performs statistical testing and evaluation
-   `SplittingService` — assigns users into treatment and control groups

Currently, the `DataService` is under development.

---

## 📁 Data

All relevant datasets are stored in the [`/data`](../data/) folder and are available via links.
