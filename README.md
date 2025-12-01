COVID-19 South Korea Exploratory Data Analysis (EDA)

📌 Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on the COVID-19 dataset from South Korea (early to mid-2020). The goal is to understand the spread of the virus through various demographic, geographic, and environmental lenses.

The analysis investigates relationships between infection rates and factors such as age, gender, region, and weather conditions to derive meaningful insights into the pandemic's dynamics.

📂 Dataset

The project utilizes a rich set of time-series and static data files located in the corona 20 directory.

Key Datasets Used:

TimeAge.csv: Time series data of patients by age group.

TimeProvince.csv: Time series data of cases by administrative region.

TimeGender.csv: Time series data of patients by gender.

Weather.csv: Time series data on weather conditions in each region.

Additional Available Data:

Region.csv (Metadata), Time.csv (Test results), Case.csv (Infection cases), PatientInfo.csv (Patient profiles), SeoulFloating.csv (Population mobility), SearchTrend.csv (Search keywords), Policy.csv (Government policies).

📊 Key Analyses & Insights

1. Demographic Analysis (Age)

Infection Rates: The 20s age group showed the highest number of confirmed cases. This is attributed to higher social activity, educational mobility (universities), and social behaviors.

Mortality Rates: Mortality is strongly correlated with age. The 80s age group has the highest number of deceased cases, with mortality decreasing as age decreases. Notably, there were zero recorded deaths in the 20s age group during the analysis period.

2. Geographic Analysis (Region)

Epicenter: Daegu was identified as the epicenter, accounting for approximately 53-60% of confirmed cases, followed by Gyeongsangbuk-do.

Trends: The curve for Daegu flattened significantly after March 2020, while other regions showed different growth patterns over time.

3. Gender Analysis

Infection vs. Mortality: While females had a higher number of confirmed cases compared to males, males exhibited a higher number of deceased cases.

4. Environmental Analysis (Weather)

Temperature Correlation: A weak negative correlation was observed between average temperature and the number of cases, suggesting that colder environments might facilitate higher infection rates.

Other Factors: No significant correlation was found between maximum wind speed or humidity levels and the spread of the virus.

🛠️ Technologies & Libraries

The analysis was performed using Python within a Jupyter Notebook environment.

Python 3

Pandas: Data manipulation and cleaning.

NumPy: Numerical computations.

Matplotlib & Seaborn: Data visualization and plotting.

OS: File path handling.

🚀 Getting Started

Prerequisites

Ensure you have Python installed along with the following packages:

pip install pandas numpy matplotlib seaborn


Running the Analysis

Clone this repository.

Ensure the dataset files are placed in a folder named corona 20 (or adjust the paths in the notebook accordingly).

Open Corona19 EDA.ipynb in Jupyter Notebook or JupyterLab.

Run all cells to reproduce the analysis and visualizations.

📈 Visualizations

The notebook includes various visualizations such as:

Bar charts comparing cases and deaths by age group.

Time-series line plots tracking the progression of cases.

Pie charts showing the regional distribution of cases.

Box plots for outlier detection in weather data.

Subplots correlating weather patterns with infection rates across provinces.

🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.

📝 License

This project is open-source and available for educational and research purposes.
