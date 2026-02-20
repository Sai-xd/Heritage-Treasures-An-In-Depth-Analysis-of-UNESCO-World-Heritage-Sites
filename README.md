🌍 Heritage Treasures: An In-Depth Analysis of UNESCO World Heritage Sites
📌 Project Overview
This project presents a comprehensive data analysis and visualization of UNESCO World Heritage Sites using Tableau and Flask-based web integration. The dashboard provides insights into regional distribution, category classification, danger status, and inscription trends of heritage sites across the world.

The project combines data preprocessing, interactive dashboards, and web deployment to deliver meaningful visual analytics.

🎯 Objectives
Analyze global distribution of UNESCO World Heritage Sites
Identify region-wise and category-wise patterns
Study inscription trends over years
Highlight sites that are in danger
Integrate Tableau dashboard into a responsive website using Flask
🛠️ Technologies Used
Tableau – Data Visualization
Python (Flask) – Web Integration
HTML, CSS, Bootstrap – Frontend Design
GitHub – Version Control
UNESCO Dataset (2021) – Data Source
📊 Dashboard Features
🌎 Countries per Region
📈 Regional Inscription Trends
🏛 Category-wise Distribution (Cultural, Natural, Mixed)
⚠ Danger Status Analysis
🗺 World Map Visualization
🌐 Country-wise Heritage Site Counts
🔄 Data Preprocessing Steps
Cleaned dataset using Data Interpreter
Renamed columns:
name → Site_Name
country → Country
date_inscribed → Year_Inscribed
danger → Danger_Status
category_long → Category
Fixed data types (Country as String, Year_Inscribed as Integer)
Removed null and inconsistent values
Created calculated fields for analysis
🏗 Project Architecture
Data Collection (UNESCO Dataset)
Data Cleaning & Transformation
Tableau Dashboard Creation
Flask Web Integration
Deployment via GitHub
