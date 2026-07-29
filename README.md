# Quantum Machine Learning Research

Welcome to the repository hosting my academic research on quantum computing applications in machine learning. This repository contains the manuscripts, supplementary materials, and related code for two recent papers.

## 📄 Publications

### 1. Quantum Feature Engineering for Credit Default Prediction: When and Why IQP Circuits Help Linear Classifiers
* **Authors:** Menachem Finkelstein, Diana Levy, and Sarel Cohen[cite: 1].
* **Status:** Submitted to IEEE]
* **Summary:** This paper explores whether Instantaneous Quantum Polynomial-time (IQP) circuits can produce features that improve linear classifiers for tabular credit default prediction[cite: 1]. 
* **Key Findings:** Using the UCI Default of Credit Card Clients dataset, appending 16 IQP features to a Logistic Regression model raised the F1 score from 0.462 to 0.517[cite: 1]. The study demonstrates that this quantum advantage outperforms Kernel PCA at an equal feature budget and is specific to linear expressivity, as tree-based and kernel methods did not see similar benefits[cite: 1].
* **File:** `Quantum Feature Engineering for Credit Default Prediction When and Why IQP Circuits Help Linear Classifiers.pdf`

---

### 2. Quantum-Inspired Hybrid Neural Networks for Neural Decoding: A Controlled Ablation Study of Learnable Quantum Sidecar Integration
* **Authors:** Diana Levy, Menachem Finkelstein, Peter Chin, Eilon Vaadia, and Sarel Cohen[cite: 2].
* **Status:** Accepted to Workshop IJCAI26 
* **Summary:** This research investigates the integration of parameterized quantum circuits (PQCs) as residual sidecar modules within a classical ResNet-50 backbone[cite: 2]. The model is applied to a 31-class neural population decoding task for imagined handwriting[cite: 2]. 
* **Key Findings:** Through a nine-variant ablation study, the research shows that backbone-gradient training consistently reorganizes representation geometry and reveals a latent star-topology preference[cite: 2]. The study also identifies that the representational capacity of a 4-qubit circuit acts as the primary bottleneck for further accuracy gains[cite: 2].
* **File:** `Quantum-Inspired Hybrid Neural Networks for Neural Decoding_ A Controlled Ablation Study of Learnable Quantum Sidecar Integration.pdf`
