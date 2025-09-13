🌍 Life Expectancy & GDP Analysis (2000–2015)

This project explores the relationship between life expectancy and GDP across six countries — Chile, China, Germany, Mexico, United States, and Zimbabwe — over the period 2000–2015.

Using pandas, seaborn, and matplotlib, we clean the dataset, generate descriptive summaries, analyze correlations, and visualize trends to understand how economic growth aligns with public health outcomes.

📂 Project Structure
.
├── all_data.csv                  # Dataset with life expectancy & GDP (2000–2015)
├── data_viz_basics_project.ipynb # Notebook with step-by-step EDA & plots
├── plt_project.ipynb             # Additional Matplotlib/Seaborn experiments
├── saved_images/                 # Exported charts (PNG files)
├── README.md                     # Project documentation

🔑 Key Steps

Data Cleaning & Preparation

Rename long columns to simpler names (life_expectancy, gdp, year, country).

Ensure numeric datatypes for GDP & life expectancy.

Confirm no missing values.

Descriptive Insights

Track changes in life expectancy by country.

Compute GDP growth rates (CAGR).

Compare starting vs ending values across 15 years.

Correlation Analysis

Compute correlations between log(GDP) and life expectancy.

Test strength of association per country.

Visualizations

📈 Life expectancy over time (line plots)

💰 GDP trends over time (log scale)

🔄 Relationship: GDP vs Life expectancy (scatterplots)

🗂️ Per-country mini trends (facet grid)

📊 Key Findings

China: GDP grew at ~15.9% annually, life expectancy rose +4.4 years.

Zimbabwe: Life expectancy rebounded +14.7 years despite modest GDP growth.

USA & Germany: Stable economies, modest improvements in life expectancy.

Chile & Mexico: Steady but smaller gains compared to China.

Correlation: Across all six countries, log(GDP) strongly correlates with life expectancy (0.92–0.98).

🛠️ Tech Stack

Python 3.x

Pandas – data wrangling

NumPy – numerical operations

Matplotlib / Seaborn – visualization

🚀 How to Run

Clone the repository and open the notebook:

git clone https://github.com/yourusername/life-expectancy-gdp.git
cd life-expectancy-gdp
jupyter notebook data_viz_basics_project.ipynb


Install dependencies if needed:

pip install pandas numpy matplotlib seaborn

📌 Takeaway

This project demonstrates how combining economic indicators (GDP) with health outcomes (life expectancy) can reveal meaningful trends:

Wealthier countries tend to live longer, but gains flatten at higher GDP levels.

Even with modest GDP growth, targeted improvements (like Zimbabwe’s rebound) can yield dramatic health outcomes.