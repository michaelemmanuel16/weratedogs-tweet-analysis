
This analysis was based on tweets containing images of dogs. The original data was gathered from various sources and included a wide range of information, 
such as the tweet's text, timestamp, source, expanded URLs, and various dog-related attributes such as breed and stage.

The extraction and cleaning of data was the first step in the data wrangling process. This entailed eliminating any duplicate or irrelevant observations 
and dealing with any missing values. Some tweets, for example, did not include information about the dog's breed or stage, so these fields were left blank. In addition, some rows in had the wrong datatypes and had to be fixed for easy analysis when it was needed.
Following data cleaning, the next step was to add new columns and perform feature engineering. I added a new column called dog stage which is the result of melting the stages from being columns, so I had to drop them when the new column was created.

After that, I did some exploratory data analysis (EDA) to learn more about the data and find any patterns or trends that could help with the analysis. By creating a bar chart of dog breeds, for instance, we can determine which breeds are most popular among Twitter users. A scatter plot of the retweet count and the favorite count was used to comprehend the connection between these two parameters. Lastly, a bar chart of the most popular dog names was created to better comprehend the most frequently used dog names in tweets.

Final steps in the data wrangling process were feature engineering, creating new columns, and cleaning and wrangling the data. The analysis revealed the distribution of dog breeds, the relationship between retweet count and favorite count and the most popular dog names. Even though this is only a starting point and additional insights may be discovered through additional analysis, these insights provide a solid foundation for comprehending the data and how it relates to the question at hand.
