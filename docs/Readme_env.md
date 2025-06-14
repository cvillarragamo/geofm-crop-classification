# 🧪 Environment Setup Guide

This guide explains how to create and activate the development environment used in this project, using Conda and the `environment.yml` file.

---

## 📌 Requirements

- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/) installed

---

## 🛠 Step-by-Step Instructions

### 1. Clone the repository (if not done yet)

```bash
git clone https://github.com/cvillarragamo/geofm-crop-classification.git
cd geofm-crop-classification
```

### 2. Create the environment

From the project root directory, run:

```bash
conda env create -f environment.yml
```

This will create a new environment named `geofm-challenge` and install all required dependencies.

---

### 3. Activate the environment

```bash
conda activate geofm-challenge
```

---

### 4. Launch development tools

To open Jupyter Notebook:

```bash
jupyter notebook
```

Or simply use this environment in your code editor (e.g., VS Code).

---

### 5. Optional: Export the environment after changes

If you install new packages and want to update your environment file:

```bash
conda env export --from-history > environment.yml
```

This keeps the environment.yml clean and minimal.

---
