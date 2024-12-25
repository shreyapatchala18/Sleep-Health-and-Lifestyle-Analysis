# **Sleep Health and Lifestyle Analysis** 🛌

## **Project Overview**

This project explores the relationships between sleep disorders, stress levels, and sleep duration across various age groups using the Sleep Health and Lifestyle dataset. Through advanced visualizations and data analysis, the project highlights key insights into how sleep patterns and stress interact, offering actionable takeaways for understanding sleep health.

The project delivers:
- **Clear visual trends** showcasing the impact of sleep disorders on stress and sleep duration.
- **Age-group segmentation** for targeted analysis.
- **Actionable insights** to support health-related studies and recommendations.

## **Dataset Description**

The analysis is based on the **Sleep Health and Lifestyle Dataset**, which includes attributes such as:
- **Sleep Duration**: Hours of sleep logged daily.
- **Stress Level**: Self-reported stress levels.
- **Sleep Disorder**: Diagnoses of disorders like insomnia and sleep apnea.
- **Age Group**: Segmented into Young, Middle-Aged, Older Adult, and Senior categories.

**Source**: [Kaggle Sleep Health Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/data)

## **Tools and Technologies**

- **Language**: R
- **Libraries**:
  - `ggplot2` for creating insightful visualizations.
  - `patchwork` for combining multiple plots.
  - `gghighlight` for emphasizing key trends.
  - `tidyr` and `dplyr` for data cleaning and transformation.

## **Key Findings**

- **Stress Reduction**: Stress levels consistently decrease with increasing sleep duration across all disorders.
- **Insomnia Impact**: Individuals with insomnia show the **highest stress levels** and **shortest sleep durations**, particularly in the Young and Middle-Aged groups.
- **Age Group Trends**: Sleep duration and stress patterns vary significantly across age groups, with insomnia disproportionately affecting younger demographics.

## **Visualizations**

1. **Line Plot**: Shows the relationship between sleep duration and stress levels, segmented by sleep disorder.
2. **Box Plot**: Highlights the distribution of stress levels across different sleep disorders.
3. **Stacked Bar Plot**: Visualizes average sleep duration and stress levels by age group and disorder.

## **How to Run**

1. **Prerequisites**:
   - Install R and RStudio.
   - Install required libraries: `ggplot2`, `patchwork`, `gghighlight`, `tidyr`, and `dplyr`.

2. **Execution**:
   - Load the `Sleep_health_and_lifestyle_dataset.csv` file.
   - Run the provided R script to generate visualizations and insights.
