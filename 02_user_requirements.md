Here’s something pretty close to what they are after:
[Forestry Decision Support Tool](http://www.forestdss.org.uk/geoforestdss/esc4.jsp#)

It’s a forestry decision support tool with an interactive map to draw up all the data available for a particular area.
We wonder if this sort of system could be adapted for us so that you could click on each of the communities
where we have collected data and see the data for each site.
#### Each community has marker and when clicked it shows (key?) features for that community


The data table below the map would show several different elements e.g. antibiotic use, access to animal healthcare providers and environmental features.
This data will enable the user to identify for each community which are the most important factors impacting their risk of AMR.
#### Table based on drop-down menu

In the forestry tool, there are symbols showing suitability of each area for certain tree species. We could instead use symbols highlighting ‘high risk’ and ‘low risk’ elements for AMR development.
#### Use thresholds and data on selected community to populate symbols of risk on button click

These would be assigned based on a ‘risk threshold’ for each element, which we will define based on the data set. We would also like the tool to provide the user with a total score for each community, based on the sum of these elements.
#### Again calculate on button click

To the left hand side of the map there is a panel where you can manually adjust features.
#### If built in jupyter and with leaflet then use ipywidgets
This panel could provide an option to look at the historical situation vs the present day, so the user can explore how the parameters have changed over time and how this has impacted on the risk of AMR across the study sites.
#### Present day vs historic in drop-down menu
There could also be a way for people to manipulate the data to see what adjustments would be required for reduction of AMR risk.
#### Pretty big challenge, but if data is loaded as pandas dataframe then shouldn't be big issue manipulating underlying data temporarily

Finally, we would like to have the option for users to input their own data and view user generated content as part of the tool. Would this be a possibility?
#### Out of scope, next version certainly possible 

It would be great to hear your thoughts on this and whether based on the above info you could give a very rough estimate of how long it might take to implement?

 
