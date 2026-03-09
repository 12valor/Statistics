# Laboratory Activities for Statistics with Python

A collection of hands-on laboratory activities designed to teach Statistics using Python through practical, real-world data analysis.

This repository is built for students who want to actually understand statistics and the coding fundamentals behind them, not just memorize formulas.

---

## Repository Structure

### The Labs

The activities follow a progression from Python basics to statistical application:

| Lab      | File Name                                  | Key Concepts                                                                                                 |
| :------- | :----------------------------------------- | :----------------------------------------------------------------------------------------------------------- |
| **01**   | `Lab-1-lists-and-tuples.ipynb`             | **Python Basics:** Handling data structures, list manipulation, and tuple immutability.                      |
| **02**   | `Lab-2-for-Loop.ipynb`                     | **Control Flow:** Iterating through data sequences and automating calculations.                              |
| **03**   | `Lab-3-numpy-basics.ipynb`                 | **Numerical Computing:** Introduction to NumPy arrays, broadcasting, and vectorization.                      |
| **04**   | `Lab-4-pandas-basics.ipynb`                | **Data Manipulation:** Loading CSVs, DataFrames, cleaning data, and basic exploratory analysis.              |
| **05**   | `Lab-5-correlation.ipynb`                  | **Statistical Relationships:** Measuring the strength of relationships between variables (Pearson/Spearman). |
| **06**   | `Lab-6-standard-normal-distribution.ipynb` | **Probability:** Understanding the Bell Curve, Z-scores, and probability density.                            |
| **07**   | `Lab-7-z-Distribution.ipynb`               | **Probability:** Finding the CI and Visualizing the Z-distribution                                           |
| **08**   | `Lab-8-T-Distribution.ipynb`               | **Probability:** The T-Distribution                                                                          |
| **09**   | `lab-9-hypothesis-testing.ipynb`           | **Hypothesis Testing:** Formulating null/alternate hypotheses and testing significance.                      |
| **10**   | `lab-10-proportion-test.ipynb`             | **Proportions:** Testing population proportions and understanding categorical data differences.              |
| **11**   | `lab-11-normality-test.ipynb`              | **Normality:** Checking for normal distribution using visual and formal statistical tests.                   |
| **12**   | `lab-12-t-test.ipynb`                      | **T-Tests:** Applying 1-sample, 2-sample, and paired t-tests to compare means.                               |
| **Exam** | `Endterm Exam/Exam.ipynb`                  | **Endterm Exam:** 1-Sample T-Test utilizing Central Limit Theorem for website Bounce Rate analysis.          |

### The Datasets

Located in the `dataset/` directory, these real-world CSV files are used throughout the labs:

- **Environmental:** `air-quality.csv`
- **Energy:** `current-power.csv`, `current-test.csv`, `transformer-voltage.csv`
- **Retail/Inventory:** `shoe-inventory.csv`

Additionally, the **Endterm Exam** utilizes a specific dataset located in its respective folder:

- **Web Analytics:** `Exam dataset/website.csv`

---

## Tech Stack

- **Python 3.9+**
- **Jupyter Notebook**
- **Core Libraries:**
  - `numpy` (Math & Arrays)
  - `pandas` (Data Handling)
  - `matplotlib` & `seaborn` (Visualization)
  - `scipy` (Scientific Computing)

---

## Getting Started

1.  **Clone the repository**

    ```bash
    git clone [https://github.com/12valor/Statistics.git](https://github.com/12valor/Statistics.git)
    cd Statistics
    ```

2.  **Install dependencies**

    ```bash
    pip install numpy pandas matplotlib scipy seaborn jupyter
    ```

3.  **Launch Jupyter Notebook**
    ```bash
    jupyter notebook
    ```
