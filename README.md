# 🔐 Adaptive Privacy-Aware Federated FCA (AP-FedFCA)

<p align="center">

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Research](https://img.shields.io/badge/Research-Federated%20Learning-green)
![Framework](https://img.shields.io/badge/Framework-FCA-orange)
![Privacy](https://img.shields.io/badge/Privacy-Differential%20Privacy-red)
![Status](https://img.shields.io/badge/Status-Research%20Project-purple)

</p>

<p align="center">
🧠 Federated Knowledge Discovery  
🔒 Privacy-Preserving Learning  
📊 Formal Concept Analysis
</p>

---

## 📌 Overview

**Adaptive Privacy-Aware Federated Formal Concept Analysis (AP-FedFCA)** is a distributed framework designed to enable collaborative knowledge discovery while preserving data privacy. The framework extends **Federated Formal Concept Analysis (FedFCA)** by introducing an **adaptive differential privacy mechanism** that dynamically allocates privacy budgets according to the structural importance of concepts.

This strategy improves the **privacy–utility trade-off**, ensuring that sensitive information remains protected while maintaining the structural quality of the discovered knowledge.

Formal Concept Analysis (FCA) is a mathematical framework used to analyze relationships between **objects and attributes** and organize them into a **concept lattice structure**, enabling interpretable knowledge extraction and hierarchical data analysis.

---

## 🎯 Research Objectives

The main objectives of this work are:

- Enable **federated knowledge extraction** without sharing raw datasets.
- Integrate **differential privacy mechanisms** into distributed concept mining.
- Introduce **adaptive privacy budget allocation** based on concept sensitivity.
- Evaluate the **privacy–utility trade-off** in federated FCA environments.

---

## 🧠 Key Contributions

✨ **Adaptive Privacy Budget Allocation**  
Dynamic adjustment of differential privacy budgets according to concept sensitivity.

🔗 **Federated Concept Lattice Construction**  
Multiple participants collaboratively construct a global lattice without exchanging raw data.

📉 **Improved Privacy–Utility Trade-off**  
Better preservation of conceptual knowledge while maintaining strong privacy guarantees.

📊 **Evaluation Metrics**

- Concept Preservation Rate (CPR)
- Support Degradation
- Jaccard Similarity

---

## 🏗 Federated Architecture
<p align="center">
<img src="architecture.png" width="700">
</p>

Each participant maintains its **local dataset**, constructs a **local formal context**, extracts **formal concepts**, applies **adaptive differential privacy**, and shares protected information with the **federated aggregator** to build the global concept lattice.

---


## 📚 Scientific References

Ganter, B., & Wille, R. **Formal Concept Analysis: Mathematical Foundations**. Springer, 1999.  
https://link.springer.com/book/10.1007/978-3-642-59830-2

McMahan, B. et al. **Communication-Efficient Learning of Deep Networks from Decentralized Data**. AISTATS, 2017.  
https://proceedings.mlr.press/v54/mcmahan17a.html

Dwork, C., Roth, A. **The Algorithmic Foundations of Differential Privacy**.  
https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf

---

## 👩‍🔬 Authors

**Saida Sfaxi**  
RIADI Laboratory  
University of Tunis El Manar – Tunisia  

**Mokhtar Sellami**  
RIADI Laboratory  
University of Jendouba – Tunisia  

**Mohamed Mohsen Gammoudi**  
RIADI Laboratory  
University of Manouba – Tunisia  

---

## 📄 Citation

If you use this work in your research, please cite:
@article{apfedfca2026,
title={Adaptive Privacy-Aware Federated Formal Concept Analysis},
author={Sfaxi, Saida and Sellami, Mokhtar and Gammoudi, Mohamed Mohsen},
year={2026}
}
