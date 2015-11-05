How Fertility rates affects the ranking of the most populated countries of the world (1960-2050)
-----------------------------------------------------------------

### Summary

This visualization is the representation of how the fertility rate affects the ranking of the countries like UK, Germany, Japan and Russia which were in Top 10 most populated countries in 1960 and the countries like Philippines, Nigeria, Ethopia and Pakistan which entered into Top 10 countries after 1960. This also gives us the picture about how some countries like UK, Germany, Russia and Japan moved down the ladder due to low fertility rates continuously for decades. Also how Philippines, Ethopia, Nigeria and Pakistan moved up the ladder due to high fertility rates continuously for decades.

By comparing the countries which moved out of the top 10 with the ones which entered into top 10, it is easier to make out how the fertility rate of the countries is impacting the ranking. There may be other factors too which might be contributing this change but fertility rate is for sure one of the most leading causes.

### Design
After getting the feedback for the last submission of Population pyramid which was as pointed out was more of exploratory. In order to make it explanatory I had to show what was causing the change in the movement of the countries up and down the ranking. I started looking for the cause which was playing very important role.  Fertility rates is one of the leading causes of the population growth of any country. So decided to show how the ranking of the countries depending on the fertility rates. 

Now I have to show the ranking and fertility rate in the same chart for each country. Initial thoughts were to have two charts. One bar chart with the ranking and other line chart for the fertility rate. But with two different charts it will be very difficult to compare how one affects the other. I needed a way to show both the charts in the one single chart. 

1) Decided to create on chart with two y axis 
2) One y axis for the fertility rate and other one for ranking.
3) Bars were selected for ranking as it is more of a categorical value
4) Line chart selected for fertility rates as wanted to show the trend.
5) Different colors were selected for each as should differentiate from each other. Each represent different parameter.

Made some changes after the initial feedback from friends:

1) Added a legend for the country attribute to highlight which country is being shown.
2) Allowed Users to stop and start the animation. This should help the users to view the visualization for each country in more detail.
3) Added another legend which shows what represents ranking and what represents fertility rates.

Made changes after the feedback from the review comments from the Udacity Reviewer:

1) Added an option to view all the countries in one single page/view.
2) Added an button to play all one by one.
3) Fixed the axis for fertility rate.

Made Changes after the third feedback from Udacity Reviewer:

1) Filter and removed few countries from the dataset 
2) Considered only those countries which were in Top 10 in 1960 and moved out during later decades. 
3) Also considered the countries which were not in Top 10 in 1960 and moved into Top 10 during later decades.
4) As suggested by the Udacity review used the below encodings
   a) Year on the x-axis
   b) Color for country
   c) Ranking on the y-axis 
   d) Fertility rate as bubble size. 
5) Added a legend which will allow users to hide or select the countries.

### Feedback

####Below are the feedback from friends for the previous submission:

Feedback for index1.html:
1) Too many graphs in one view
2) Too small to follow
3) Even though it conveys the information about each country's rank and fertility rate it looks too clumsy

Improvements made based on the feedback:
1) Removed all charts in one view and added only one chart for one country at a time
2) Added animation to display one chart at a time.

Feedback for index2.html:
1) It is difficult to follow which country visualization is being displayed
2) Color of the bar is too light and difficult to follow the change
3) There is a relationship between fertility rates and ranking.
4) There should be a way to stop the animation and view the visualization for each country.

Improvements made based on the feedback:
1) Changed the color of the bars to blue.
2) Changed the color of the line to kind of maroon.
3) Added a legend for the country attribute to highlight which country is being shown.
4) Allowed Users to stop and start the animation. This should help the users to view the visualization for each country.

Feedback for index_final.html:
1) Layout of the chart with the details of which country chart is being displayed is very nice.
2) Having option to stop and start the animation is very good way of allowing to view the chart for each country in more detail.
3) The details displayed when hovering over the bars and line gives more information of the actual data values.
4) With bars and lines chart displayed together, it is very easy to understand how the fertility rates impacts the ranking of the country.

#### Second Feedback from the Project reviewer

Feedback:
1) There is no way to compare countries to each other
2) Ranges of the y-axis change for each charts
3) Ranking has decimal values

Improvements based on the feedback:
1) Added an option to view all the countries in one single page/view.
2) Added an button to play all one by one.
3) Fixed the y axis for fertility rate. 
4) y-axis for ranking was not fixed. Fixing it was not making any good for the visualization. 
5) There are only two countries India and China for which the ranking axis goes into decimal. Could not avoid it.
  
#### Third Feedback from the Project Reviewer

1) Comparing the countries is not possible.
2) Ranking representation is confusing.
3) Neutral countries

Improvements made based on the feedback:
1) Filter and removed few countries from the dataset 
2) Considered only those countries which were in Top 10 in 1960 and moved out during later decades. 
3) Also considered the countries which were not in Top 10 in 1960 and moved into Top 10 during later decades.
4) As suggested by the Udacity review used the below encodings
   a) Year on the x-axis
   b) Color for country
   c) Ranking on the y-axis 
   d) Fertility rate as bubble size. 
5) Added a legend which will allow users to hide or select the countries. This should make comparing between the countries easier.

### Resources
* http://www.worldometers.info/world-population/ - Data Source
* http://d3js.org/
* http://dimplejs.org/
* http://dashingd3js.com/
* http://alignedleft.com/
* http://animateddata.co.uk/articles/
* http://www.censusindia.gov.in/
* http://code.tutsplus.com/
* http://adilmoujahid.com/
* http://www.visualisingdata.com
