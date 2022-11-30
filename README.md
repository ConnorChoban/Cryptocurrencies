# Cryptocurrencies

The purpose of this analysis is to create a preliminary analysis for clients who are interested in investing in the Cryptocurrency market. We used our skills to parse data on a wide variety of cryptocurrencies, pass the data through Principal Component Analysis (PCA), generate clusters through the KMeans algorithm to generate predictions, and then finally, we created several visualizations in hvplot using the scaled data to support our analysis. 

## Results

By analyzing our visualizations below we can come to a few conclusions. By looking at the elbow curve chart, we see that at around 4 or 5 clusters there is a significant shift in inertia, which would indicate that either number of clusters would be ideal for our analysis. 

<img width="720" alt="Screen Shot 2022-06-24 at 2 15 10 AM" src="https://user-images.githubusercontent.com/99847786/175476140-fb7aac8b-f785-4820-983e-e45253ac03f4.png">

In this visualization, we see which data belongs to which cluster. We can see that three of the four clusters aggregate by components 1 and 2, with BitTorrent being a noticeable outlier. Depending on our needs for this analysis in the future, we can either choose to investigate this outlier or decide to eliminate it completely. 

<img width="818" alt="Screen Shot 2022-06-24 at 2 14 53 AM" src="https://user-images.githubusercontent.com/99847786/175474319-9e091413-5f39-4567-a6d6-b933af228e66.png">

Finally, in the last chart, we placed all of our currencies in a scatterplot and arranged by the total amount of coins mined, and the total supply. Most currencies clustered in the lower left corner, with two noticeable outliers towards the top, one with a lower value in relation to the total amount of coins mined, wheras the other is the opposite, with a higher value in relation to the total amount of coins mined with both having a high supply. As such, it may be worth it to investigate these outliers further to try to determine why the supply is so much higher than the other values. These currencies could either be worthless, or on the other hand, could be currencies overlooked by investors and may be significantly undervalued. 

<img width="742" alt="Screen Shot 2022-06-24 at 2 14 22 AM" src="https://user-images.githubusercontent.com/99847786/175474328-a047a914-f6d7-42ca-b692-6eae19119ade.png">
