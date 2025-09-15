# Lending Club Data Repository

This repository contains Lending Club loan data and supporting materials for analysis and coursework.  
⚠️ The dataset is large (>100 MB) and is stored using **Git LFS (Large File Storage)**.

---

## 📥 How to Clone This Repository

### 1. Install Git and Git LFS
Make sure you have **Git** and **Git LFS** installed.

- **Windows/Mac**: Download from [https://git-scm.com/downloads](https://git-scm.com/downloads)  
- **Linux**: Install with your package manager (e.g., `sudo apt install git git-lfs`)

Then run this one-time setup:
```bash
git lfs install
```

### 2. Clone the Repo
```bash
git clone https://github.com/rfox12-edu/p2p-lending.git
cd p2p-lending
```

### 3. Verify the Data File
Git LFS will automatically pull the large dataset file (.parquet) when you clone.
If you see only a tiny text file instead of the data, run:
```bash
git lfs pull
```
