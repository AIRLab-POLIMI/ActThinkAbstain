# Act, Think or Abstain: Complexity-Aware Adaptive Inference for Vision-Language-Action Models

## Overview
Current research on Vision-Language-Action (VLA) models predominantly focuses on enhancing generalization through established reasoning techniques. While effective, these improvements invariably increase computational complexity and inference latency. Furthermore, these mechanisms are typically applied indiscriminately, resulting in the inefficient allocation of resources for trivial tasks while simultaneously failing to provide the uncertainty estimation necessary to prevent catastrophic failure on out-of-distribution tasks. Inspired by human cognition, we propose an adaptive framework that dynamically routes VLA execution based on the complexity of the perceived state. Our approach transforms the VLA's vision-language backbone into an active detection tool by projecting latent embeddings into an ensemble of parametric and non-parametric estimators. This allows the system to execute known tasks immediately (\textit{Act}), reason about ambiguous scenarios (\textit{Think}), and preemptively halt execution when encountering significant physical or semantic anomalies (\textit{Abstain}). In our empirical analysis, we observe a phenomenon where visual embeddings alone are superior for inferring task complexity due to the semantic invariance of language. Evaluated on the LIBERO and LIBERO-PRO benchmarks as well as on a real robot, our vision-only configuration achieves 80\% F1-Score using as little as 5\% of training data, establishing itself as a reliable and efficient task complexity detector. 

> [!WARNING]
> The manuscript is under review, and the source code and dataset will be released after publication.

> [!CAUTION]
> Temporary Citation (Preprint) - ArXiv: 
>

**Authors**: [Riccardo Andrea Izzo](mailto:riccardo.izzo@mail.polimi.it), [Gianluca Bardaro](mailto:gianluca.bardaro@polimi.it) and [Matteo Matteucci](mailto:matteo.matteucci@polimi.it)  
**Location**: [**AIRLab** (The Artificial Intelligence and Robotics Lab of Politecnico di Milano)](https://airlab.deib.polimi.it/)

