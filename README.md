# 🔓🚀 Unlock Your `package-lock.json` with **lockfile-extract**  

**`lockfile-extract` is a lightweight CLI tool that extracts all package versions from `package-lock.json`—without installing dependencies!**  
Easily analyze your project's dependencies without running `npm list` or installing unnecessary packages.  

## 🚀 Features  
- ✅ **Instantly extract** package names & versions  
- ✅ **Multiple output formats**: CLI, JSON, and CSV  
- ✅ **Zero dependencies** required—no `npm install` needed  
- ✅ **Fast & lightweight** for quick analysis  

## 🔧 Installation  

### Install from PyPI (Recommended)
```bash
pip install lockfile-extract
```
## ⚡ Usage

### Extract package versions (CLI Output)
```bash
lockfile-extract package-lock.json
```
### ✅ Example Output
```nginx
express 4.17.1, axios 1.2.3, lodash 4.17.21, ...
```

### Save output to JSON or CSV

#### 📄 Output as JSON file
```bash
lockfile-extract package-lock.json --format=json
```
📌 Creates output.json with package details in JSON format.

#### 📊 Output as CSV file
```bash
lockfile-extract package-lock.json --format=csv
```
📌 Creates output.csv with package details in CSV format.
