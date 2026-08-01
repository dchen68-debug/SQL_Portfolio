# SQL_Portfolio

What it is:
  Synthetic P&C insurance dataset, self-built to practice CTEs/window functions and real world case studies. Dataset is included in sql_practice_seed_data.sql.Practice is split up into these modules:

  - Module 1 — Multi-CTE Fluency
  - Module 2 — Window Function Fundamentals
  - Module 3 — Ranking Functions
  - Module 4 — LAG / LEAD
  - Module 5 — Running Totals & Frames
  - Module 6 — Combining CTEs + Windows
  - Module 7 — Query Optimization Basics
  - Module 8 — Capstone


Schema w/ column names:
  1) claims_payments
     - payment_id integer
     - claim_id integer
     - payment_date date
     - payment_amount numeric (10,2)
     - payment_type
  2) claims
     - claim_id integer
     - policy_id integer
     - loss_date date
     - report_date date
     - claim_status text
     - incurred_amount numeric (10,2)
  3) monthly_premiums
     - policy_id integer
     - month date
     - earned_premium numeric (10,2)
  4) policies
     - policy_id integer
     - policyholder text
     - line_of_business text
     - state text
     - effective_date date
     - expiration_date date
     - annual_premium number (10,2)
    
