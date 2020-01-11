# Heroes of Pymoli

## Background
Congratulations! After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

Your final report should include each of the following:

### Player Count

* Total Number of Players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

As final considerations:

* You must use the Pandas Library and the Jupyter Notebook.
* You must submit a link to your Jupyter Notebook with the viewable Data Frames.
* You must include a written description of three observable trends based on the data.

-----
## Trends Based on Data
1. The majority of players are male, at 84.03%. Females players make up 14.06%. The remaining minority are non-binary or non-disclosed at 1.91%. Of those players, the age demographics shows that majority of players are in the age range of 20-24 years olds, at about 44.79%.
2. In addition to being the most popular age range of players, 20-24 year olds as a whole spend the most money on Heroes of Pymoli, spending $1,114.06 as listed in the Total Purchase Value and an average purchase of $4.32 per person. However, the demographic group that has the highest Average Purchase Total is the 35-39 year olds with an average purchase of $4.76 per person. Their Total Purchase Value is $147.67.
3. The Total Purchase Count is 780, but the total player count is 576, which means that there is about 204 repeat purchases from at least one same player for Heroes of Pymoli. For these purchases, the most profitable item, Nirvana is not the most popular item tying for second with Fiery Glass Crusader and Extraction, Quickblade Of Trembling Hands at 9 Purchase Counts. The most popular item is Oathbreaker, Last Hope of the Breaking Storm at 12 Purchase Counts and a Total Purchase Value of $50.76
