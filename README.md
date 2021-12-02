#Motivation

I enjoy visiting and providing volunteer work for dogs, and have a dog of my own. As I delved into research about dog shelters, I decided to explore what  dogs are less likely to be adopted in a shelter located in Zurich according to some of the characteristics mentioned in Animals That Are Adopted Last (thesprucepets.com). I was also curious as to how accurately my analysis would reinforce how 20% of dogs (Animals That Are Adopted Last (thesprucepets.com) who enter shelters in America are euthanized. 


Data Process

Though this dataset of adoptable dogs from Zurich from Kaggle.com provided enough information to answer my initial research question, there was a lot of missing information for columns that described the friendliness with people of different ages and dogs and compatibility with cats. I decided to exempt the use of such columns along with other columns that were not related to the physical traits of the dogs, and ultimately focused on the ‘color’, ‘size’, and ‘age’ columns. I began with a brief cleaning check in Excel to make sure there weren’t negative values, and found that the available data was accurate. I utilized R Studio to process the categorical columns of data to create a boxplot summary and create plots to summarize dog characteristics


Visualizations

![My first figure](https://raw.githubusercontent.com/kmj333/Karen-Magana-EDA/main/vis.png)
![My second figure](https://raw.githubusercontent.com/kmj333/Karen-Magana-EDA/main/vis2.png)

The first demonstrates the genders of the dogs and the second demonstrates the sizes of the adoptable dogs, which either were small, medium, or large. By this visualization I was able to see that about 2000 medium dogs composed the majority size of dogs in these shelters. For large dogs, there was a slightly bigger amount than small dogs, but each consisted of approximately 500 count.


Analysis

I utilized Tukey's 5 number summary to view a detailed summary of the ages for the only continuous column of the data to gain a better perspective of the age range of the dogs.The youngest was a puppy of .15 years of age and the oldest was 21.92 years old. Both the min and max I think could be classified as outliers since the 1st and 3rd quarter were approximately at 5.8 and 11.2 years of age. The median and mean stood at almost 8.7 and 8.6 years of age. By creating box plot of the summary of age information I was able to make a conclusion.

