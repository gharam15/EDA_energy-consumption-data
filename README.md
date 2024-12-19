⚡ Energy Consumption Dashboard
🌟 Project Overview
The Energy Consumption Dashboard is an interactive data visualization tool designed to analyze and optimize energy consumption patterns across different regions and time periods. By leveraging Python, Dash, and Plotly, the project provides insights into energy usage trends, identifies cost-saving opportunities, and highlights the impact of time and region on energy consumption.

✨ Key Features
📊 Interactive Visualizations:

Displays energy consumption trends across different regions and times of the day.
Line and bar charts to compare energy usage before and after optimization thresholds.
💡 Energy Optimization:

Applied threshold-based analysis to identify and shut down low-consumption cells.
Calculated potential savings in both kilowatt-hours (kWh) and cost (EGP).
📈 Statistical Analysis:

Conducted ANOVA tests to determine:
Whether regions significantly impact energy consumption.
If time of day correlates with energy consumption patterns.
💰 Cost Savings:

Developed methods to calculate total energy costs before and after applying optimization techniques.
Achieved measurable cost savings by reducing low-consumption cells.
🛠 Tools and Technologies
🖥 Programming Language: Python
📦 Libraries:
Dash: For building interactive web applications.
Plotly: For creating interactive visualizations.
Pandas: For data cleaning, preprocessing, and manipulation.
Scipy/Statsmodels: For statistical hypothesis testing (e.g., ANOVA).
📂 Data:
Energy consumption datasets including regions, time of day, and energy prices.
🛤 Methodology
🔍 Data Cleaning:

Fixed missing and inconsistent data (e.g., NaN values, outliers).
Standardized the DateTime column to enable proper grouping and analysis.
📊 Exploratory Data Analysis (EDA):

Visualized energy consumption trends by region and time of day.
Identified outliers and anomalies in the data.
⚙️ Threshold Optimization:

Calculated the 25th percentile of energy consumption as the threshold.
Shut down cells with energy consumption below the threshold.
📉 Statistical Analysis:

Conducted ANOVA to validate:
The relationship between regions and energy consumption.
The relationship between time of day and energy consumption.
📈 Visualization and Reporting:

Created an interactive Dash application to visualize trends and findings.
Compared energy consumption and cost savings before and after optimization.
🚀 How to Run the Project
📥 Clone the Repository:
Copy code
git clone https://github.com/gharam15/energy-consumption-dashboard.git
cd energy-consumption-dashboard
🔧 Install Dependencies: Ensure you have Python installed. Then install the required libraries:
Copy code

pip install -r requirements.txt
▶️ Run the Dashboard: Execute the following command to start the Dash app:
Copy code
python app.py
Open your browser and navigate to http://127.0.0.1:8050/ to interact with the dashboard.

📊 Results and Insights
🌍 Regional Differences:

Energy consumption varies significantly across regions, highlighting the need for tailored strategies.
⏰ Time-of-Day Trends:

Peak energy usage occurs during the afternoon, indicating high activity in residential and commercial areas.
💵 Cost Savings:

By applying the threshold to shut down low-consumption cells, significant cost savings were achieved.

📬 Contact
For any questions or contributions, feel free to reach out:

📛 Name: Gharam Ahmed Mokhtar
📧 Email: garamahmedmokhtar@gmail.com
🌐 GitHub: https://github.com/gharam15
