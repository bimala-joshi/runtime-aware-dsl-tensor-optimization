# Runtime-Aware Optimization Selection in a Lightweight DSL for Tensor Operations

## Project Overview

This project presents a lightweight Python-based domain-specific language (DSL) framework for runtime-aware optimization selection in tensor operations. The system evaluates multiple execution strategies and determines whether optimization is beneficial for a given workload.

The framework supports tensor workloads such as:
- Elementwise computation chains
- Matrix multiplication

The system compares multiple execution strategies including:
- Baseline execution
- Fused execution
- Tiled execution

The main goal of the project is to demonstrate that optimization is workload-dependent and should not always be applied universally.

---

## Features

- Lightweight embedded DSL for tensor operations
- Heuristic-based optimization prediction
- Runtime-aware strategy selection
- Runtime validation of candidate strategies
- Correctness verification against baseline execution
- Performance comparison across execution modes
- Explainable optimization decision generation

---

## Technologies Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Google Colab

---

## Repository Contents

| File | Description |
|---|---|
| `CostAware_DSL_Tensor_Optimization.ipynb` | Main project notebook |
| `baseline_vs_dsl_selected.png` | Runtime comparison figure |
| `speedup_vs_baseline.png` | Speedup comparison figure |
| `strategy_comparison.png` | Strategy comparison visualization |
| `final_results_summary.csv` | Summary experiment results |
| `final_results_detailed.csv` | Detailed runtime results |
| `optimization_benefit_analysis.csv` | Optimization benefit analysis |
| `strategy_comparison.csv` | Strategy comparison results |
| `adaptive_vs_baselines.csv` | Adaptive vs baseline comparisons |
| `average_runtime_summary.csv` | Average runtime summary |

---

## How to Run

1. Open the notebook:
   `CostAware_DSL_Tensor_Optimization.ipynb`

2. Run all notebook cells sequentially.

3. The notebook will:
   - Generate tensor workloads
   - Evaluate candidate strategies
   - Measure runtimes
   - Validate correctness
   - Generate result tables and figures

---

## Expected Outputs

The notebook generates:
- Runtime comparison tables
- Speedup analysis
- Optimization decision analysis
- PNG figures
- CSV result files

---

## Experimental Environment

Experiments were conducted using:
- Google Colab
- CPU-based NumPy execution environment

Runtime measurements may vary slightly due to shared cloud execution environments.

---

## Author

Bimala Joshi  
University of Wisconsin–Milwaukee

---

## Course Information

CS 790/657 – Domain Specific Programming for AI
