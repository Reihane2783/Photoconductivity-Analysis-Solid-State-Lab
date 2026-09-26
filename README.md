# Photodetector and Malus's Law Analysis

A Python-based analysis of experimental photodetector data, including intensity–voltage measurements and verification of Malus's law through the relationship between light intensity and `cos²(theta)`.

## Overview

This project analyzes two experimental datasets:

1. **Intensity vs. Voltage**
2. **Intensity vs. cos²(theta)**

Linear regression is applied to both datasets to determine their best-fit relationships.

## Analysis

### 1. Intensity vs. Voltage

The measured voltage (`V1`) and current/intensity (`I1`) are fitted using a linear model:

```text
I = aV + b
