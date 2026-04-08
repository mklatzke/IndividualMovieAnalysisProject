# Individual Movie Analysis Project - Meta Klatzke
COMP 3125 Data Science Fundamentals Final Individual Project

In addition to the group project, this repository answers the following two research questions regarding the movie dataset from Kaggle:
1. Are movies released in odd-numbered years more profitable than movies from even-numbered years?
2. How much of the total box office gross comes from opening day ticket sales?

## Dataset
The dataset used in this individual project is the same one as in the group project. It is the Movie Dataset for Analytics & Visualization by Shubham R. Pawar on Kaggle. It is a synthetic dataset containing 999,999 rows and 17 columns​.
URL: https://www.kaggle.com/datasets/mjshubham21/movie-dataset-for-analytics-and-visualization
<img width="1565" height="513" alt="Screenshot 2026-04-08 151406" src="https://github.com/user-attachments/assets/0b1047a9-4176-413f-aa8c-47e06067f224" />

## Methods
The following tools were used to complete this analysis:
- Google Colab (Python coding)
- pandas (Python library for dataframe usage)
- scipy stats (t-test)
- matplotlib.pyplot (box plot and pie chart)

## Results
1. Are movies released in odd-numbered years more profitable than movies from even-numbered years?
  This question can be answered using a two-sample t-test. The null hypothesis in a two-sample t-test is that there is no difference between the means of the groups. This test compares the mean global box offices between movies released in odd and even years. The p-value is 0.4710319611283329, so the test fails to reject the null hypothesis. There is no statistical difference between the average revenue of movies released in odd-numbered years and even-numbered years.
<img width="659" height="435" alt="data science individual1" src="https://github.com/user-attachments/assets/c3447fd7-f790-466a-a83e-7118b1af62f7" />

2. How much of the total box office gross comes from opening day ticket sales?
  Opening day ticket sales make up ~20 percent of all US first-week box office earnings. This is a significant amount of profit to make all in the first day.
<img width="501" height="411" alt="data science individual2" src="https://github.com/user-attachments/assets/ba2cff57-fd79-4d01-b8fb-5ecac417f573" />

## Discussion
The findings of this project reveal that the odd- or evenness of a movie's release year does not affect its box office profits. This makes sense because audience members do not frequently consider the year when deciding if they are available and willing to watch a movie. The analysis also finds that opening day ticket sales in the US contribute to a large amount of revenue within the first week. Although 20 percent of profit is not the majority, it is still significant because an average weekday should contribute 1/7, or about 14 percent of the weekly revenue. Making 1/5 of the week's profit in just one day shows that the opening day ticket sales have an effect on total box office earnings.

## Summary
This projects adds on two extra questions to the movie analysis group project: Are movies released in odd-numbered years more profitable than movies from even-numbered years, and how much of the total box office gross comes from opening day ticket sales? Using Google Colab and many imported Python libraries, it was concluded that release year does not affect total revenue, but opening day sales do.
