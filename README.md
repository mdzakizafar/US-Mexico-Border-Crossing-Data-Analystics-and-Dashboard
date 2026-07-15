# 🌎 US–Mexico Border Crossing Data Analytics and Dashboard

## 📌 Project Overview

The **US–Mexico Border Crossing Data Analytics and Dashboard** is a data analysis and visualization project developed using **Microsoft Power BI**.

This project analyzes border-crossing data between the **United States and Mexico** to identify important trends, patterns, and insights related to the movement of passengers, pedestrians, vehicles, trucks, buses, and other transportation categories.

The interactive dashboard transforms raw border-crossing data into meaningful visualizations, making it easier to analyze crossing volumes across different ports, states, transportation measures, and time periods.

This project demonstrates practical skills in **data cleaning, data transformation, exploratory data analysis, Power Query, DAX, data visualization, and interactive dashboard development**.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze the total number of border crossings.
* Examine border-crossing trends over time.
* Compare crossing volumes across different U.S. states.
* Identify the busiest border ports.
* Analyze crossings based on transportation categories.
* Compare passenger, pedestrian, and vehicle movement.
* Identify seasonal and yearly crossing patterns.
* Create an interactive dashboard for effective data exploration.
* Transform complex border-crossing data into meaningful insights.

---

## 📊 Dashboard Preview

The dashboard provides an interactive overview of US–Mexico border-crossing data using:

* KPI cards
* Line charts
* Bar charts
* Column charts
* Donut or pie charts
* Map visualizations
* Tables and matrices
* Interactive filters and slicers

> Add a screenshot of your dashboard to the repository with the filename `dashboard.png`.

Then add the following line to display it:

```markdown
![US-Mexico Border Crossing Dashboard](dashboard.png)
```

---

## 📈 Key Performance Indicators

The dashboard may include important KPIs such as:

| KPI                     | Description                                                  |
| ----------------------- | ------------------------------------------------------------ |
| Total Crossings         | Total number of recorded border crossings                    |
| Total Ports             | Number of border ports included in the analysis              |
| Total States            | Number of U.S. border states represented                     |
| Average Crossing Volume | Average number of crossings across records                   |
| Busiest Port            | Port with the highest border-crossing volume                 |
| Top Crossing Category   | Transportation category with the highest number of crossings |

---

## 🚦 Border-Crossing Categories

The dataset includes different types of border crossings, such as:

* 🚶 Pedestrians
* 🚗 Personal vehicles
* 👥 Personal vehicle passengers
* 🚌 Buses
* 🧑‍🤝‍🧑 Bus passengers
* 🚛 Trucks
* 📦 Truck containers
* 🚆 Trains
* 🚃 Train passengers

These categories help analyze how people, vehicles, and commercial transportation move across the US–Mexico border.

---

## 📊 Dashboard Visualizations

### 📅 Border Crossings Over Time

Analyzes changes in border-crossing volume across different years and months.

This visualization helps identify:

* Long-term crossing trends
* Increases or decreases in border activity
* Seasonal patterns
* Periods with unusually high or low crossing volumes

### 🗺️ Border Crossings by State

Compares total border-crossing volumes across U.S. states located along the Mexico border.

The analysis may include:

* California
* Arizona
* New Mexico
* Texas

This visualization helps identify states with the highest levels of border activity.

### 🏢 Border Crossings by Port

Analyzes crossing activity across different ports of entry.

This visualization helps identify:

* The busiest border ports
* Ports with lower crossing volumes
* Differences in traffic among locations
* Major transportation and trade routes

### 🚗 Border Crossings by Transportation Measure

Compares different border-crossing categories, including:

* Pedestrians
* Personal vehicles
* Personal vehicle passengers
* Trucks
* Buses
* Trains

This analysis helps determine which transportation categories contribute the most to total border movement.

### 📆 Monthly Border-Crossing Trends

Displays border-crossing activity by month.

This visualization helps identify:

* Seasonal changes
* Peak crossing months
* Months with lower crossing activity
* Recurring travel and transportation patterns

### 📈 Yearly Border-Crossing Trends

Analyzes changes in crossing volume over multiple years.

This visualization helps understand:

* Growth in border activity
* Long-term transportation trends
* Major changes in crossing patterns

---

## 🛠️ Tools and Technologies Used

| Tool or Technology  | Purpose                                               |
| ------------------- | ----------------------------------------------------- |
| Microsoft Power BI  | Interactive dashboard creation and data visualization |
| Power Query         | Data cleaning and transformation                      |
| DAX                 | Creating measures, calculated columns, and KPIs       |
| Microsoft Excel/CSV | Dataset storage and management                        |
| Data Modeling       | Organizing data for efficient analysis                |
| Git                 | Version control                                       |
| GitHub              | Source-code hosting and project documentation         |

---

## 🧹 Data Cleaning and Preparation

The dataset was cleaned and transformed using **Power Query** before dashboard development.

The data-preparation process included:

* Removing unnecessary columns
* Checking for missing values
* Handling null values
* Identifying and removing duplicate records
* Correcting column data types
* Renaming columns for improved readability
* Standardizing state and port names
* Formatting date columns
* Extracting year and month information
* Preparing numerical columns for analysis
* Creating calculated columns and DAX measures

---

## 🧮 Example DAX Measures

The following DAX measures can be used to calculate important dashboard metrics.

### Total Border Crossings

```DAX
Total Crossings =
SUM('Border Crossing Data'[Value])
```

### Average Border Crossings

```DAX
Average Crossings =
AVERAGE('Border Crossing Data'[Value])
```

### Total Ports

```DAX
Total Ports =
DISTINCTCOUNT('Border Crossing Data'[Port Name])
```

### Total States

```DAX
Total States =
DISTINCTCOUNT('Border Crossing Data'[State])
```

### Maximum Crossing Volume

```DAX
Maximum Crossings =
MAX('Border Crossing Data'[Value])
```

> Table and column names may need to be changed according to the actual names used in the Power BI dataset.

---

## 📂 Project Structure

```text
US-Mexico-Border-Crossing-Data-Analystics-and-Dashboard/
│
├── US Mexico Border Crossing Dashboard.pbix
├── Border Crossing Dataset.csv
├── dashboard.png
└── README.md
```

> The actual filenames may be different depending on the files available in the repository.

---

## 💡 Key Insights

The dashboard can help identify insights such as:

* Border-crossing activity varies significantly across different states and ports.
* Some ports handle substantially higher crossing volumes than others.
* Personal vehicles and passengers contribute significantly to total border movement.
* Texas contains several major border-crossing locations.
* Border-crossing activity changes over different months and years.
* Transportation categories show different trends depending on location and time.
* Interactive filters make it easier to analyze specific states, ports, years, and crossing measures.

---

## 🎛️ Interactive Dashboard Features

Users can interact with the dashboard using:

* State filters
* Port filters
* Year filters
* Month filters
* Transportation-category filters
* Date slicers
* Interactive charts
* Cross-filtering between visualizations

These features allow users to explore border-crossing data from multiple perspectives.

---

## ▶️ How to Use the Dashboard

### 1. Clone the repository

```bash
git clone https://github.com/mdzakizafar/US-Mexico-Border-Crossing-Data-Analystics-and-Dashboard.git
```

### 2. Open the project directory

```bash
cd US-Mexico-Border-Crossing-Data-Analystics-and-Dashboard
```

### 3. Install Microsoft Power BI Desktop

Download and install **Microsoft Power BI Desktop** if it is not already installed.

### 4. Open the Power BI file

Locate the `.pbix` file and open it using Microsoft Power BI Desktop.

### 5. Explore the dashboard

Use the available:

* Filters
* Slicers
* KPI cards
* Charts
* Maps
* Tables

to interact with the dashboard and explore border-crossing trends.

---

## 🎯 Skills Demonstrated

This project demonstrates practical knowledge of:

* Data Analytics
* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Microsoft Power BI
* Power Query
* DAX
* Data Modeling
* KPI Development
* Interactive Dashboard Design
* Data Visualization
* Business Intelligence
* Trend Analysis
* Data Storytelling

---

## 🔮 Future Improvements

The following improvements may be added in the future:

* Add year-over-year growth analysis
* Include month-over-month comparisons
* Add forecasting for future border-crossing volumes
* Add detailed state-level dashboard pages
* Include port-level drill-through analysis
* Add advanced tooltip pages
* Add transportation-category comparisons
* Improve dashboard navigation
* Add dynamic dashboard titles
* Include additional border and trade datasets
* Publish the dashboard using Power BI Service
* Add more recent border-crossing data

---

## 👨‍💻 Author

**Md Zaki Zafar**

B.Tech – Computer Science and Engineering
Data Science Specialization
Lovely Professional University

GitHub:
https://github.com/mdzakizafar

---

## 🤝 Contributions

Suggestions and improvements are welcome.

To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make the required improvements.
4. Commit your changes.
5. Push the branch to GitHub.
6. Create a Pull Request.

---

## ⭐ Support

If you find this US–Mexico Border Crossing Data Analytics and Dashboard project useful, consider giving the repository a ⭐.

Thank you for visiting the project!
