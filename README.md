# 📞 Megaline Tariff Analysis

## 🧠 Context
As a data analyst for the telecom company **Megaline**, I was tasked with identifying which of the two prepaid plans — **Surf** or **Ultimate** — generates more revenue. This helps the marketing department allocate their advertising budget more efficiently.

---

## 🎯 Objective
To analyze customer usage patterns (calls, SMS, internet) and determine which plan yields higher average monthly revenue.

---

## 🧰 Tools Used
- **Python**
- **Pandas**, **Matplotlib**, **NumPy**, **SciPy**
- Statistical testing: Welch’s t-test (for comparing means)

---

## 🗃️ Dataset Overview
The analysis was based on real customer usage data from 2018:
- `megaline_users.csv` – customer plan, region, start date
- `megaline_calls.csv` – call durations per user per month
- `megaline_messages.csv` – SMS messages sent
- `megaline_internet.csv` – megabytes used monthly
- `megaline_plans.csv` – plan details (prices, limits, overcharges)

---

## 🔍 Key Analyses
- Data cleaning and type conversion (e.g., converting MB to GB, ensuring numeric formats)
- Monthly revenue calculation per user under each plan
- Average revenue per plan across all users
- Statistical testing (Welch’s t-test) to compare plan revenue averages

---

## 📊 Insights & Results
- **Ultimate** generates slightly higher revenue on average, due to frequent overage charges.
- **Surf** is more popular but less profitable per user.
- **T-test** shows the difference in average revenue is statistically significant (`p < 0.05`).

---

## ✅ Conclusion
- **Recommendation:** Focus marketing budget on users likely to exceed usage limits under Surf, or promote Ultimate to heavy users.
- Further segmentation by region or user behavior is advised for more targeted campaigns.

---

## 👨‍💻 Author
**Emerson Ríos**  
[LinkedIn](https://www.linkedin.com/in/emersonrios/) | [GitHub](https://github.com/Eme48)
