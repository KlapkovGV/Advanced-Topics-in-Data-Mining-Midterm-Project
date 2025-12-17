# Advanced-Topics-in-Data-Mining-Midterm-Project
This project performs an analysis of the "1000 Drugs and Side Effects" dataset from Kaggle. The analysis includes statistical summaries, data visualizations, correlation analysis, and clustering techniques to explore relationships between drugs, side effects, patient demographics, and treatment outcomes.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wCWNfjsm51Yl7rtoCeh-5MjP2C6C0gJC?usp=sharing)

## Dataset Description

The dataset contains information on 1,000 real-world pharmaceutical drugs. It includes key details such as drug names, categories, chemical formulas, dosage forms, mechanisms of action, therapeutic uses, side effects, and manufacturer information.

## Analysis Performed

The following questions are addressed in this project:

1. Calculate basic statistics for all numerical columns: mean, std, min, 25%, median, 75%, and max.
2. Visualize the data in categorical columns with pie charts separately for each column.
3. The Condition column contains the disease cause. Visualize the distribution of treatment duration (Treatment_Duration_days) corresponding to these causes on a single boxplot.
4. Draw a 2D histogram (or an appropriate 2D frequency visualization) for the Drug_Name and Side_Effects columns and interpret the results.
5. For the data you used in the previous question (item 4), perform hierarchical clustering using the clustermap function from the seaborn library. Interpret the resulting graph and write your interpretations in markdown cells.
6. Calculate the correlation between Age and Improvement_Score variables and interpret the result.
7. Calculate the disease (Condition) rates for men and women in a normalized manner. (For example, you can create a probability distribution such that the total for each gender equals 1.)
8. For which drugs has the side effect of dizziness been reported? Sort these drugs by descending frequency.
9. For the drug Metoprolol, calculate the probability of the Dizziness side effect relative to other side effects (the proportion of Dizziness among all side effects reported for Metoprolol).

