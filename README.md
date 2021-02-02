# Life-Expectancy-Prediction

## I. Intrduction

Life expectancy of humans has progressed sharply during the last 200 years. According to [Our World in Data](https://ourworldindata.org/life-expectancy), average global life expectancy in 1800 is 29 years, the life expectancy grew to 46 years in 1950. It was not until 2015 when the global average life expectancy reached 71 years. A long path was taken for humans to live longer, and we are wondering what changes possibly triggers this growth. Considering individual health conditions, national development and healthcare focus, many factors may impact life expectancy, and it's vital for the world to identify relevant factors as well as their impacting mechanisms. The project aims to leverage on Machine Learning models with relevant features to help countries identify what would be the key development factors they should focus on in improving citizens’ life expectancy.

## II. Type of Learning & Domain Definition

This prediction problem is a **supervised learning** problem, and is in the category of **regression**. Therefore, we’ll explore predictive models to investigate the relationship between the life expectancy and available healthcare/economic/social factors.

With reference to `P(T, E+ ΔE) > P(T, E)`, here goes our clarification for the life expectancy prediction problem. 
- **Task T:** Predict the life expectancy for a given country
- **Experience E:** Historical data for countries about health, economic and social factors, as well as life expectancy
- **Performance measure P:** Root Mean Squared Error (RMSE), R-Squared

The baseline model would be to use **simple summary statistics** to create predictions for the life span, such as the mean values of the independent variable (life expectancy) data. Our machine learning models will learn from the experience and improve the performance in the prediction problem.

## III. Data
The data was collected from the WHO and the UN website and is available on [Kaggle](https://www.kaggle.com/kumarajarshi/life-expectancy-who) (`Life_expectancy_data.csv`). The dataset consists of 22 columns and 2,938 rows. Each row refers to a country, and each column refers to one country level health related or economic features. The health related features include `life expectancy, adult mortality, infant deaths, alcohol drinking, hepatitis B, measles, BMI, HIV/AIDS`, etc. The economic features include `development status, percentage expenditure, GDP, population, schooling`, etc.

## Possible Findings and Implications
With the dataset, we can explore the following problems and learn insights from them.

- The impact of schooling on life expectancy. It can motivate governments, the UN, and related stakeholders to implement education-related policies and measures.
- Relationships between eating habits, lifestyles and the life span. It would provide data-driven insights and guidance for individuals to keep track of a healthy life.
- The impact of immunization coverage on life expectancy. It can inspire WHO and related organizations, governments to think about expanding the immunization coverage on certain diseases.

As the project completes, we came to reveal the relationships between life expectancy and various country-level factors, inspiring us to explore the direct pathway and useful measures for countries to help people appropriately live longer. Based on the key findings, we put forward recommendations and policy suggestions on making improvements in aspects of **healthcare development, human development and welfare improvement, education promotion, and global Support Program**.
