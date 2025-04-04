# RedBus-Bus-Reviews-Scraper-Analysis
Developed a Streamlit app that scrapes RedBus customer reviews using Selenium, cleans and stores the data in SQLite, and visualizes insights like top-rated buses, common issues, and rating trends. Enables users to explore and analyze bus services for better travel decisions.

# 🚌 RedBus Bus Reviews Scraper & Analysis using Streamlit

📌 **Domain**: Travel & Transportation | Web Scraping | Data Analytics  
🛠️ **Skills**: Web Scraping (Selenium), Streamlit, SQL, Data Cleaning, Python Programming

---

## 🚀 About the Project

A complete data pipeline that scrapes **RedBus customer reviews**, cleans the data, stores it in a **relational database**, and presents it via an **interactive Streamlit dashboard** for user exploration. Perfect for gaining insights into bus operator quality, ratings, and user feedback.

---

## 🎯 Features

- 🔍 Scrape live RedBus data (bus name, operator, route, ratings, reviews)
- 🧹 Clean & preprocess data for accuracy
- 🗃️ Store data in **SQLite/PostgreSQL**
- 📊 Visualize data using **Streamlit**
- 🔄 Search, filter & sort bus reviews
- 📈 Perform basic sentiment analysis (optional)

---

## 💡 Use Cases

- 🧑‍💼 Travelers: Compare and choose the best-rated bus services
- 🧾 Operators: Identify issues from user feedback for service improvement
- 🎯 Analysts: Perform review-based insights and sentiment trends
- 📲 Future Scope: Personalized bus recommendations

---

## 📂 Tech Stack

| Category | Tools |
|---------|--------|
| Web Scraping | Selenium |
| Backend | Python, SQLite/PostgreSQL |
| Dashboard | Streamlit |
| Data Wrangling | Pandas, Regex |
| Visualization | Matplotlib / Plotly (Streamlit native) |

---

## 📊 Sample Visual Insights

- 🔝 Top-Rated Bus Operators
- 😠 Most Common Complaints
- 💬 Review Sentiment Word Cloud
- 📈 Rating Distribution by Routes

---

## 🏗️ Project Structure


---

## 🧪 How to Run the Project

```bash
# Step 1: Clone the repo
git clone https://github.com/hana3232/redbus-review-streamlit.git
cd redbus-review-streamlit

# Step 2: Install requirements
pip install -r requirements.txt

# Step 3: Run scraper to fetch data
python scraper/scrape_reviews.py

# Step 4: Launch the Streamlit app
streamlit run app/main.py

📌 References
Streamlit Docs

Selenium WebDriver Docs

SQL Connection Guide

Streamlit Tamil Special Session (Aug 11)

🧑‍💻 Author
Created by: Hana

Verified and Approved by: Aravinth Meganathan

📅 Project Timeline
Duration: 1 Week
Status: ✅ Completed and Functional
Future Enhancements: Recommendation system, AI-based review classification, Deployment on Streamlit Cloud or Hugging Face Spaces

