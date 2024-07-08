# What is the Global Reach of K-Dramas?
## Lede Project 1

This is my submission for the Lede Program's first project - to create a shot data journalism piece with a topic of choice using the data analysis, coding, and visualization tools we've learned so far. 

My topic of choice was K-dramas - more specifically, their popularity around the world. I was interested in seeing if I could pinpoint which part of the world was watching the most K-dramas, and which K-dramas they were watching. I took data from the [Netflix official website](https://www.netflix.com/tudum/top10/) through which they provide a downloadable CSV of ranking data, and scraped my own data from [MyDramaList.com](MyDramaList.com). 

I used pandas to find the rows within the Netflix data which had show titles that matched the K-drama titles from the MyDramaList website. I extracted those rows and made a dataframe, on which I used pandas to sort by country (which I later turned into a DataWrapper map) and by show. 

The data shows that the countries in Southeast Asia are the biggest consumers of K-drama, followed by South Asian countries, then closely followed by the Middle East, Central America, and several South American countries like Peru and Bolivia. It also shows that the K-dramas that are trending in recent years on Netflix are the dark, grittier dramas as opposed to the bright, cheesy romances that one might be accustomed to associating K-dramas with. 
 
