Online Retail Recommendation System – A content-based product recommender built with Python, TF-IDF, KNN, and Streamlit. It suggests similar products using product descriptions, provides country-wise & month-wise sales insights, and features interactive visualizations & fuzzy matching for better user input handling.
# 🛍️ Online Retail Recommendation System  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)  
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)  
![Scikit-learn](https://img.shields.io/badge/ML-ScikitLearn-orange)  
![License](https://img.shields.io/badge/License-MIT-green)  

## 📌 Overview  
This project is an **Online Retail Recommendation System** designed to suggest similar products to online shoppers. It mimics e-commerce recommendation features to improve **user engagement and shopping experience**.  

It uses **content-based filtering** with product descriptions, TF-IDF vectorization, dimensionality reduction (SVD), and **K-Nearest Neighbors with cosine similarity**.  

---

## 🎯 Features  
✅ **Content-based product recommendations**  
✅ **Country-wise & month-wise top-selling product insights**  
✅ **Interactive Streamlit dashboard**  
✅ **Fuzzy matching** to handle spelling errors in product names  
✅ **Visualizations using Seaborn & Matplotlib**  

---

## 📂 Dataset  
- **Source**: [Online Retail Dataset (Kaggle)](https://www.kaggle.com/)  
- **Features**: InvoiceNo, StockCode, Product Description, Quantity, InvoiceDate, CustomerID, Country  

---

## 🔄 Project Workflow  

1️⃣ **Data Preprocessing**  
- Removed duplicates & handled missing values  
- Converted `InvoiceDate` to datetime and extracted monthly trends  

2️⃣ **Exploratory Data Analysis (EDA)**  
- **Top-selling products** (global, country-wise, month-wise)  
- Visualized trends with **bar plots & heatmaps**  

3️⃣ **Recommendation Engine**  
- **TF-IDF Vectorization** of product descriptions  
- **Truncated SVD** for dimensionality reduction  
- **KNN (cosine similarity)** to find similar products  
- **Fuzzy matching** to handle typos in user input  

4️⃣ **Streamlit Web App**  
- Interactive interface where users can input a product name & get similar recommendations  

---

## 🛠️ Tech Stack  
- **Python** (pandas, numpy, scikit-learn)  
- **Streamlit** for web app  
- **Seaborn & Matplotlib** for visualization  
- **TheFuzz** for fuzzy string matching  

---

## 🚀 How to Run  

```bash
# Clone this repo
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
📊 Example Visualizations
📌 Top 10 Popular Products Globally
(placeholder for screenshot)

📌 Country-wise Product Demand
(placeholder for screenshot)

📌 Month-wise Sales Heatmap
(placeholder for screenshot)

🔮 Future Enhancements
✅ Add collaborative filtering for personalized recommendations

✅ Include user purchase history for better accuracy

✅ Improve UI/UX with filters & better design

✅ Deploy on Streamlit Cloud / Heroku

🤝 Contributing
Feel free to fork this repo and submit pull requests!

📜 License
This project is MIT licensed.

💡 Want to see it live?
👉 Coming soon: Deployment link!

👩‍💻 Author
Aashi Talwar
📧 aashitalwar31@gmail.com
