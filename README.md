# Applied Data Science Capstone
## A description of the problem and a discussion of the background.

The problem that I would choose to solve is the location in which I would advice one to open up a retail store at.

From a business class that I took in the past, the most important factor of succeeding in the retail industry is it's location. Where ever there is a good traffic of people, the sales is expected be larger due to the people entering the store. 

In reality, it is difficult to obtain the data of sales and store locations to test the corelation between the location and the sales, so I would need to twist around the research question.

The data that I have from the past assignment is the Postalcode that are used in Toronto and their geographical location in logitude and latitude.

In order to apporximate the traffic, I searched and found the traffic of Subway as "Business Day Platform Usage" data.

Together with that, I also discovered the geographical location of each of the station in the form of longitude and the latitude. 

From these informations, I can test if there is any correlation between the subway usage and the number of retail stores on these geographical locations.

Suppose that there is a correlation between the retail stores and the geographical locations, then I can advice on where to open the retail store based on the information that I gathered.

## A description of the data and how it will be used to solve the problem.

he data that I have from the past assignment is the Postalcode that are used in Toronto and their geographical location in logitude and latitude.

In order to apporximate the traffic, I searched and found the traffic of Subway as "Business Day Platform Usage" data.
https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#75d6b4a2-7f29-b0df-f1eb-cc5bc7f53b68

Together with that, I also discovered the geographical location of each of the station in the form of longitude and the latitude. 
http://scruss.com/blog/2005/12/14/toronto-subway-station-gps-locations/

From these informations, I can test if there is any correlation between the subway usage and the number of retail stores on these geographical locations.

I would plot the Subway usage against the number of retail stores to find their correlation. The number of the data point would equal the number of postalcode in Toronto. The x-axis would be the subway usage (total of To Trains and From Trains), and then the y-axis would be the number of retail stores that were returned on the search result.

I would present the data in two ways.

The first graph is simple plot graph that shows the correlation between the two data.

The second graph is the heatmap overlay on the map produced from Folium.

Those should provide the visual representation of the validity of my hypothesis.

Finally, I would provide with the advice on which specific postalcode to open the store at.
