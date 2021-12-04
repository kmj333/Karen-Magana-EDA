### Motivation

This dog dataset of sheltered dogs in Hungary sparked my interest, given that I enjoy providing volunteer work for dog shelters and have a dog of my own. As I delved into research about dog shelters, I decided to explore the amount of dogs in this dataset that are less likely to be adopted due to old age, according to some of the ‘unadoptable’ characteristics mentioned in Animals That Are Adopted Last (thesprucepets.com).

### Data Process

This dataset describes adoptable dogs from Hungary, which can be found in Kaggle.com. Most of the dataset consists of categorical values, except for the “age” column. I focused my analysis on the ‘age’ and ‘sex columns, since there was plenty of missing data for many of the other columns along with the intention to make my investigation more concise. I began with making cleaning checks in Excel for these 2 columns, and no changes were made because my exploratory analysis didn’t require it. I utilized R Studio to create a boxplot of the age of dogs separated by sex, and to create a histogram visualzing the age range.


### Visualizations

![My first figure](https://github.com/kmj333/Karen-Magana-EDA/blob/main/dogagehistogram.png)

My visualization above represents the age range of dogs, which range from less than a year, to up to 24 years of age. 

### Analysis

I utilized Tukey's 5 number summary to view a detailed summary of the ages for the only continuous column of the data to gain a better perspective of the age range of the dogs.The youngest was a puppy of .15 years of age and the oldest was 21.92 years old. Both the min and max I think could be classified as outliers since the 1st and 3rd quarter were approximately at 5.8 and 11.2 years of age. The median and mean stood at almost 8.7 and 8.6 years of age. By creating box plot of the summary of age information I was able to make a conclusion.

