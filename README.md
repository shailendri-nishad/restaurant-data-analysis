# 🍽️ Restaurant Data Analysis — Cognifyz Technologies Internship

This project is part of my **Data Science Internship at Cognifyz Technologies**.
I worked with a real-world restaurant dataset to clean the data and find useful insights from it.

---

## 📌 What is this project about?

The dataset contains information about restaurants from different cities and countries — things like their cuisines, ratings, price range, votes, and whether they offer online delivery or table booking.

I went through 3 main steps:

1. **Cleaned the data** so it's accurate and easy to work with
2. **Analyzed the data** to answer simple questions (Level 1)
3. **Went deeper** to find patterns and relationships in the data (Level 3)

---

## 📂 Files in this project

| File | What it is |
|------|------------|
| `Dataset.csv` | The original, raw restaurant data |
| `Dataset_cleaned.csv` | The cleaned version of the data |
| `01_data_cleaning.ipynb` | Notebook where I clean the data |
| `Level_01_Task.ipynb` | Notebook with basic analysis |
| `Level_03_Task.ipynb` | Notebook with advanced analysis |

---

## 🧹 Step 1: Data Cleaning

Before analyzing any data, it's important to make sure it's clean. In this step I:

- Checked for missing values and filled them in properly
- Checked for duplicate rows
- Fixed broken text (some special characters like `£` and `İ` were showing up incorrectly)
- Removed extra spaces from text
- Made sure all numbers (ratings, votes, cost, etc.) made sense
- Saved the final clean file as `Dataset_cleaned.csv`

---

## 📊 Step 2: Basic Analysis (Level 1)

Here I answered some simple, beginner-level questions:

- **Top Cuisines** — What are the most common cuisines restaurants serve?
- **City Analysis** — Which city has the most restaurants? Which city has the best-rated restaurants?
- **Price Range** — How are restaurants spread across different price ranges?
- **Online Delivery** — How many restaurants offer online delivery, and do they get better ratings?

### A few things I found:
- **Inner City** has the highest average rating (**4.90**), while **Faridabad** has the lowest (**1.87**)
- Only **25.66%** of restaurants offer online delivery
- Restaurants offering online delivery have better average ratings (**3.25**) than those that don't (**2.47**)

---

## 🔎 Step 3: Deeper Analysis (Level 3)

In this part, I looked for **patterns and relationships** in the data:

- **Reviews** — Looked at rating categories (like "Good", "Poor") to see which are most common
- **Votes** — Found which restaurants got the most and least votes, and checked if more votes mean better ratings
- **Price vs Services** — Checked if pricier restaurants are more likely to offer online delivery or table booking

### A few things I found:
- **Toit** has the highest number of votes (**10,934**)
- There is a **weak positive link** between votes and ratings (more votes → slightly better ratings, but not a strong pattern)
- **Table booking** is much more common in expensive restaurants, but **online delivery** is not — it's actually more common in mid-range restaurants

---

## 🛠️ Tools I Used

- **Python**
- **Pandas** — for cleaning and working with data
- **Matplotlib / Seaborn** — for making charts
- **Jupyter Notebook**

---

## 🙏 Acknowledgment

This project was completed as part of my Data Science Internship with **Cognifyz Technologies**. I'm grateful for the opportunity to work on real data and learn practical data analysis skills.

---

## 📬 Connect with me

Feel free to check out the notebooks in this repo to see the full code and explanations, step by step.

## Author

**Shailendri Nishad**
[LinkedIn](https://www.linkedin.com/in/shailendri-nishad-59b13027b) · [GitHub](https://github.com/shailendri-nishad)
