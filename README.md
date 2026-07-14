# Operations Analytics — DEA, LP & Network Flow Optimisation (Excel Solver)

> Three quantitative optimisation models — **Data Envelopment Analysis (DEA)**, **Linear Programming (LP)**, and **Network Flow Optimisation** — built and solved in **Excel Solver** for operations management decision-making.
>
> **Operations Analytics**

---

## 🎯 Problem

Operations teams must allocate scarce resources efficiently. This project tackles three classic OR problems using spreadsheet-based Solver models:

| Model | Business Question |
|---|---|
| **DEA (Data Envelopment Analysis)** | Which decision-making units (DMUs) are technically efficient, and what are the benchmarks for the inefficient ones? |
| **Linear Programming** | How should limited resources be allocated to maximise an objective (profit / output) subject to capacity, demand and supply constraints? |
| **Network Flow Optimisation** | What is the minimum-cost (or maximum-flow) routing through a supply-distribution network? |

## 🧪 Methodology

### 1. Data Envelopment Analysis (DEA)
- Input-oriented CRS/VRS models
- Efficiency frontier identification
- Benchmarking inefficient DMUs against peers
- Sensitivity to model orientation

### 2. Linear Programming (LP)
- Decision-variable formulation with objective function
- Constraint specification (capacity, demand, non-negativity)
- Solver configuration: **Simplex LP** method
- Shadow-price analysis and sensitivity reporting
- ±RHS / ±Objective coefficient ranges

### 3. Network Flow Optimisation
- Node-arc network representation
- Supply, demand and transhipment node modelling
- Minimum-cost flow / shortest-path formulation
- Solver-based solution with flow balance constraints

## 📈 Key Deliverables

- Solved Excel workbooks with Solver parameters pre-configured
- Sensitivity reports (Answer Report, Sensitivity Report, Limits Report)
- Interpretation of shadow prices and reduced costs
- Strategic recommendations based on optimisation results

## 🧰 Tech Stack

`Microsoft Excel` · `Solver` (Simplex LP / GRG Nonlinear) · Sensitivity & Answer reports

## 📁 Repo Structure

```text
.
├── Report/
├── Solved Excel File/
├── LICENSE
└── README.md
```

## ▶️ How to Use

1. Open the workbook(s) in `Solved Excel File/` using **Microsoft Excel**
2. Navigate to `Data` → `Solver` — parameters are already configured
3. Click **Solve** to reproduce the optimal solutions
4. Review the Sensitivity and Answer reports for interpretation

## 📄 Report

Full analysis with model formulations, results and strategic recommendations → see `Report/` directory.

---

<sub>MIT-licensed · Author: [Parth Badiger](https://github.com/parthbadiger24-creator)</sub>
