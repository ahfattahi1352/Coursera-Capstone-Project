# Data Science Capstone Project:    The Best Neighborhood in 
# Montreal for Opening a new Café/ Coffee Shop

## 1. Introduction
### *1.1. Business Problem*

In a metropolitan-multicultural city like Montreal, there are a number of places full of students and businesses which are suitable to open a new Coffee Shop close there. This study is going to help people planning to open a new Coffee Shop in Montreal. This idea have a heated debate over the optimal neighborhood for setting up shop, but the people would like to be located in an appropriate location of the city and in a spot where people already tend to drink Coffee. Assuming, demography of population and income are not an issue of each neighborhood in accordance with competitors already exist on the same regions. 

### *1.2. Target Audience*
The target audience of this report would be anyone who wants to buy or establish a Coffee Shop in Montreal, or anyone in Montreal just looking for a nice area to drink a coffee.

## 2. Data
In order to provide the stakeholders the necessary information to best make this decision, some data would be needed. For the city of Montreal has some public datasets that describe various aspects of the city, and Foursquare API allows access to collect competitors data on the same neighborhoods:

Altogether, there are three sets of data for our analysis:

**Administrative boundary of the Montréal agglomeration (Boroughs and related cities) Data**
- This is going to help us by providing Polygons delimiting the boroughs of the City of Montreal, boroughs and related cities constituting the agglomeration of Montreal and allowing us to select one of the suitable areas for new Coffee Shop

  http://donnees.ville.montreal.qc.ca/dataset/polygones-arrondissements


**Montreal's Census Profile** 
- This is going to provide data contains Montreal's 2016 census Aboriginal peoples; Education; Ethnic origin; Families, households and marital status; Housing; Immigration and citizenship; Income; Journey to work; Labour; Language; Language of work; Mobility; Population; Visible minority

https://www12.statcan.gc.ca/census-recensement/2016/dp-pd/prof/details/page_Download-Telecharger.cfm?Lang=E&Tab=1&Geo1=POPC&Code1=0547&Geo2=PR&Code2=24&SearchText=Montreal&SearchType=Begins&SearchPR=01&B1=All&TABID=1&type=0

Montreal income census 2016 per borough can be downloaded as excell in the following url: 'http://ville.montreal.qc.ca/pls/portal/url/ITEM/55637C4923B8B03EE0530A930132B03E'




**Foursquare API**
- Foursquare data is robust and provides location data allows you to retrieve information about the most popular spots in each neighborhood in Montreal. 

 ## 4. Results and Discussion¶

We have pulled data on census individual average income for each boroughs in Montreal and used this information to narrow down boroughs options from 33 boroughs to 11 boroughs with 61 neighborhoods. Our analysis has informed us that:

Café & Coffee Shop, Restaurant, Pharmacy, Park, Bakery, Pizza Place, French Restaurant, Grocery Store, Sandwich Place are the most common venues in our 11 preferred boroughs. 

Clustering neighborhoods based on their most popular venues grouped all 11 preferred boroughs with majority of their neighborhoods categorized into cluster 2.  There are eleven neighborhoods in boroughs such Rivière-des-Prairies–Pointe-aux-Trembles, Mercier–Hochelaga-Maisonneuve, Rosemont–La Petite-Patrie, Ahuntsic-Cartierville, Le Sud-Ouest, Saint-Laurent, and verdun are categorized into Cluster 1 and 3 that Café & Coffee Shop is not popular venue in these neighborhoods.Places such in Mercier–Hochelaga-Maisonneuve, Villeray–Saint-Michel–Parc-Extension, Saint-Laurent, Le Plateau-Mont-Royal, Ville-Marie have majority Café & Coffee shops as popular venues, whereas most of the popular vanues in cluster 1 such as Dutrisac/Saint-Laurent, Louis-Riel/Mercier–Hochelaga-Maisonneuve,Saint-Sulpice/Ahuntsic-Cartierville, Côte-Saint-Paul/Le Sud-Ouest, Café & Coffee shop is not popular venue, but locations like Park, Gym, and restaurant are more popular.  	

Based on this analysis, Longue-Pointe/Mercier–Hochelaga-Maisonneuve, Parc-Jarry and Crémazie/ Villeray–Saint-Michel–Parc-Extension, Bois-Francs/Saint-Laurent, and Mile End / Le Plateau-Mont-Royal	are hot places for Café & Coffee Shops and may not suitable to open a new one. Saint-Laurent, Rosemont–La Petite-Patrie seems to offer a good balance between foot traffic, popularity for Café & Coffee Shop, and might be rent prices. Le Plateau-Mont-Royal and Ville-Marie seems to be a hot spot for Café & Coffee Shop, but also comes with the high cost of rent. 

Loyola / Côte-des-Neiges–Notre-Dame-de-Grâce, René-Lévesque/Ville-Marie, Parc-Extension/Villeray–Saint-Michel–Parc-Extension, Saint-Louis/ Le Plateau-Mont-Royal seem to have similar feel on same clustering but is not hotspot and there are the medium busy neighborhood. Places Rosemont–La Petite-Patrie including four neighborhoods Marie-Victorin, Petite-Côte, Vieux-Rosemont, Louis-Hébert, and Père-Marquette have the most population of average individual income might be better place to open a new Café & Coffee Shop which is popular venue but not much in contrast with other places and has more potential customers too.

Ultimately, the optimal Café & Coffee shop spot depends on what type of Coffee Shop you would like to open. An upscale and trendy Coffee Shop might fare better against competition in an expensive and bustling area like Loyola/Côte-des-Neiges–Notre-Dame-de-Grâce, whereas a university may be the spot in an area, which likely receives most of its foot traffic exclusively from its residents.

A major drawback of this analysis is that the clustering was completely based on Foursquare’ s data for popular venues. There are other ways to assess popularity of neighborhoods and the spots inside them, venue popularity is just one of them. It may also be helpful to look exclusively at Café & Coffee in an area, how many there are, and how popular they are on weekdays and weekends.

## 5. Conclusion


We have executed a project using common python libraries to manipulate data sets, Foursquare API, Montreal Open Data portal, StatCan portal to explore the Montreal Agglomeration, census income data and find popular venues of Montreal, and Folium leaflet map to cluster and segment neighborhoods. This project could be further developed with more census data such as rent price, traffic information, and crime data for each boroughs for more accurate investigation and have better decision.

This was just one use-case. These analytical tools open a world of possibilities for strategic decision making across the various realms of business. 
