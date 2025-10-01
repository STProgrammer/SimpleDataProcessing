# SimpleDataProcessing

Three self-contained Jupyter Notebooks that **clean messy CSV/Excel files and produce 5 clear charts** per case. Each notebook saves a cleaned dataset, chart images (PNGs), and keeps the steps reproducible in code.

---

## What’s inside (short)

```
SimpleDataProcessing/
├─ case1_ecommerce_sales/      # notebook + charts + sample raw/clean CSV
├─ case2_saas_churn/           # notebook + charts + sample raw/clean CSV
├─ case3_marketing_perf/       # notebook + charts + sample raw/clean CSV
└─ .gitignore
```

---

## Quick start

### 1) Clone and open

```bash
git clone https://github.com/STProgrammer/SimpleDataProcessing.git
cd SimpleDataProcessing
```

Open in JupyterLab or classic Jupyter Notebook (VS Code works too).

### 2) Install minimal dependencies

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

pip install --upgrade pip
pip install jupyter pandas numpy matplotlib
# optional: pip install seaborn
```

### 3) Run any notebook

* Open `case*/notebook.ipynb`.
* Adjust the **input file path** (CSV/XLSX) in the first cell if needed.
* Run cells top-to-bottom.

Each notebook will:

* load the raw file
* standardize text/casing, parse dates, fix types, remove duplicates, handle nulls
* produce **5 charts** (saved under `charts/`)
* export a **cleaned dataset** (`*clean.csv`)

---

## Per-case notes

* **case1_ecommerce_sales** — Ecommerce sales data, 10 charts, a Jupyter Notebook
* **case2_saas_churn** — SaaS sales and churt data, 10 charts, a Jupyter Notebook
* **case3_marketing_perf** — Marketing performance data, 5 charts, a Jupyter Notebook

*(Column names vary by dataset; tweak early cells to map your columns.)*

---

## Outputs

* `charts/1_*.png` … `charts/5_*.png` (publication-ready)
* `*clean.csv` (cleaned dataset)
* Executed `notebook.ipynb` documenting every step

---

## Environment

* Python 3.10+ recommended
* Packages: `jupyter`, `pandas`, `numpy`, `matplotlib` (optional: `seaborn`)

---

## License

Add a `LICENSE` file (e.g., MIT/BSD/Apache) if you plan to reuse.
