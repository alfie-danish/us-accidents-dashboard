# 💥 Accidents in the USA - Moving Average Dashboard

![Dashboard image](https://github.com/alfie-danish/us-accidents-dashboard/blob/main/assets/dashboard-tableau.png?raw=true)

## ☀️ Overview
#### 🔗 [View Dashboard in Tableau](https://public.tableau.com/views/USAccidents-MovingAverageDashboard/Dashboard?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)

The **Accidents in the USA - Moving Average Dashboard** is a powerful tool for those interested in understanding and preventing road accidents in the United States. With its comprehensive overview of accident data, the dashboard allows users to gain valuable insights into various aspects of accidents, including frequency, severity, and timing.

The dashboard utilizes a variety of data visualizations to present complex information in an easily digestible format. For example, the moving average chart allows users to see trends in accident frequency over time, while the heatmap provides a visual representation of the relationship between temperature and time of day with respect to accident occurrence. Furthermore, the dashboard allows users to filter the data by severity level or period of day, providing deeper insights into specific aspects of the data.

Behind the scenes, the dashboard is powered by a combination of Python and Tableau. The interactive elements of the dashboard, such as the date range highlighting and dynamically updating titles, make it a user-friendly and engaging experience.

Overall, the **Accidents in the USA - Moving Average Dashboard** is an essential tool for anyone interested in understanding and preventing road accidents. By providing valuable insights into accident trends and patterns, the dashboard empowers users to make informed decisions about road safety and take action to reduce the risk of accidents on our roads.

## 🚀 Project Details
##### Tech stack:
- [Python](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- [Tableau](https://www.tableau.com/)

##### Higlights
- [Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) acquisition, engineering and cleaning performed using Python. The Python code can be found [here](https://github.com/alfie-danish/us-accidents-dashboard/blob/main/notebooks/get-data.ipynb).
- Moving Average line chart provides user interactivity by allowing for date range highlighting
- Titles update dynamically with the selected date range, period and duration. These dynamically change upon user selection from the Filter section and/or highlighting date range within the line chart
- Data in all charts updates based on user selection
- Both line and heatmap charts provide additional bar charts in tooltip upon hovering on data points

##### The types of charts used in this dashboard are as follows:
- Moving Average Line Chart
- Scorecard
- Horizonatal Bars
- Heatmap

##### Filters included are:
- Interactive Date Highlighting within Moving Average chart
- Moving Average Duration
- Moving Average Period
- Data Date Range

## 🛢 Resources / References
- [Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- [Tableau platform](https://www.tableau.com/)
- [Python](https://www.python.org/)
- Dashboard inspired by [London Bike Rides Dashboard](https://public.tableau.com/app/profile/mo.chen/viz/LondonBikeRides-MovingAverageandHeatmap/Dashboard)

