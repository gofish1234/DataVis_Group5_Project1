# DataVis_Group5_Project1
This repo is for DataVis Group 5 project work 

Alonzo Morales: I added street intersection info from Minneapolis Centerline datafile to scooter datafile. I, then, using Geocoding API, obtained latitude and longitude for all scooter trips in the scooter datafile which included over 6,500 unique locations. I also obtained latitude and longitude for all neighborhoods in the Minneapolis crime datafile. Next, I plotted scooter locations on a map.Then, overlaid the scooter location map with the crime heatmap.

Mohamed Abdi: Took the total crime data in Minneapolis from 2017-2018. Cleaned up the data and organized it by neighborhood. Then I took a sum of all the crime in each neighborhood and made a dataframe. Converted that dataframe into a csv file and used that data to plot a map of Minneapolis and layer a heat map of crime over Minneapolis.

Chris Miller:  I combined the cities that the major scooter companies have operations, made an API call to get lat/lngs, which were converted to lists and visualized via jupyter gmaps.  I used seaborn to produce the boxplot summarizing mean crime rate for each type for the periods before the trial and during the trial.   I then used numpy to do a ttest on each crime category before and after to determine which changes were significant.  
