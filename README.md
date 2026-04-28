
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=200&section=header&text=Study%20Notebooks&fontSize=40&fontAlignY=35&animation=fadeIn" />
</p>

<h1 align="center">📚 Study Notebooks</h1>

<p align="center">
  A curated collection of Jupyter notebooks for learning, experimenting, and building intuition.
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/rhyzor/study-notebooks?style=social" />
  <img src="https://img.shields.io/github/forks/rhyzor/study-notebooks?style=social" />
  <img src="https://img.shields.io/github/actions/workflow/status/rhyzor/study-notebooks/notebooks.yml?style=flat-square" />
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" />
</p>

---

## 📑 Table of Contents

- [🧠 Overview](#-overview)
- [🎬 Preview](#-preview)
- [📂 Repository Structure](#-repository-structure)
- [🚀 Getting Started](#-getting-started)
- [📊 Topics Covered](#-topics-covered)
- [🧩 Featured Notebooks](#-featured-notebooks)
- [🐳 Docker](#-docker-optional-but-)
- [🤖 CI / Automation](#-ci--automation)
- [🔮 Roadmap](#-roadmap)
- [⭐ Support](#-support)

---

## 🧠 Overview

This repository is a growing collection of **study notebooks** where I:

- explore new concepts  
- test ideas in code  
- document my learning process  

It acts as both a **learning log** and a **technical playground**.

---

## 🎬 Preview

<p align="center">
  <img src="assets/demo.gif" width="800"/>
</p>

> 💡 Tip: replace this with your own notebook demo GIF

---

## 📂 Repository Structure

```bash
study-notebooks/
│
├── notebooks/        # Jupyter notebooks
├── data/             # datasets
├── src/              # helper scripts
├── assets/           # gifs / images
└── requirements.txt
````

---

## 🚀 Getting Started

### ⚡ One-line setup (recommended)

```bash
git clone https://github.com/rhyzor/study-notebooks.git && cd study-notebooks && make setup
```

---

## 🧰 Manual Setup

### 📦 1. Clone the repository

```bash
git clone https://github.com/rhyzor/study-notebooks.git
cd study-notebooks
```

---

### 🐍 2. Environment Setup

#### 🍎 macOS / 🐧 Ubuntu

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

---

#### 🪟 Windows (PowerShell)

```powershell
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

---

### 📓 3. Launch

```bash
jupyter notebook
```

---

## 📊 Topics Covered

* Python fundamentals
* Data analysis
* Machine learning basics
* Mathematics & statistics
* Experimental notebooks

---

## 🧩 Featured Notebooks

### 📊 Data Analysis

* 📈 Exploratory Data Analysis (EDA)
* 📉 Data visualization

### 🤖 Machine Learning

* 🧠 Linear Regression from scratch
* 🌲 Decision Trees basics

### 🐍 Python Experiments

* ⚡ Performance tricks
* 🎲 Simulations

> 📂 Browse more in the `/notebooks` directory

---

## 🎬 Notebook Previews

| Data Analysis       | Machine Learning   |
| ------------------- | ------------------ |
| ![](assets/eda.gif) | ![](assets/ml.gif) |

---

## 🐳 Docker (optional, but 🔥)

```bash
docker build -t study-notebooks .
docker run -p 8888:8888 study-notebooks
```

---

## ⚙️ Makefile Commands

```bash
make setup      # install dependencies
make run        # start jupyter
make clean      # cleanup
```

---

## 🤖 CI / Automation

This repository uses **GitHub Actions** to automatically execute notebooks on every push.

✔ ensures notebooks run without errors
✔ keeps outputs fresh
✔ improves reproducibility

---

## 🧠 Philosophy

> Learning by doing > passive consumption

This repo reflects an **iterative learning process**:
small experiments → insights → improvement.

---

## 🔮 Roadmap

* [ ] Add structured learning paths
* [ ] Improve organization
* [ ] Add real-world mini projects
* [ ] Enhance documentation

---

## ⭐ Support

If you find this repository useful:

* ⭐ Star the repo
* 🍴 Fork it
* 💡 Use it for your own learning

---

## 📬 Contact

GitHub: [https://github.com/rhyzor](https://github.com/rhyzor)

```
