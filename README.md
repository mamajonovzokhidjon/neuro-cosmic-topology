# Neuro-Cosmic Topology

A quantitative network science model analyzing the structural topological similarities between cosmic webs and human neural networks (connectomes).

## 🌌 Overview
Although separated by 27 orders of magnitude in spatial scale, the large-scale structure of the Universe (cosmic web of galaxies and filaments) and the micro-scale structure of the human brain (neuronal networks) share striking topological properties. This project simulates and analyzes these structural characteristics using advanced network science methodologies, heavily inspired by foundational research from **Franco Vazza** and **Alberto Feletti**.

## 🧠 Key Features & Metrics
* **Small-World Architecture:** Implements the **Watts-Strogatz model** to simulate high clustering coefficients alongside short average path lengths.
* **Topological Metrics:** 
  * Average Clustering Coefficient ($C$)
  * Average Shortest Path Length ($L$)
  * Degree Distribution & Hub Identification ($k$)
* **Dual-Panel Visualization:** Generates dark-themed, publication-ready visual topologies and degree distribution histograms.

## 🚀 How to Run
You can run this simulation directly in your browser via Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mamajonovzokhujdon/neuro-cosmic-topology/blob/main/Neuro_Cosmic_Topology_Comparative_Analysis.ipynb)

### 📊 Comparative Metrics Summary

| Network Model | Nodes ($|V|$)| Edges ($|E|$)| Avg Degree ($\langle k \rangle$) | Clustering Coeff ($C$) |

| :--- | :--- | :--- | :--- | :--- |

| **Cosmic Web (BA)** | 300 | ~891 | ~5.94 | ~0.065 |

| **Neural Connectome (WS)** | 300 | 900 | 6.00 | ~0.521 |

---


## 🛠️ Tech Stack
* **Python**
* **NetworkX** (Network analysis & graph generation)
* **Matplotlib** (Advanced data visualization)
* **NumPy** (Mathematical computations)

##
---
*Developed as part of an independent exploration into complex systems and network topology.*

## 🔬 Comparative Topological Analysis

This repository now includes a comparative quantitative analysis examining structural and topological similarities between:
1. **Cosmic Web Simulations** (Scale-free network properties modeled via the Barabási-Albert algorithm)
2. **Human Neural Connectomes** (Small-world network properties modeled via the Watts-Strogatz algorithm)

### 📊 Key Metrics Analyzed
* **Number of Nodes & Edges**
* **Average Degree**
* **Clustering Coefficient**
* **Average Shortest Path Length**

### 🚀 Visualizations
The model generates publication-ready dual-panel dark-themed plots comparing the spatial topologies of cosmic structures and neural networks.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mamajonovzokhidjon/neuro-cosmic-topology/blob/main/Neuro_Cosmic_Topology_Comparative_Analysis.ipynb)
