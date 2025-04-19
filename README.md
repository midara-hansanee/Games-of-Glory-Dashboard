<h1 align="center"> <b>GAMES OF GLORY : A VISUAL ODYSSEY OF THE SUMMER OLYMPICS</b> </h1>

<h3 align="center"> <b><i> A comprehensive Power BI Dashboard for  Data Analysis of modern Summer Olympics (Sydney 2000 - Rio 2016)  </i></b> </h3>

<div align="center">
  <img height="200" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGFobnV3ODBhc2tpNHB3Z3dnang4ZnFocDRiamFoOHlyemIyaHY3eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/xqlsxbXNf5cMMWrnU6/giphy.gif"  />
</div>

<hr>

### 1. Introduction 
<p align="justify">The Games of Glory project is an interactive Power BI Dashboard that visualizes key trends from the Summer Olympics spanning from Sydney 2000 to Rio 2016. This dashboard provides comprehensive insights into athlete participation, medal distribution, event trends, and host city statistics, allowing users to analyze historical patterns and identify significant trends in the Olympic Games.

By leveraging advanced data visualization techniques, this project aims to present an intuitive and data-driven understanding of the evolution of the modern Olympic Games.</p>

<p>🤝 This project was developed by a group of second year undergraduates (4 members), as part of a university assignment for the BSc in Applied Data Science Communication degree program.</p>
<p>⚠️ Note: This project is open-source. Contributions and suggestions are welcome. Feel free to fork and adapt it for your own use. </p>
<br>

### 2. Dataset Information
* The dataset used in this project is sourced from: <a href="https://figshare.com/articles/dataset/Olympic_history_longitudinal_data_scraped_from_www_sports-reference_com/6121274?file=11693840"> Olympics History Dataset </a>

* Dataset Characteristics:
    - Initial Data Volume: 271,116 rows × 15 columns
    - Primary Attributes: Athlete demographics (Age, Gender, Height, Weight), Event participation, Medal achievements (Gold, Silver, Bronze), Host city information

<br>
 
### 3. Data Preparation & Methodology

* <b>Data Cleaning & Preprocessing : </b>
  The dataset was imported into Microsoft Power BI, where it underwent extensive cleaning and transformation, including:
    - ✅ Handling missing values and duplicates</p>
    - ✅ Establishing relationships between relevant tables</p>
    - ✅ Filtering and structuring data for optimal visualization</p>

* <b>Visualization Techniques Used : </b>
  The dashboard utilizes a variety of visualization techniques to ensure clear and interactive data analysis such as :
    - 📊 Bar Charts & Line Graphs : Trend analysis of athlete participation, performance and medal counts
    - 📊 Scatter Plots : Correlation between age and medal achievements
    - 📊 Geospatial Maps : Medal distribution patterns across different countries, Host city insights and global representation/participation.
    - 📊 Tables : Summary statistics and key athlete details
    - 📊 Slicers & Filters : Interactive filtering by country, event, year, and medal type
    - 📊 Pie Charts – Medal distribution across different categories

<br>

### 4. Dashboard Overview
The Power BI dashboard comprises six interactive pages, each designed to provide focused insights into different aspects of Olympic history.

📌 <b>Page 1: Cover Page</b>
<p>Serves as an introduction to the dashboard, setting the theme for analysis.</p>
<div align="center">
  <img src = "Dashboard - Page 1.png" />
</div>
<br>

📌 <b>Page 2: Athlete Performances Overview</b>
<p>Displays key demographic statistics (age, gender, height, weight) and their correlation with performance.</p>
<div align="center">
  <img src = "Dashboard - Page 2.png" />
</div>
<br>

📌 <b>Page 3: Medal Distribution Analysis</b>
<p>Breakdown of medals won per country, athlete, and Olympic year.</p>
<div align="center">
  <img src = "Dashboard - Page 3.png" />
</div>
<br>

📌 <b>Page 4: Sports & Events Highlights</b> 
<p>Insights into the most popular sports, win-loss records, and athlete participation trends.</p>
<div align="center">
  <img src = "Dashboard - Page 4.png" />
</div>
<br>

📌 <b>Page 5: Host City Highlights</b> 
<p>Visual representation of host city locations and country-wise participation data.</p>
<div align="center">
  <img src = "Dashboard - Page 5.png" />
</div>
<br>

📌 <b>Page 6: Conclusion Page </b>
<p>Summarizes key findings and recommendations for future analysis. </p>
<div align="center">
  <img src = "Dashboard - Page 6.png" />
</div>
<br>

<br> 

### 6. Key Insights

<p> 📉 <b> Athlete Performance Trends </b>
<br> - Michael Phelps is the most decorated athlete, with an unmatched gold medal count.
<br> - Athletes peak between ages 23-27, after which performance gradually declines.</p>

<p> 📉 <b> Gender Distribution Trends </b>
<br> - Female participation has steadily increased, reaching its highest in 2016.
<br> - Male participation has slightly declined over the years.</p>

<p> 📉 <b> Global Medal Distribution and Performances </b>
<br> - The United States consistently leads in medal counts.
<br> - China showed a significant rise in medals in 2008, indicating growing dominance.</p>

<p> 📉 <b> Popular Sports & Events </b>
<br> - Swimming and Athletics have the highest participation and medal-winning opportunities.</p>

<br>

### 7. Future Scope
<p>To further enhance the analysis, potential areas of exploration include:
<br>📌 The impact of economic & training conditions on athlete performance
<br>📌 Advancements in sports science & technology and their role in breaking Olympic records
<br>📌 Comparing Winter & Summer Olympics to analyze global sports trends
<br>📌 Building predictive models for future Olympic performances</p>

<br>

## Documentation
This repository includes :
- Power BI dashboard file
- Technical Report with implementation details
- Images of the Dashboard (Page 1 - 6)

<br> 

## References
 
1. R. Griffin, *Olympic History – Web Scraping & Data Wrangling*, available at:  
   - [Part 1: Web Scraping](https://rgriff23.github.io/2018/05/27/olympic-history-1-web-scraping.html)  
   - [Part 2: Data Wrangling](https://rgriff23.github.io/2018/05/28/olympic-history-2-data-wrangling-1.html)  
   - [Part 3: Advanced Data Wrangling](https://rgriff23.github.io/2018/05/28/olympic-history-3-data-wrangling-2.html)  
2. Olympstats, *Historical Olympic Data*, available at:  
   - [Olympic Statistics & Medal Counts](http://olympstats.com/2016/08/21/the-olymadmen-and-olympstats-and-sports-reference/)  
3. Power BI Learning Resources:  
   - [Power BI Dashboard Design Tips](https://learn.microsoft.com/en-us/power-bi/create-reports/service-dashboards-design-tips)  
   - [Power BI Dashboard Tutorial – DataCamp](https://www.datacamp.com/tutorial/power-bi-dashboard-tutorial)  
4. Official Dataset:  
   - [Figshare – Olympic History Dataset](https://doi.org/10.6084/m9.figshare.6121274.v1)  


<br> 
