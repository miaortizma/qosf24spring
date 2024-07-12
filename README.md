# qsof24spring
Quantum Clustering project for QSOF 2024 Spring mentorship program

## Overview
This project contrasts classical clustering techniques with quantum-inspired clustering using the Schrödinger equation and quantum clustering via the D-Wave quantum annealer to evaluate efficiency and accuracy on the Crab and Cancer datasets.

## Getting Started / Instructions

## Results

### Impact of Sigma
- Lower sigma values tend to create more localized clusters, which can capture finer details.
- Higher sigma values result in broader clusters, which are more robust to noise but may overlook finer details.
- Scanning over sigma values provides insight in the appropriate choice of sigma value, where the number of clusters is stable.

### Optimization Performance
- The Conjugate-Gradient and Broyden-Fletcher-Goldfarb-Shanno algorithms show reliable performance.
- Various optimization algorithms result in consistent trend in the number of clusters as a function of sigma values, increasing the confidence in the choice of sigma value. 

![numClusters_vs_sigma_crab](results/crab_numClusters_vs_sigma_All-methods_pca1-pca2.pdf)

## Conclusion

## Contact
