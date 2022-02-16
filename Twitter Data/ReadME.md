This repository contains most of the code that I used when collecting tweets. Per the data use agreement that I signed, I am unable to share or upload most of the Twitter data that I collected from the Center of an Informed Public (CIP), which is where I ended up collecting all my twitter data. However, before I gained access to the CIP database, I collected around 500,000 coronavirus tweets that had already been classified by researchers on GitHub as true or false. So, I have shared the code that I used to connect to the twitter API to rehydrate the tweet IDs along with the links to the GitHub databases with the tweet IDs. Please note you will need to change the file pathway to load the csv files into R and you will need to use your own Twitter API. I cannot publish the rehydrated tweets due to Twitters' terms of service policy. I have recently completed my user exposure/engagement index (UEI) using COVID-19 tweets and data on influencers in the US that are on the right and left from the CIP. I created this index by adding up the number of followers, retweets, likes, and comments for each tweet. To get the aggregate UEI for tweets on the left and right at 36 different time intervals, I added up all the UEI scores for the right and then divided this number by the total number of tweets on the right and left for the given interval. I then did this again except I summed up the UEI scores for the left. Since my UEI index is based on aggregated information I have added my user engagement csv file "UEI.csv '' and the code that I used to create my index and wrangle the 300 GB of twitter data. 

 

# Sources 

Cui, L., & Lee, D. (2020). Coaid: Covid-19 healthcare misinformation dataset. arXiv preprint arXiv:2006.00885. 

Hayawi, K., Shahriar, S., Serhani, M., Taleb, I., & Mathew, S. (2022). ANTi-vax: A novel twitter dataset for COVID-19 vaccine misinformation detection. Public Health, 203, 23-30. doi:10.1016/j.puhe.2021.11.022 

Shahi, G. K., Dirkson, A., & Majchrzak, T. A. (2021). An exploratory study of covid-19 misinformation on Twitter. Online Social Networks and Media, 22, 100104. doi:10.1016/j.osnem.2020.100104 
 
 Starbird, K., Spiro, E.S., Lockaby, P., Robinson, J. West, J.D. (2022). Coronavirus Pandemic Twitter Dataset. Center for an Informed Public, University of Washington.
