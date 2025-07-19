# 🧪 A/B Testing: Credit Card vs. Cash Fares – NYC Yellow Taxi Data

This project was completed as part of the **Google Advanced Data Analytics Professional Certificate – Course 4: The Power of Statistics**. In this end-of-course project, I acted as a data analyst at Automatidata, working on a consulting project for the New York City Taxi and Limousine Commission (TLC).

We were tasked with using statistical testing to determine whether **passengers who pay with credit cards** are charged higher **fare amounts** than those who pay with **cash**.

---

## 📊 Project Overview

- **Client**: NYC Taxi and Limousine Commission (TLC)
- **Company**: Automatidata (fictional)
- **Objective**: Use statistical testing to assess the relationship between fare amount and payment type (cash vs. credit card)
- **Methodology**: A/B Test (Independent Two-Sample T-Test)

---

## 📁 Dataset

- **Name**: `2017_Yellow_Taxi_Trip_Data.csv`
- **Rows**: 408,294
- **Source**: Fictionalized dataset for educational purposes
- **Relevant columns**:
  - `payment_type`: 1 = Credit Card, 2 = Cash
  - `fare_amount`: Fare charged for the trip

---

## 🔍 Steps Performed

1. Imported and explored the dataset
2. Filtered records for **credit card (1)** and **cash (2)** payment types
3. Removed entries with invalid or zero fare values
4. Calculated descriptive statistics:
   - Credit Card Mean Fare: `$13.43`
   - Cash Mean Fare: `$12.22`
5. Visualized distributions using Seaborn
6. Conducted a two-sample t-test (Welch’s t-test)
7. Interpreted results

---

## 🧠 Key Findings

| Metric           | Credit Card | Cash      |
|------------------|-------------|-----------|
| Mean Fare        | $13.43      | $12.22    |
| Standard Deviation | 13.85     | 11.69     |
| Sample Size      | 15,262      | 7,266     |
| T-Statistic       | 6.87       |           |
| P-Value           | < 0.0001   |           |

✅ **Result**: We **rejected the null hypothesis**. There is a **statistically significant difference** in fare amounts—credit card users pay more.

---

## 📌 Insights & Recommendations

- Encourage **credit card payments** through promotions or loyalty incentives
- Investigate possible reasons behind higher credit card fares (e.g., trip length, tipping, location)
- Explore other variables such as `trip_distance`, `tip_amount`, or `time_of_day` for further insights

---

## 📂 Files in This Repository

- `Automatidata_AB_Test_Notebook.ipynb`: Jupyter notebook with full code and analysis
- `Executive_Summary.pdf`: 1-page summary of insights and recommendations
- `PACE_Strategy_Document.pdf`: Answers to project planning and reflection questions
- `README.md`: This project documentation

---

## 🧠 Tools Used

- Python (Pandas, NumPy, SciPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Google Workspace Templates (PACE strategy + Executive summary)

---

## 🚀 Certification Path

This project was submitted as the capstone for:
> 📚 **Google Advanced Data Analytics Professional Certificate**  
> **Course 4: The Power of Statistics**

---

## 📫 Contact

**Bheki Mogola**  
📍 South Africa  
📧 bhekimogola123@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/bheki-mogola-8481122b7)

---

⭐ If you found this project useful, feel free to give it a ⭐ and connect with me!
