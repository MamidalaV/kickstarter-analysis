# Kickstarting with Excel

## This project is to analyze Kickstarter data on various fundraising campaigns across the world. Here, a data set of 4114 fundraisers has been considered between the years 2009 and 2017.

### The purpose of this project is to provide insights to our client on how other fundraisers have faired in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
	- A total of 1369 campaigns have been lauched in the "Theatre" category. 
	- Of these, 839 have been successful, 493 have failed and 37 were cancelled.
	- Highest number of fundraisers were launched in the month of May, followed by June.
	- Most successful campaigns were launched in May with 66.9% followed by 65.3% in June.

[Graph for Theater Outcomes vs Launch](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
	- From the master dataset, 1047 fundrasiers have been analyzed that fall under the subcategory "Plays".
	- Highest number of fundrasiers had the goals between $1,000 and $4,999.
	- The fundraisers with goals less than $1,000 have been most successful at 75.8%.
	- The next successful goal range is between $1,000 and $4,999 with 72.7%.

[Graph for Outcomes vs Goals](Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
	- The date format of the campaigns launch date and the deadlines are in unix format. If unknown, the dataset would not be useful.
	- When applying formulas to analyze the data, if one single condition is omitted, the the result would be incorrect and so will be the conclusion.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1. 61.3% of the campaigns run in the 'Theatre" category have been successful. Implies, this could be the success rate of any fundraiser in this category.
	2. The campaigns launched in the month of May are most successful than the others, with a 66.9% success rate.

- What can you conclude about the Outcomes based on Goals?
	- The goal of the intended funraiser is $10,000. Based on the data, chances of campaigns with this goal to be successful is 59.2%.

- What are some limitations of this dataset?
	- The goal amount is in 'dollars' and it is assumed that this has already been converted for the fundraisers from other countries.
	- There are no reasons provided for failed/cancelled campaigns to slice the data further.
	- The date range considered for this analysis is between years 2009 and 2017. Since there are datapoints that are a decade old, this may not be the true depiction of the "current trend".

- What are some other possible tables and/or graphs that we could create?
	- This data can be used to create a graph
		- With the number of successful campaigns across various categories and/or subcategories that will help in deciding upcoming scripts.
		- To show the number of backers year over year. Which will help in assessing the trend of whether more or less people participating in crowdfunding. 
		- We can further drill this data to assess the average pledge amount for a certain type of category/subcategory. This will help is assessing if more/lesser backers are supporting a certain catergory.

## Final Recommendations:
	- Option 1: After analyzing the data based on Launch date and goal, running a fundraiser in the Month of May for $10,000 would have higher success rate.
	- Option 2: Considering the data based on Launch date, goals, Plays within theatre category and the most recent data (between 2015 and 2017), my recommendation would be to run 2 fundraisers for $5,000 each in the Month of July and Nov. With this, the chances of getting funded in full would be around 80%. This is if the timing is not a constraint. 

[Supporting Data here](For_Final_Recommendation.xlsx)
