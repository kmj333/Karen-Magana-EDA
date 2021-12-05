### Motivation

This dog dataset of 2938 sheltered dogs in Hungary sparked my interest, given that I enjoy providing volunteer work for dog shelters and have a dog of my own. As I delved into research about dog shelters, I decided to explore the number of dogs in this dataset that are less likely to be adopted due to old age, according to some of the ‘unadoptable’ characteristics mentioned in Animals That Are Adopted Last (https://www.thesprucepets.com/animals-adopted-last-4769768).

### Data Process

This dataset describes adoptable dogs from Hungary, which can be found on Kaggle.com (https://www.kaggle.com/jmolitoris/adoptable-dogs/version/1). Most of the dataset consists of categorical data, except for the “age” column. I focused my analysis on the ‘age’ and ‘sex'columns since there was plenty of missing data for many of the other columns along with the intention to make my investigation more concise. I began with making cleaning checks in Excel for these 2 columns, and no changes were made because my exploratory analysis didn’t require it. I utilized R Studio to apply Tukey's 5 number summary, to make a boxplot of the 'age' column separated by sex, and to create a histogram visualizing the age range of these dogs.

### Visualizations

![My first figure](https://github.com/kmj333/Karen-Magana-EDA/blob/main/dogagehistogram.png)

The visualization above represents the age range of 2938 dogs, which range from less than a year old to approximately 22 years of age. This roughly symmetrical histogram demonstrates a senior age mostly between 5 to 13 years of age with an apparent average of 9 years of age with a standard deviation of 4. Still, there appears to be a significant number of dogs for ages 5 and below. As for dogs of older age, there is more of a tail that illustrates outliers of 16 years and older, which extends to 22 years of age.

To gain a better view of the outliers, I created a boxplot of the ages separated by sex, as seen below.

![My second figure](https://github.com/kmj333/Karen-Magana-EDA/blob/main/dogageboxplot.png)

The boxplot above demonstrates that there is more old age outliers among feamle dogs than male dogs even though there is more males than females, which is interestingly acccurate in portraying how female dogs have more longevity. The male dogs' outliers do lie above 20 years of age, while the female dogs' outlier ages are roughly between 17 and 20. 

### Analysis

I utilized Tukey's 5 number summary to view a detailed summary of the ‘age’ column to gain a more specific age range of the dogs that the histogram couldn't provide. The youngest was a puppy of 0.15 years of age and the oldest was 21.92 years old. Both the min and max can be classified as outliers since the 1st and 3rd quarters were approximately at 5.8 and 11.2 years of age. The median and mean stood at almost 8.7 and 8.6 years of age. Based on this information most of the dogs are seniors, which sadly makes most of these dogs more unlikely to get adopted.
