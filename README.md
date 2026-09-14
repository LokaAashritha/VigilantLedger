# 🏦 VigilantLedger

## ⚠️ The Problem
When cybercriminals steal money online today, they don't leave it in one place. They use automated scripts to instantly split and transfer the stolen cash across a long chain of **10 to 20 different "mule accounts"** within seconds. 

Traditional bank security systems are **passive**. They look at the data *after* the money is transferred, notice the theft, and print an alert on a dashboard for a human worker to review. By the time a human checks the alert, the money has already cleared the chain and vanished completely. 

---

## 💡 The Solution
**VigilantLedger** is a smart, high-speed automated defense engine for banking systems built out of personal curiosity to tackle this real-world security challenge.

Instead of waiting for theft to happen and logging an alert, this system sits right in the middle of the payment flow and checks transactions **in-flight (while they are happening)**. 

When a payment request comes in, the system instantly runs two automated checks:
1. **Velocity Check:** It looks to see if a user is suddenly spamming payments (e.g., trying to send more than 3 payments in under a single minute).
2. **Chain Check:** It scans the receiver's account history to see if they behave like a "mule account" that immediately forwards incoming money out to other random accounts.

If the system catches these patterns, it **takes action instantly**. It intercepts the transaction thread, automatically freezes the compromised accounts, and rolls back the database ledger so that **no money ever leaves the account boundaries**. This moves banking security from passive watching to active protection.

