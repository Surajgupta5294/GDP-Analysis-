# GDP-Analysis-

🌍 GDP Analysis Project
This project provides a comprehensive analysis of global GDP trends from 1960 to 2016 using Python libraries such as pandas, matplotlib, seaborn, and Plotly. The dataset includes GDP values for countries and regions around the world.

📁 Dataset
.Source: gdp.csv

.Fields:

   .Country Name: Name of the country or region

   .Country Code: ISO country code

   .Year: The year of the GDP value

   .Value: GDP in current US dollars

📊 Key Features
.Null Value Check & Summary Statistics: Basic data inspection and column descriptions

.Arab World GDP Growth Calculation: Specific analysis of GDP trends in the Arab World

.Global GDP Growth Computation: Calculates yearly GDP growth for every country

.Top/Bottom Growth Insights: Identifies countries with the highest and lowest GDP growth

.Visualization Dashboards:

  .World GDP trend over time

  .Country-wise GDP comparisons (India, China, USA, etc.)

  .Top 20 countries by GDP

  .Line plots of GDP for all countries

  .Comparative GDP trends between specific countries

📈 Visualizations
Interactive plots created using Plotly Express:

 .Line plots for historical GDP trends

 .Bar charts for top GDP countries

 .Comparative graphs between countries like India, China, and the USA

🛠️ How to Use
1 Clone the repository
git clone https://github.com/Surajgupta5294/gdp-analysis.git
cd gdp-analysis

2 Install dependencies
pip install pandas numpy matplotlib seaborn plotly

3 Run the script
python gdp_analysis.py

4 Open output
The script will display interactive plots directly in your browser or IDE.

🧮 Dependencies
. pandas
. numpy
. matplotlib
. seaborn
. plotly

📌 Notes
 . The script calculates GDP growth as the percentage change year-over-year.
 
 . Ensure gdp.csv is in the same directory as the script before execution.

📃 License
This project is licensed under the MIT License.
