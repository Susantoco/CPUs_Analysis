# CPUs_Analysis  
**Probability and Statistics**

In this analysis, we investigate the relationships between CPU specifications and their cache size characteristics, with a focus on **power** consumption. The analysis was conducted using Python, primarily leveraging **Pandas** for data handling and **statistical methods** including ANOVA and Linear Regression.

### Tools and Techniques Used:
- **Pandas**: For data cleaning, preprocessing, and exploratory data analysis (EDA).
- **ANOVA (Analysis of Variance)**: Used to analyze differences in CPU power consumption across different categorical groups, such as CPU families or architecture types.
- **Linear Regression (LR)**: Applied to model and predict **CPU cache size** based on numerical features such as the number of threads and recommended customer price.

### Workflow Overview:
1. **Data Cleaning**  
   - Removed missing or inconsistent data entries  
   - Converted data types appropriately  
   - Detected and handled outliers

2. **Exploratory Data Analysis (EDA)**  
   - Used descriptive statistics, histograms, and boxplots  
   - Analyzed correlation between features  
   - Visualized relationships through scatter plots and heatmaps

3. **Statistical Testing**  
   - **ANOVA** was employed to test whether CPU power significantly differs between different CPU categories (e.g., by brand or technology generation)

4. **Modeling with Linear Regression**  
   - Built a multiple linear regression model to estimate **CPU cache size** based on numerical predictors: number of threads and recommended customer price  
   - Evaluated model performance using **R-squared** and **p-values** to assess goodness of fit and statistical significance

5. **Insights**  
   - Identified key factors that influence CPU power  
   - Found statistically significant differences in power usage among CPU types

---

Let me know if you’d like to add code snippets, graphs, or a summary of results!
