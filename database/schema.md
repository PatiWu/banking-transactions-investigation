# Database Schema

## Customer

Stores customer information.

| Column | Description |
|---|---|
| customer_id | Unique customer identifier |
| first_name | Customer first name |
| last_name | Customer last name |
| email | Customer email |
| country | Customer country |


## Account

Stores bank accounts.

| Column | Description |
|---|---|
| account_id | Unique account identifier |
| customer_id | Related customer |
| account_type | Type of account |
| balance | Current balance |


## Transaction

Stores financial transactions.

| Column | Description |
|---|---|
| transaction_id | Unique transaction identifier |
| account_id | Related account |
| transaction_date | Date of transaction |
| amount | Transaction amount |
| merchant | Merchant name |
| status | Transaction status |
