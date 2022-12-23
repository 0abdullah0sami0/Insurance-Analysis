# Citation
> abdullah shalaan. (2022, December 20). Insurance Data analysis. Rpubs. https://rpubs.com/AbdullahS/insurance

# Project title
> Insurance data analysis

# Content
<p>
  <a href="#project-description">Project Description</a>
  
  <a href="#data-analysis-insights">Data analysis insights</a>
</p>


## Project Description
In this project, we conduct an exploratory data analysis (EDA) on an insurance charges dataset to discover and understand the relationship between insurance charges and different health and demographic factors (age, sex, region, BMI, smoker, number of children). The data set is from the [GitHub repository of Machine Learning with R datasets](https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv).

## Data analysis insights

### Univariate analysis
In this section, we used tables and interactive (ggplotly) charts to explore the distribution of each features from the data set in order to understand the data sample we are working with.

We derived the following insights from this sections:
* The percentage of females in the data is 49% and the percentage of males is 51%, which indicates that the data is balanced in terms of sex.
* The majority of individuals in the dataset have less than 2 children (85.05%). Also, 42.9% of individuals don’t have any children while only 3.21% have more than 3 children.
* The majority of individuals in the data are non smokers (79.52%).
* Individuals in the data sample are distributed almost evenly among the four regions, with southeast being the most common region in the data (27.2%).
* Individuals aged less than 20 years old make only 10.24% of the data, as the majority is aged over 40 years old (47.61%).
* We find that 31.39% of individuals in the data have charges over the average, which means that these individuals have some extreme charges values that pulled the average.
* The distribution of BMI looks symmetrical and centered around 30.

### Bivariate analysis: relationship between charges and other factors
In this section, we analyze the relationship between insurance charges and each one of the factors from the data using tables and visualizations.

We derived the following insights from the bivariate analysis section:
* There is a moderate linear relationship between insurance charges and age. the relationship is positive, which means that the higher the age the higher the charges.
* Insurance charges are lower on average for individuals with 5 children compared to the other groups, and higher for individuals with 2 to 3 children.
* There is a moderate positive linear relationship between insurance charges and BMI, indicating that the higher the BMI value the higher are the charges.
* The distribution of insurance charges for female is less variant than the distribution of charges for male. The average (median) insurance charges is similar for female and male individuals.
* Insurance charges are meaningfully higher on average for smokers compared to non-smokers.

### Bivariate analysis on filtered data
In this section, we analyze the relationship between insurance charges and each one of the factors on filtered samples of the data.

We derived the following insights from the bivariate analysis section:
* We notice that also for the group of individuals with BMI between 30 and 40, insurance charges are meaningfully higher on average for smokers compared to non-smokers.
* For only female individuals, insurance charges are noticeably higher on average for smokers compared to non-smokers.
* The proportion of non-smokers with charges below the average is 68.54% of the entire data which is meaningfully higher compared to the proportion of smokers (0.07%), which indicates that insurance charges are mostly higher than average for smokers.
* For non-smokers with less than 2 children, we notice that female have higher insurance charges on average compared to male individuals.
* For individuals from southwest with BMI larger than 35, we notice that male have higher insurance charges on average compared to female individuals.

### Multivariate analysis
In this section, we aim to understand the relationship between insurance charges and multiple factors from the data on filtered and unfiltered samples of the data, using tables and visualizations.

We derived the following insights from the bivariate analysis section:
* On average, insurance charges are similar for non-smoker males and females, and for smoker males and females.
* On average, insurance charges are similar among smokers regardless of their sex and region, and similar among non-smokers regardless of their sex and region.
* the majority of individuals with more than 2 children and charges over the average are smoker males (39.44%) followed by non-smoker females (25.35%) and the minority is non-smoker males (14.08%)
* The majority of smokers with charges over the average are males from southeast (20.15%), followed by males from northeast and southwest (13.55% each), and the minority are females from southwest (7.69%)
* The boxplots above illustrate the distribution of charges for individuals with BMI between 35 and 45 by sex and region. We notice that the medians of insurance charges for females and males are very close in each region. The boxes sizes of females and males are different within each region which indicates that the variation of charges is different between them. We also observe that there are some outlier values in the data, like in the group of females from southeast and males from northeast.


