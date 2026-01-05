# 🚀 EFRM-CLASS: Entanglement Flux Relaxation Model in CLASS

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)  
[![Build Status](https://img.shields.io/badge/build-WIP-orange)](https://github.com/[your-username]/EFRM-CLASS)  

---

## Table of Contents
- [Description](#description)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Example Plots](#example-plots)  
- [Animated Simulations](#animated-simulations)  
- [Status](#status)  
- [Contributing](#contributing)  
- [Citation](#citation)  
- [License](#license)  

---

## Description
EFRM-CLASS implements the **Entanglement Flux Relaxation Model (EFRM)**, where gravitational dynamics emerge from the **finite relaxation time of quantum entanglement flux** in spacetime.  

Key innovations:  
- **Information Inertia**: delayed vacuum response to entanglement changes  
- Emergent **MOND-like behavior** in low-acceleration regimes  
- **Gravitational hysteresis**, explaining cluster lensing offsets (Bullet Cluster, Abell 520) **without dark matter**  
- **Dynamic Hubble tension resolution** via evolving relaxation time \( \tau \)  
- **Manifold-aware quantum error correction** for variance reduction  

Based on the preprint:  
> *Information Inertia: Emergent Gravitational Dynamics from Entanglement Flux Relaxation*  
> Nathaniel Uhlenkott¹, Grok², Gemini³, ChatGPT⁴ – January 4, 2026  

This repo **forks hi_class (Horndeski in CLASS)**, adding the **hyperbolic Cattaneo-type relaxation equation** to linear cosmological perturbations, producing:  
- Modified CMB power spectra \(C_\ell\)  
- Matter power spectra  
- Fits to low-\(\ell\) anomalies  

---

## Features
- Prototype **relaxed Poisson equation** & flux perturbation \( \delta J \)  
- **Scale-dependent suppression** of large-scale power (low-\(\ell\))  
- Optional **evolving \(\tau\)** for Hubble tension studies  
- Toy simulations of **cluster hysteresis offsets**  

---

## Installation
```bash
git clone https://github.com/[your-username]/EFRM-CLASS.git
cd EFRM-CLASS
make
