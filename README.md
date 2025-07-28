📈 Tech Stock Analysis Dashboard (Apple, Google, Amazon, Microsoft)

A dynamic stock market dashboard created using Python to analyze and visualize stock performance of 4 major S&P 500 tech companies — Apple, Google, Amazon, and Microsoft. The dashboard presents key financial trends like moving averages, daily returns, and resampled closing prices.

🔍 Purpose

This dashboard enables users to interactively explore stock price behavior of leading tech companies. It offers time series analysis using pandas and helps understand volatility, trends, and average performance over time.

🧰 Tech Stack

• 🐍 Python
• 📊 Pandas & NumPy – for data handling
• 📉 Matplotlib & Seaborn – for visualizations
• 📒 Jupyter Notebook – for development
• 🖥️ Streamlit / Python script – for dashboard creation
• 📁 Dataset – Individual CSVs per company (5-year daily data)

📂 Data Source

The dataset was taken from Kaggle:
🔗 https://www.kaggle.com/datasets/camnugent/sandp500

It includes 5 years of historical daily stock price data for the following 4 companies:

🍏 Apple (AAPL)

🔍 Google (GOOGL)

🛒 Amazon (AMZN)

💻 Microsoft (MSFT)

Each dataset contains: Date, Open, High, Low, Close, Volume

🎯 Features & Highlights

• 📌 Business Problem
Retail investors and data learners often struggle to interpret raw historical price data across multiple companies.

• 🎯 Project Goals

Explore and visualize price movement of 4 companies

Calculate and display daily returns and moving averages

Allow frequency-based resampling (Monthly, Quarterly, Yearly)

Enable user to switch between companies interactively

🖼️ Walkthrough of Visuals

1️⃣ Closing Price Over Time (Apple Example)
 ![Dashboard Preview](https://github.com/AshleshaAhirkar/Stock-Price-Analysis/blob/main/Analysis1.png)



2️⃣ Moving Averages (10, 20, 50 days)


3️⃣ Daily Returns for Selected Company


4️⃣ Resampled Closing Price (Monthly, Quarterly, Yearly)


💼 Business Impact

📊 Investors can visually assess performance and volatility

🧑‍🎓 Students gain hands-on experience with time-series analysis

💻 Developers can reuse logic for other stocks or dashboards

📦 Note

Only 4 companies analyzed (not full S&P500)

Large files or datasets are bundled inside the uploaded .zip file


