### Motivation

This dog dataset of sheltered dogs in Hungary sparked my interest, given that I enjoy providing volunteer work for dog shelters and have a dog of my own. As I delved into research about dog shelters, I decided to explore the number of dogs in this dataset that are less likely to be adopted due to old age, according to some of the ‘unadoptable’ characteristics mentioned in Animals That Are Adopted Last (thesprucepets.com).

### Data Process

This dataset describes adoptable dogs from Hungary, which can be found on Kaggle.com. Most of the dataset consists of categorical values, except for the “age” column. I focused my analysis on the ‘age’ and ‘sex'columns since there was plenty of missing data for many of the other columns along with the intention to make my investigation more concise. I began with making cleaning checks in Excel for these 2 columns, and no changes were made because my exploratory analysis didn’t require it. I utilized R Studio to apply Tukey's 5 number summary, to make a boxplot of the 'age' column separated by sex, and to create a histogram visualizing the age range of these dogs.

### Visualizations

![My first figure](https://github.com/kmj333/Karen-Magana-EDA/blob/main/dogagehistogram.png)

The visualization above represents the age range of dogs, which range from less than a year old to approximately 22 years of age. This histogram demonstrates that most of the dogs are of senior age between 5 to 13 years of age, but still, there appears to be a significant amount of dogs for ages 5 and below. As for dogs of older age, there is more of a tail that illustrates less than 50 dogs for ages 15 years and older (a good sign!) and also seems to be a significant outlier of about 22 years of age.

To gain a better viwe of the outliers, I created a boxplot of the ages, separated by sex as seen below.

![My second figure](https://github.com/kmj333/Karen-Magana-EDA/blob/main/dogageboxplot.png)

The boxplot above demonstrates that there is more outliers in older age among feamle dogs than male dogs, which is interestingly acccurate in portraying how female dogs have more longevity.

### Analysis

I utilized Tukey's 5 number summary to view a detailed summary of the ‘age’ column to gain a more specific age range of the dogs that the histogram couldn't provide. The youngest was a puppy of 0.15 years of age and the oldest was 21.92 years old. Both the min and max can be classified as outliers since the 1st and 3rd quarters were approximately at 5.8 and 11.2 years of age. The median and mean stood at almost 8.7 and 8.6 years of age. Based on this information most of the dogs are seniors, which sadly makes most of these dogs more unlikely to get adopted.
