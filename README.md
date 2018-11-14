#Precinct Consolidation Map
##Overview
This project was looking at which precincts have been closed betwee 2012 to 2016.

##Links
Live link: https://www.ajc.com/news/state--regional-govt--politics/voting-precincts-closed-across-georgia-since-election-oversight-lifted/bBkHxptlim0Gp9pKu7dfrN/

##File Structure
This map was initially created by the plugin QGis2Web
###CSS
Edit the qgis2web.css file to edit the css
###Data
Each year's shapefile is in this folder as well as the GA county geojson.
###JS
These are files that QQis2Web attached with the project. Do not edit. 
###Legend
Legend directory - exported from QGIS. I am not using these.

##Data
For 2012 - 2016, we were able to get the changes in precincts from shapefiles from the <a href="http://www.legis.ga.gov/Joint/reapportionment/en-US/default.aspx">Georgia Reapportionment Office</a>. The data for 2018 was not available yet, so instead, I went through the <a href="http://sos.ga.gov/index.php/elections/general_election_turnout_by_demographics">GA Secretary of State Primary results</a>, which I crosschecked with the <a href="http://results.enr.clarityelections.com/GA/74658/Web02-state.206999/#/access-to-races">GA Election Night Primary results</a>, to find the number of precincts that each county reported for the 2018 election. We only counted precincts that fell within counties, which you'll see a row of "NA" which account for these other precincts that didn't fall under any of the county codes. 

##Authors
Created by Jacquelyn Elias in Fall 2018