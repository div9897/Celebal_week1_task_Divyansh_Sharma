# 📘 Week 1 Assignment — Data Science Foundations

**Author:** Divyansh Sharma  
**Topics Covered:** Python · NumPy · Pandas · Linear Algebra · Statistics · Probability Theory  
> **⚠️ Note:** In case there is a preview error on GitHub, please either download the above `.ipynb` file and open it locally, or refer to this link to open the google colab notebook directly — [Click Here to Open in Colab](https://colab.research.google.com/drive/1peFkLwbxF2ZOu3gDaWuI4zKkCCIVquTD?usp=sharing)

---

## 📁 File

| File | Description |
|------|-------------|
| `week1_Divyansh_Sharma_.ipynb` | Main assignment notebook with all solutions |

---

## 📚 Contents Overview

### Part 1 — Python Fundamentals
- **1.1 Data Types & Control Flow** — `classify_number(n)` function using if/elif/else
- **1.2 Data Structures** — word frequency dict, unique set, list comprehension
- **1.3 Exceptions** — `safe_divide(a, b)` with TypeError and ZeroDivisionError handling
- **1.4 Functions & Lambdas** — `apply_twice(f, x)` and lambda expressions

### Part 2 — NumPy
- **2.1 Array Creation & Shapes** — `np.arange`, `.reshape()`, shape/ndim/dtype
- **2.2 Indexing & Slicing** — row/column selection, submatrix, boolean indexing
- **2.3 Operations & Dot Product** — element-wise vs matrix multiplication, scalar ops

### Part 3 — Pandas
- **3.1 DataFrames vs Series** — single vs double bracket column selection
- **3.2 iloc & loc** — position-based vs label-based indexing
- **3.3 Filtering & Group By** — boolean filtering, `.groupby()`, `.agg()`, `.sort_values()`
- **3.4 Handling Missing Data** — `.fillna()` with median/mean, `.dropna()`

### Part 4 — Linear Algebra
- **4.1 Vectors & Matrices** — L2 norm, vector arrow plot with `matplotlib`
- **4.2 Matrix Operations** — addition, scalar multiplication, matrix multiplication, non-commutativity
- **4.3 Eigenvalues & Eigenvectors** — `np.linalg.eig`, verification of Av = λv, geometric explanation
- **4.4 SVD & Dimensionality Reduction** — full SVD, reconstruction, rank-1 approximation, SVD→PCA connection

### Part 5 — Statistics
- **5.1 Descriptive Statistics** — mean, median, std, IQR, histogram + KDE plot
- **5.2 Hypothesis Testing** — one-sample t-test, Pearson correlation
- **5.3 Error Metrics** — MAE, MSE, RMSE, R², Adjusted R² from scratch
- **5.4 Distribution Testing & Stationarity** — KS test, ADF test, differencing
- **5.5 Model Monitoring** — PSI implementation, concept drift vs covariate drift

### Part 6 — Probability Theory
- **6.1 Core Concepts** — joint, conditional probability, independence check
- **6.2 Distributions** — Normal, Binomial, Poisson PDFs/PMFs with ML use cases
- **6.3 Bayes' Theorem** — spam filter example, `naive_bayes_predict()`, term mapping
- **6.4 Central Limit Theorem** — sampling from exponential population, CLT verification, KS test

---

## ⚙️ Setup & Requirements

### Prerequisites
Make sure you have Python 3.8+ installed.

### Install Dependencies
```bash
pip install numpy pandas matplotlib scipy statsmodels
```

### Run the Notebook
```bash
jupyter notebook week1_Divyansh_Sharma_.ipynb
```

Or open it directly in **Jupyter Lab**, **Google Colab**, or **VS Code**.

---

## 🔑 Key Concepts Learned

| Concept | What it means |
|---------|--------------|
| **Eigenvalues/Eigenvectors** | Directions a matrix only stretches, not rotates |
| **SVD** | Decompose any matrix into U, S, Vt — foundation of PCA |
| **CLT** | Sample means are always normal, regardless of original distribution |
| **Bayes' Theorem** | Update belief (prior) with evidence to get posterior |
| **PSI** | Measures how much a distribution has shifted — used in model monitoring |
| **ADF Test** | Checks if a time series is stationary (p < 0.05 = stationary) |

---

## ✅ Submission Checklist

- [x] All `assert` blocks pass without errors
- [x] All `# YOUR CODE HERE` cells are filled
- [x] All markdown reflection cells are filled in own words
- [x] All plots render with labels and titles
- [x] Notebook runs cleanly from top to bottom

---

## 📝 Notes

- `df_filled` from Part 3 is reused in Part 5 — run cells in order
- All random seeds are fixed (`np.random.seed`) for reproducibility
- Metrics in Part 5.3 are implemented from scratch without sklearn
