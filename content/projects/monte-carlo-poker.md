---
title: "Monte Carlo Poker Evaluator"
summary: "SIMD-accelerated poker hand evaluator running millions of simulations"
description: ""
cover: "/img/poker.jpg"
coverGif: "/img/poker.gif"
coverAlt: "Monte Carlo Poker Evaluator"
weight: 4
---

## Overview

A high-performance poker hand evaluator that uses Monte Carlo simulations to calculate hand equity. This personal project focused on pushing C++ performance to its limits through low-level CPU optimizations.

## Technical Details

The evaluator leverages SIMD instructions (SSE/AVX) to accelerate hand evaluation, achieving a 1.5x speedup over the scalar baseline implementation. The system is optimized to execute millions of Monte Carlo simulations efficiently, using careful memory layout and CPU cache optimization techniques to maximize throughput.

---

**Technologies:** C++, SSE/AVX SIMD  
**Repository:** [GitHub Link](https://github.com/BenjaminEmag/MonteCarloPoker)
