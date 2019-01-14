# Udacity-project---Blog
Udacity project - Blog: Explaning variation in prices on AirBnB


# Which variables determine prices for overnight stays on the platform AirBnb?


AirBnb is an important platform for privately renting out apartments and single rooms: Prices for apartments, however, vary, even within one city. In this blog post, I ask which variables determine the price for overnight stays on the platform AirBnb and try to develop a simple tool that can effectively predict prices. To do so, I use Seattle AirBNB Data which includes information on prices, but many other variables that potentially affect the price a host may charge such as the characteristics of the apartment, information on the host or review rating scores.

First, I take a closer look at the distribution of prices with the Seattle AirBNB Data to identify the existing variation. Then, I study the relation between prices, characteristics of the apartment, review rating scores and information on the host in three separate analysis. Finally, I build a prediction model that effectively predicts the price a new host may charge for an overnight stay. I hope that this tool will be helpful for anyone who is thinking about renting out his or her apartment/room. 

# What variation in prices exists?
The average price for a overstay night at AirBnB in the Seatle Data is $127.98; while the minimum price is $20 and the maxium price $1.000. This shows the high variablity in prices in this dataset and also the value of developing a tool that can help new hosts to set an appropriate price. The full distribution of prices is shown in the following figure:


# How does the price of an apartment depend on the characteristics of the apartment?
In the next step, I relate prices to the characteristics of the apartments such as size in square feet, number of bedrooms and bathrooms, and the type of apartment (private room vs. whole apartment). From this analysis, we learn that -- as expected -- larger apartments with more beds and bathrooms are typically more expense. Furthermore, an entire apartment is more expense to rent than a single or shared room.

# How do past reviews affect current prices?
Next, we relate prices to past reviews. Intuitively, offers with better reviews should attract more potential customers and hence should achieve higher prices. Generally, this intuition is confirmed by the analysis as both review scores and the number of reviews are positively correlated with prices. Checking and communication with the host, by contrast, appear less important for costumers as their scoring is not significantly related to prices. 

# Can we build a simple prediction model that can accurately predict prices on AirBnb?
My final goal is to provide you with a simple tool that can effectively predict prices on AirBnB. This tool should be helpful for anyone who is thinking about renting out his or her apartment as it allows an immediate comparison to one’s competition. This model takes into account the characteristics of the overnight apartment such as size or number of bedrooms and bathrooms, information on the host as well as past reviews. My analysis reveals that a simple linear model including the aforementioned variables can accurately predict 74% of the price. This should give new host a good idea about the potential price range of their overnight option.

