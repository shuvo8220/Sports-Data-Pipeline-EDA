# Sports-Data-Pipeline-EDA
EDA project for internship

This project is part of a Python internship task to collect, clean, and analyze sports data using Python. I chose to work with the **Olympic History Dataset** from Kaggle, which contains athlete-level data from over 120 years of Olympic Games.

##  Project Objectives

-  Clean and organize the data
-  Perform detailed Exploratory Data Analysis (EDA)
-  Visualize meaningful patterns and trends
-  Save and share a clean dataset

##  Dataset Used

- **Source:** [Kaggle - 120 Years of Olympic History](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
- **File:** `athlete_events.csv`
- **Size:** 270,000+ rows
- **Columns:** Athlete name, sex, age, height, weight, team, sport, event, medal, etc.

##  Data Cleaning Steps

- Removed duplicate records
- Dropped rows with missing critical info (e.g., Name, Age, Year, Sport)
- Filled missing `Height` and `Weight` values using median
- Converted data types (`Age`, `Year`) to integers
- Sorted the dataset by year, team, name, and sport
- Added a new feature: `Medal_Won` (boolean)

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were created using `Matplotlib`, `Seaborn`, and `Plotly`:

1.  **Medal Count** – Bar chart showing counts of Gold, Silver, Bronze
2.  **Top 10 Sports** – By number of athletes
3.  **Gender Participation Over Time**
4.  **Number of Unique Events Over the Years**
5.  **Top 15 Participating Countries** – Using Plotly bar chart
6.  **Age Distribution**
7.  **Height vs Weight** – Scatterplot
8.  **Age Distribution in Top 5 Sports** – Boxplot
9.  **Correlation Heatmap** – Age, Height, Weight
10. **Age by Medal Type** – Violin plot
11. **Gender Ratio Pie Chart**

##  Tools & Libraries Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Google Colab

 ##  How to Run

1. Open `olympic_analysis.ipynb` in Google Colab
2. Upload the `athlete_events.csv` file
3. Run all cells to generate cleaned dataset and visualizations
4. Download `olympic_cleaned.csv` if needed
