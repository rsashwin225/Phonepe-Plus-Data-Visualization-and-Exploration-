# PhonePe Pulse Data Visualization and Exploration

## Introduction

This project is a Streamlit web application built to explore and visualize digital payment trends in India using the PhonePe Pulse dataset. The app allows users to analyze transactions and user statistics across states, districts, years, quarters, and transaction categories.

By using interactive charts and maps, the dashboard helps identify patterns, track adoption of UPI payments, and gain insights that are useful for the fintech industry.

 Technologies Used

Python – Core programming

PostgreSQL – Database for structured storage

Pandas – Data handling and transformation

Plotly – Interactive charts and graphs

Streamlit – Web application framework

Setup & Installation

Clone the repository:

git clone <your-repo-link>
cd phonepe-dashboard


Install the dependencies:

pip install pandas psycopg2 plotly requests streamlit


Run the Streamlit app:

streamlit run app.py


Open your browser and go to:

http://localhost:8501

🎯 Features

Data Extraction – The PhonePe Pulse dataset (JSON) is processed into structured tables for easy analysis.

Database Integration – Data is stored in PostgreSQL for optimized querying.

Interactive Dashboard – A Streamlit-based interface with filters (state, year, quarter, transaction type, device brands).

Dynamic Visualizations – Plotly is used for bar charts, line graphs, scatter plots, and maps.

Geo-visualization – View UPI adoption across Indian states and districts using interactive maps.

Top Insights – Identify leading states, districts, and pincodes in terms of transaction volumes and users.

Custom Filters – Easily switch between years/quarters to track digital payment growth.

Example Use Cases

Compare UPI transaction growth between two states.

Analyze adoption trends of different transaction types (P2P, merchant payments, recharge, etc.).

Identify top-performing states/districts for business expansion opportunities.

Explore user device brand popularity in digital transactions.

Future Enhancements

Add machine learning models to predict future UPI adoption.

Include downloadable PDF/CSV reports from the dashboard.

Improve UI with custom themes and advanced filters.

Contact

If you’d like to connect or have questions:

Email: rsashwin2253@example.com

