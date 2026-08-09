# Telecom Churn Analysis — Power BI Dashboard

A 10-page, 43-visual Power BI report analysing customer churn for a telecom operator: who leaves, for what reason, and where to act first.

## The question

A telecom operator is losing subscribers without knowing which ones, or why. The data exists — contracts, usage, customer service calls, billing — but scattered, with no shared indicator to rank the problem.

## What the report answers

| Metric | Value |
|---|---|
| Customers analysed | 6,687 |
| Churned | 1,796 |
| **Churn rate** | **26.86 %** |
| Customer service calls | 6,123 |

**Main findings**

- **Competitors drive churn.** "Competitor made a better offer" and "Competitor had better devices" lead the reasons, ahead of price and network reliability.
- - **Support calls predict churn.** Customers who leave average about 2.5 service calls; those who stay average about 0.4 — a six-fold gap, consistent across every state.
  - - **Contract type matters.** Month-to-month contracts represent 51 % of the customer base and concentrate the churn risk.
    - - **Churn is geographic.** Rates vary sharply by state, mapped in the report.
     
      - ## Approach
     
      - **Modelling** — the raw export had no churn indicator. The following DAX measures were created:
     
      - - `Churn Rate`
        - - `Avg Customer Service Calls`
          - - `Avg Extra Data Charges`
            - - `Avg Extra International Charges`
             
              - **Segmentation** — churn rate crossed with contract type, payment method, age band, monthly GB usage and state, until the at-risk combinations stood out.
             
              - **Structure** — ten pages opening on an *Overview* and closing on an *Insights* page, so the report answers before it details.
             
              - ## Report pages
             
              - `Overview` · `Churn Demographics` · `Groups and Categories` · `Unlimited Plan` · `International Calls` · `Contract Type` · `Age Groups` · `Payment and Contract` · `Extra Charges` · `Insights`
             
              - ## Stack
             
              - Power BI Desktop · DAX · Power Query
             
              - ## Data
             
              - Databel — telecom customer dataset used in the DataCamp *Data Visualization in Power BI* course. Built and structured independently as the course's final project.
             
              - ## Author
             
              - [Idens Meranvil](https://www.linkedin.com/in/idens-meranvil) — Supply Chain Team Lead at Talkpool AG, working on data analysis applied to operations.
              - 
