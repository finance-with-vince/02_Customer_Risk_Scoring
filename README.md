# Project 2: Basic Customer Risk Scoring

**Objective:** Develop a simple rule-based risk scoring model for a set of customers. This is a foundational element of Know Your Customer (KYC) and Customer Due Diligence (CDD) processes.

**KYC/AML Concepts Demonstrated:**
*   **Customer Due Diligence (CDD):** The process of collecting and evaluating information about a customer to assess their risk profile.
*   **Risk Assessment:** Assigning risk levels (e.g., Low, Medium, High) to customers based on predefined criteria.
*   **Enhanced Due Diligence (EDD):** Understanding that high-risk customers require more thorough investigation.

---

### Your Tasks:

**1. Python & Pandas Analysis:**
*   Load the `customers.csv` dataset.
*   Define a risk scoring function that assigns points based on `Country` and `Occupation`.
    *   **High-Risk Countries (e.g., "Cayman Islands", "Panama"):** +50 points
    *   **High-Risk Occupations (e.g., "Casino Owner"):** +40 points
    *   **Medium-Risk (e.g., "Jewelry Dealer"):** +20 points
*   Calculate a `RiskScore` for each customer.
*   Categorize customers into `RiskLevel` (Low, Medium, High) based on their score.

**2. SQL Analysis:**
*   Import the `customers.csv` into a database.
*   Use `CASE` statements in a SQL query to calculate the `RiskScore` for each customer directly in the database.
*   Create a view or a new table that includes the calculated `RiskScore` and `RiskLevel`.

**3. Power BI Visualization:**
*   Connect to the `customers.csv` data.
*   Create a new column for `RiskScore` and `RiskLevel` using Power Query or DAX.
*   Build a dashboard that shows:
    *   A pie chart of the number of customers in each `RiskLevel`.
    *   A table of all high-risk customers.
    *   A map visualizing the geographic distribution of customers.
