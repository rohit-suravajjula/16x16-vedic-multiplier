# Design Approach

## Introduction

The 16×16 Vedic Multiplier was designed using a hierarchical approach. Instead of creating one large circuit, the design starts with smaller multiplier blocks and gradually builds the complete system.

This approach makes the design easier to understand and verify during each stage of development.

Related block diagrams are available in the `images` folder.

---

## Design Workflow

The multiplier is developed in the following order:

2×2 Multiplier  
↓  
4×4 Multiplier  
↓  
8×8 Multiplier  
↓  
16×16 Multiplier

---

## RCA and CLA

Two different adder designs were considered in this project.

### Ripple Carry Adder (RCA)

The RCA passes the carry output from one stage to the next. It is simple to design, but the carry has to travel through each stage before the final result is produced.

---

### Carry Lookahead Adder (CLA)

The CLA calculates carry signals differently from the RCA. This helps reduce carry calculation time in many designs, although the overall performance depends on the complete implementation.

---

## Summary

The project follows a modular design approach where smaller multiplier blocks are combined to create the final 16×16 multiplier. RCA and CLA based architectures were studied and compared based on the available design analysis information.