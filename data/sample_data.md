# Sample Data

This file contains sample banking data used for QA investigation.

---

# Customer Table

| customer_id | first_name | last_name | email | country |
|---|---|---|---|---|
| 101 | Anna | Kowalska | anna.kowalska@email.com | Poland |
| 102 | John | Smith | john.smith@email.com | UK |
| 103 | Maria | Rossi | maria.rossi@email.com | Italy |
| 104 | Peter | Brown | peter.brown@email.com | Germany |

---

# Account Table

| account_id | customer_id | account_type | balance |
|---|---|---|---|
| 5001 | 101 | Current | 2500 |
| 5002 | 102 | Savings | 8000 |
| 5003 | 103 | Current | 1200 |
| 5004 | 104 | Current | 5600 |

---

# Transaction Table

| transaction_id | account_id | transaction_date | amount | merchant | status |
|---|---|---|---|---|---|
| 9001 | 5001 | 2026-01-10 | 120.00 | Amazon | Completed |
| 9002 | 5001 | 2026-01-10 | 120.00 | Amazon | Completed |
| 9003 | 5002 | 2026-01-11 | 75.50 | Netflix | Completed |
| 9004 | 5003 | 2026-01-12 | 200.00 | Booking.com | Completed |
| 9005 | 5004 | 2026-01-13 | 50.00 | Spotify | Failed |
| 9006 | 5004 | 2026-01-13 | 50.00 | Spotify | Completed |
