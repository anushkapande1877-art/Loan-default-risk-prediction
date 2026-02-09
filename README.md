<h1 align="center">💳 Loan Default Risk Prediction Demo</h1>

<p align="center">
  <em>End-to-end machine learning pipeline for credit risk classification</em>
</p>

<p align="center">
  <img src="Design/MainTop.gif" alt="Loan Default Risk Prediction Demo" width="400">
</p>

<div align="center">
<br />

![license](https://img.shields.io/badge/license-MIT-blue.svg)
![python](https://img.shields.io/badge/python-3.8%2B-blue)
![ml](https://img.shields.io/badge/Machine%20Learning-Classification-orange)
![status](https://img.shields.io/badge/status-active-success)

</div>

<details open="open">
<summary><strong>Table of Contents</strong></summary>

- [About](#about)
- [Problem Statement](#problem-statement)
- [Core Intuition](#core-intuition)
- [Features Used](#features-used)
- [ML Pipeline](#ml-pipeline)
- [Models](#models)
- [Evaluation Metrics](#evaluation-metrics)
- [Explainability](#explainability)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [License](#license)

</details>

---

## About

This project builds a **machine learning classification model** to predict whether a loan applicant is likely to **default** or **repay** a loan.

The goal is to assist banks, NBFCs, and fintech platforms in making **data-driven, explainable credit decisions**.

---

## Problem Statement

Loan defaults cause major financial losses.

Traditional credit evaluation:
- Is manual
- Is slow
- Lacks consistency

👉 This project automates **loan risk assessment** using historical borrower data.

---

## Core Intuition

Loan default is **not random**.

Borrowers who default often share common financial risk signals:
- Unstable income
- High debt burden
- Poor credit history
- Late or missed payments
- Risky financial behavior

The model learns these patterns and applies them to **new applicants**.

---

## Features Used

| Rank | Feature | Description |
|----|--------|-------------|
| 🥇 | Credit Score | Overall creditworthiness |
| 🥈 | Debt-to-Income Ratio | Debt burden relative to income |
| 🥉 | Payment History | Past late or missed payments |
| 4️⃣ | Employment Stability | Job continuity & income stability |
| 5️⃣ | Loan Amount | Requested loan size |

---

## ML Pipeline

```text
Data Collection
     ↓
Data Cleaning & Preprocessing
     ↓
Feature Engineering
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Risk Prediction (Probability + Class)
