# 🧠 AI-Powered Personal Finance Tracker

This is a smart finance assistant built in **Python** using **Streamlit**, **Hugging Face Transformers**, and classic ML libraries. It analyzes your transactions, clusters vendor spending, and provides intelligent summaries to help you manage your money like a boss.

## 📊 Features

- 🧾 **Transaction Categorization:** Classifies vendors into spending categories (Food, Transport, Shopping, etc.).
- 🤖 **Vendor Clustering:** Uses KMeans to detect patterns in your vendor spending behavior.
- 💬 **Sentiment Summarization:** Applies Hugging Face models to notes for insights into spending context.
- 📈 **Data Visualization:** Generates interactive charts with Seaborn & Matplotlib.
- 🌐 **Streamlit UI (Optional):** Can be deployed as a lightweight web app for live interaction.

## 📂 Project Structure

├── AISpendingTracker.ipynb # Main Jupyter notebook
├── financial_transactions.csv # Input transaction data (fake/simulated)
├── .gitignore # Git exclusions
├── LICENSE # MIT License
└── README.md # You are here


## 🚀 Quickstart

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/ai-spending-tracker.git
   cd ai-spending-tracker

pip install -r requirements.txt

jupyter notebook AISpendingTracker.ipynb

streamlit run AISpendingTracker.ipynb

📦 Dependencies
pandas

numpy

matplotlib

seaborn

scikit-learn

transformers (Hugging Face)

streamlit (optional, for deployment)

pip install pandas numpy matplotlib seaborn scikit-learn transformers streamlit

📘 Data
A sample CSV file (financial_transactions.csv) is provided, simulating real-world transactions with vendors, categories, and optional notes. You can replace this with your own data in the same format.

📄 License
This project is licensed under the MIT License — open source and free to use or modify.

🤝 Let's Connect
If you liked this project or have ideas to expand it (LLM Q&A, spending alerts, predictive budgeting), feel free to connect:

GitHub: Anirudh2141-DS

LinkedIn: Anirudh Reddy Ninganpally

