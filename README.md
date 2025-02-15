# AF3005_ProgrammingForFinance

SecureBank Finance Tools 💳📊
A Python-based interactive system using ipywidgets for financial decision-making at SecureBank.

📌 Overview
This system automates loan eligibility checks, investment risk assessment, loan tracking, stock monitoring, and currency exchange tracking, offering a user-friendly financial experience.

🛠 Features & Implementation
✅ 1. Loan Eligibility Checker
✔ Employment & Income Check (PKR 50,000 minimum).
✔ Credit Score-Based Interest Rates:
750+ → 5% | 650-749 → 8% | Below 650 → Rejected
✔ Interactive user input via ipywidgets.

📊 2. Investment Risk Assessment
✔ Categorizes portfolio risk:

High Risk (any negative return)
Medium Risk (returns positive but <5%)
Low Risk (all returns ≥5%)
✔ Uses loops to analyze stock returns.

💰 3. Loan Repayment Tracker
✔ Tracks loan payments dynamically.
✔ Deducts fixed monthly payments until balance reaches zero.
✔ Loop-based tracking for real-time updates.

📈 4. Stock Price Monitoring
✔ Tracks stock prices daily.
✔ Skips None values & stops at PKR 200.
✔ Uses continue for missing data, break at sell point.

💹 5. Currency Exchange Tracker
✔ Starts at PKR 290/USD, increases daily by 1 PKR.
✔ Stops at PKR 300/USD with real-time updates.
✔ Loop-based simulation for tracking.

📂 Project Structure

📁 SecureBank-Finance-Tools/
 ├── loan_eligibility.py  
 ├── investment_risk.py  
 ├── loan_tracker.py  
 ├── stock_monitor.py  
 ├── currency_tracker.py  
 ├── README.md  
 
💡 Use Cases
🔹 Banks & Lenders: Automates loan decisions.
🔹 Investors & Traders: Assists in risk & market tracking.
🔹 Customers: Enhances financial literacy & decision-making.

📌 How to Run?
bash
Copy
Edit
git clone https://github.com/MominBinOmar/AF_3005_ProgrammingForFinance.git
pip install ipywidgets
Run scripts in Jupyter Notebook/IPython.

🚀 Future Enhancements
✔ Live API for stocks & currency tracking.
✔ Machine learning for advanced loan approvals.
✔ Data visualization for insights.
