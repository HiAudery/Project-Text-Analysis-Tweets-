The objective of this project is to perform word frequency analysis.   And the results of Term frequency method and TF-IDF shows different insights. 

Data is based on Twitter data of Elon Musk from 2010-2022. For analysis consider the years `2017-2021` (last 5 complete years). Each year has thousands of tweets. Assume each year to be a document (all the tweets in one year will be considered as a document)      

## Insights of Musk's tweets from the text analysis:  
1. from 2017, he likes saying "gt", which is the concept of the GT car emerged from Europe in the mid-1900s, with the goal of being both a high-performance automobile and a long-distance driver. So GT — meaning grand tourer or gran tourer — makes sense. Some hallmarks of GT models include a near-seamless merging of luxury and performance and a 2+2 design. Which makes sense that he also likes cars since he mentions tesla often in our previous analysis.
2. in 2018, he is researching "flamethrower" which is a jet of fire(SpaceX).  
3. in 2019, he likes to say "amp", "tesla" and "starship"(SpaceX).  
4. in 2020, "covid", "high", and "self" becomes popular in his tweets.  
5. in 2021, he likes talking about "ai"!  
6. also, he is so rigorous because he likes to speak with numbers so much during five years! Since we did not process numbers, the results makes some sense!  

- Overall, outputs of TF-IDF let us have a deeper insight of Musk's social media texts compared to TF!

- Note: We tried to process more and more text things in "tweet" within these few days, however, due to limited time and energy, there may still exist something more interesting that should be considered, for example, emojis! We realized how amazing people build NLP and ChatGPT!

- The analysis steps can be summarized here: 
1. Compute the term frequencies for each year. They should be normalized (scale of [0, 1]). Exclude stopwords.    
2. Show the top 10 words (for each year) by highest value of word frequency.    
3. Plot a histogram of word frequencies for each year     
4. Demonstrate Zipf’s law by plotting log-log plots of word frequencies v. rank for each year 5. Use TF-IDF to calculate and show the 5 most “important” words for each        

https://www.kaggle.com/datasets/ayhmrba/elon-musk-tweets-2010-2021?resource=download&select=2017.csv    
