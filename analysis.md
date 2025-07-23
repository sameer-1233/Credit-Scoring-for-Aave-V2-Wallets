
# 📊 Analysis of Wallet Credit Scores on Aave V2

This report summarizes the behavior of wallets based on their credit scores from 0–1000.

---

## 📈 Score Distribution

The credit scores are centered around ~600, with a left skew. Most users score between **400–700**, representing average financial behavior.

A smaller number of wallets scored extremely low (0–200) or high (800–1000), showing distinct risk categories.

---

## 🧠 Behavior by Score Bucket

| Score Range | Observed Behavior |
|-------------|-------------------|
| **900–1000** | High repayment ratios, low liquidation counts, healthy borrow-to-deposit ratios, active users. Very safe and reliable. |
| **700–900**  | Responsible usage with minor risks. Good repayment but slightly more borrowing. |
| **400–700**  | Average usage, moderate borrowing and repayments, occasional liquidation. |
| **200–400**  | Low repayments, high borrow-deposit ratios, more frequent liquidation events. |
| **0–200**    | Extremely risky. Many liquidations, little or no repayment, and exploit-like behavior. |

---

## 📊 Plots Included

- Histogram of credit scores (0–1000)
- Bar plot of wallet counts in 10 score buckets (0–100, ..., 900–1000)
- Boxplots of key features: deposit, borrow, repay, repayment ratio, etc.

---

## 💬 Summary

The scoring framework provides strong visibility into wallet behavior across the Aave V2 protocol. This can help:
- Flag high-risk wallets
- Reward responsible users
- Improve protocol-level risk modeling and incentives
