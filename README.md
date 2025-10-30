Problem statement:
With the rapid growth of the electric vehicle (EV) industry, analyzing and forecasting car performance, specifications, and market trends has become crucial for manufacturers, analysts, and consumers. However, raw datasets like cars_data_RAW.csv often contain inconsistent, unstructured, or incomplete information, making it difficult to extract insights or predict future patterns effectively.
🧠 Week-1: Chatbot Creation & EV Vehicle Data Analysis
📋 Project Overview

This repository contains two main parts:

Chatbot Development – a simple conversational chatbot prototype for EV-related interactions.

Data Analysis on Electric Vehicles (EVs) – preprocessing, cleaning, and exploration of electric vehicle datasets to derive insights.

The goal is to combine AI-powered conversation with data analytics to understand and communicate EV industry trends effectively.

📂 Repository Structure
Week-1/
│
├── cars_data_RAW.csv             # Original dataset before cleaning
├── cars_data_cleaned.csv         # Cleaned dataset after preprocessing
├── ev_vehicle.py                 # Python script for EV data analysis
├── charge-wise-chat-main.zip     # Chatbot project files (compressed)
└── README.md                     # Project documentation (you’re here)

⚙️ Features
🔹 Chatbot

Basic conversational chatbot using NLP concepts.

Capable of answering EV-related queries.

Customizable for integration with Hugging Face or OpenAI APIs.

🔹 EV Data Analysis

Data cleaning and preprocessing (handling missing values, outliers).

Exploratory Data Analysis (EDA) with insights on electric vehicles.

Visualizations showing trends in vehicle type, cost, and charging efficiency.

Future scope: build ML models for prediction (e.g., EV range or price).

🧰 Technologies Used
Area	Tools / Libraries
Programming Language	Python 3.x
Libraries	pandas, numpy, matplotlib, seaborn
Chatbot / NLP	streamlit, huggingface, requests
Environment	VS Code, Jupyter Notebook
Version Control	Git + GitHub
🚀 How to Run
🧩 1. Clone this repository
git clone https://github.com/JANGAMBALACHANDRAMOHANREDDY/Week-1.git
cd Week-1

⚙️ 2. Install required dependencies
pip install -r requirements.txt


(If requirements.txt doesn’t exist, install manually:)

pip install pandas numpy matplotlib seaborn streamlit python-dotenv requests

🧠 3. Run EV Analysis
python ev_vehicle.py

💬 4. Run Chatbot (after extracting zip)
unzip charge-wise-chat-main.zip
cd charge-wise-chat-main
streamlit run app.py

📊 Example Insights

Top EV Manufacturers by market share

Charging efficiency vs range analysis

Trends in EV adoption over years

Chatbot demo responding to queries like:

“Which EV has the best mileage?”
“Show stats about electric cars under ₹20L.”

🔮 Future Improvements

Integrate chatbot with live EV market data.

Build ML model to predict EV price or range.

Deploy chatbot dashboard using Streamlit Cloud or Hugging Face Spaces.

Add REST API for data access.

🧑‍💻 Author

JANGAM BALACHANDRA MOHAN REDDY
B.Tech Student | AI & Data Analyst Enthusiast

📧 Contact: jangambalachandramohanreddy@gmail.com

💼 GitHub: github.com/JANGAMBALACHANDRAMOHANREDDY

📜 License
<img width="910" height="708" alt="Screenshot 2025-10-28 173916" src="https://github.com/user-attachments/assets/58ecad50-1c37-40cd-aeef-f1baf580b4b9" />


This project is open-source and available under the MIT License.
<img width="1886" height="858" alt="image" src="https://github.com/user-attachments/assets/d4ea969d-0647-4c95-9665-3058c3cd26c1" />
