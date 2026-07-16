# Simulation and Analysis

## Introduction

Functional simulation was carried out for the 2×2, 4×4, and 8×8 stages. The 16×16 stage was partially executed due to tooling and integration issues, so its simulation results are not independently verified. Additional analysis and timing information referenced in this document are drawn from published IEEE literature.

Related simulation images are available in the `images` folder.

---

## Functional Simulation

Functional simulation helps verify whether the multiplier produces the expected output for different input combinations.

The waveforms for the 2×2, 4×4, and 8×8 stages, executed independently, show the relationship between input signals and the generated output during simulation.

---

## Timing Analysis

Since independent timing analysis was not performed for the final 16×16 design, RCA and CLA behavior was studied through reference material and trends reported in published IEEE papers (see the `images` folder for referenced graphs).

---

## Observation

The analysis shows that different adder architectures can influence multiplier performance. However, the overall result depends on the complete multiplier structure and implementation approach.

---

## Summary

Simulation waveforms for the 2×2, 4×4, and 8×8 stages (executed independently) were used to verify functional behavior. Analysis of RCA vs. CLA performance trends, along with the graphs in the `images` folder, is based on published IEEE reference material rather than independently generated results.