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
