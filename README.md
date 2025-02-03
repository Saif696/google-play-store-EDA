# Google Playstore Dataset Exploratory Data Analysis (EDA)

## Overview
This project focuses on performing exploratory data analysis (EDA) on the Google Playstore dataset. The goal is to uncover meaningful insights, clean and preprocess data for analysis, and visualize patterns and trends. This analysis will highlight app characteristics, user behavior, and market trends.

## Dataset Description
The dataset contains information about Google Playstore apps, including:
- **App**: Name of the app.
- **Category**: App category.
- **Rating**: Average user rating.
- **Reviews**: Number of reviews received by the app.
- **Size**: App size (e.g., MB, KB, or "Varies").
- **Installs**: Number of app installs.
- **Type**: App type (Free or Paid).
- **Price**: Price of the app.
- **Content Rating**: Age group for which the app is suitable.
- **Genres**: App genres.
- **Last Updated**: Date when the app was last updated.
- **Current Ver**: Current version of the app.
- **Android Ver**: Minimum Android version required.

### Key Dataset Details:
- **Rows**: 10,841
- **Columns**: 13
- **Missing Values**: Present in some columns like `Rating`, `Type`, `Content Rating`, etc.

## Objectives
The objectives of this EDA are:
1. Understand the structure of the dataset.
2. Perform data cleaning and preprocessing:
   - Handle missing values.
   - Transform categorical and numerical data.
   - Parse and standardize dates and sizes.
3. Analyze key metrics such as:
   - Rating distribution.
   - Popular categories and genres.
   - Relationships between app pricing, installs, and ratings.
   - Impact of content rating on app downloads.
4. Visualize trends and insights through plots and graphs.

## Tools and Libraries
The analysis will be conducted using:
- **Python**
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

## Steps
1. **Data Exploration**:
   - Examine column types and distributions.
   - Identify and address missing values.
2. **Data Cleaning**:
   - Convert `Reviews`, `Installs`, and `Price` columns to numeric types.
   - Standardize `Size` column.
3. **Analysis and Visualization**:
   - Identify top-performing app categories and genres.
   - Analyze trends in pricing, installs, and ratings.
   - Correlation analysis between numerical features.
4. **Insights and Documentation**:
   - Summarize key findings.
   - Prepare actionable insights based on analysis.

## Findings and Insights
### **1. Category-Wise Analysis**
- The most popular app categories are those related to entertainment, social media, and productivity.
- Categories with the highest total installs include **Game, Communication, and Social Apps**, indicating their widespread user demand.
- Certain niche categories, such as **Business and Medical**, have fewer installs but may have a dedicated user base.

### **2. Correlation Analysis**
- **Installs & Reviews (0.64)**: There is a moderate positive correlation, meaning apps with more installs tend to have more reviews.
- **Installs & Rating (0.045)**: Almost no correlation, indicating that high installs do not necessarily mean high ratings.
- **Reviews & Rating (0.063)**: Very weak correlation, meaning the number of reviews does not strongly impact ratings.
- This suggests that while popular apps get more reviews, high install numbers do not always translate into high ratings.

## Expected Outcomes
- Cleaned and preprocessed dataset for further use.
- Visualizations to illustrate trends and insights.
- Comprehensive analysis of factors influencing app success on Google Playstore.

## Next Steps
1. Perform data cleaning and transformation.
2. Generate initial visualizations for key metrics.
3. Document findings and insights.

---

### Author
This project is part of the portfolio-building initiative by [Saif Ullah].
