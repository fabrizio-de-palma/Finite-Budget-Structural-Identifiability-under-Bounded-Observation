# Finite-Budget Structural Identifiability under-Bounded Observation
This repository contains the paper and artifact for:  
"Finite-Budget Structural Identifiability under Bounded Observation"  
Official archived version on Zenodo:  
[https://doi.org/10.5281/zenodo.18736348](https://doi.org/10.5281/zenodo.18736348) 

# Abstract
We study the problem of structural regime identification under finite observational scale and finite computational budget. We consider a stochastic or deterministic process observed through a representation map at a given scale, generating an observable sequence. We introduce the notion of a novelty curve, defined as the number of distinct observations encountered up to a given time, and show that its finite-sample behavior encodes structural information about the underlying regime.

Our main result establishes a non-asymptotic equivalence between finite-budget identifiability and observational separability. In particular, we derive: a sufficient condition for regime identification expressed through a critical identification time depending on structural latency, effective integration cost, and the maximal novelty gap between regimes; a matching lower bound showing that without positive separability, no test can outperform random guessing; the existence of a maximal identifiable observational scale under finite budget constraints; and a structural allocation principle determining the optimal resolution compatible with identifiability.

The analysis reveals a phenomenon of resolution-induced collapse: increasing observational granularity may destroy identifiability when computational resources are fixed. Identification limits therefore arise not only from computational complexity, but from structural properties of observable novelty growth.

We provide explicit regime constructions illustrating latency-dominated, estimation-dominated, and separation-dominated domains. A companion software artifact is provided separately and linked via DOI, enabling empirical estimation of the structural quantities introduced in the paper.

# Contents

- 📄 [Paper](paper.pdf)
- 🧩 [Artifact](structural_identifiability_artifact.zip)

# Keywords
finite-budget inference, structural identifiability, observational scale, novelty growth, theoretical machine learning
