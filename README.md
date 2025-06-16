# JPMorgan Chase & Co. Quantitative Research Job Simulation

## Certificate of Completion

![image](cert.png)

## Overview
This program is designed to give you a risk-free way to experience real-world QR tasks, strengthen your data analysis and programming skills, and build confidence for future applications.

Quantitative Research (QR) at JPMorgan Chase is a leading quantitative modeling group specializing in financial engineering, data analytics, and portfolio management. QR partners with traders, marketers, and risk managers across all products and regions to drive:

- Sales and client interaction

- Product innovation

- Valuation and risk management

- Inventory and portfolio optimization

- Electronic trading and market making

- Financial risk controls

## Program Structure

The course is divided into four hands-on tasks that mirror the typical workflow in QR:

1. [Data Extrapolation & Interpolation (Natural Gas Pricing)](https://github.com/hajeeong/JPMorgan_Quantitative_Research/tree/main/Task1)

- Load monthly natural gas price snapshots (Oct 2020 – Sep 2024)

- Fit a trend + seasonal model to interpolate/extrapolate daily prices

- Implemented in Python using NumPy, Pandas, and Matplotlib

2. [Storage Contract Pricing Model](https://github.com/hajeeong/JPMorgan_Quantitative_Research/tree/main/Task2)

- Prototype a valuation function for gas storage deals

- Accounts for injection/withdrawal dates, volumes, and cost components

- Encapsulates PV = (sell_price − buy_price)×volume − fees

3. [Credit Risk Analysis (Personal Loans)](https://github.com/hajeeong/JPMorgan_Quantitative_Research/tree/main/Task3)

- Build logistic regression and random forest models to predict default probability

- Compute expected loss = PD × exposure × (1−recovery_rate)

- Evaluate performance (accuracy, ROC AUC) on sample loan data

4. [FICO Score Bucketing (Mortgage Book)](https://github.com/hajeeong/JPMorgan_Quantitative_Research/tree/main/Task4)

- Quantize FICO scores (300–850) into categorical buckets

- Optimized boundaries by maximizing binomial log‑likelihood via dynamic programming

- Outputs empirically derived bucket ranges and default rates