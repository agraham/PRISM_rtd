Team Lead Data Review
=====================

The items below outline the easiest data flow to follow for a team member to begin reviwing their data after uploading to PRISM.

1. Was a new team member(s) created?
---------------------------------

If a team member(s) was not available in the list of members and you created a new one (adding name and phone number), add the additional information to the new personnel.

- Go the *Search* page and in the *Search bar* at the top type in the new persons name
- 

Search bar
--------

The Search bar at the top of the page allows for entry of keywords and data attributes to filter search results.  The text entered needs to  match data fields associated with the data resources in PRISM.  Search suggestions with the associated data field (in parentheses) will auto-populate  These data fields are detailed on the `Data Types (Resources) <resources.html>`_ page.

Example Search bar entries and results:

- Typing in HEAVY auto-populates the Search bar with several options, the first two of which are 'Pit Oiling Category' and 'Zone Oiling Category'.  Selecting 'Pit Oiling Category' will list all the pits with an oiling category of Heavy.
- Typing in text known to be in an Observation comment box will auto-populate with the text from that comment box.  Selecting that option list the Observation in the results.


Location Filter
----------------

Clicking on the *Location Filter* brings up the map and shows all resources with the area of interest.  Zooming into to a more specific area, clicking on the *Map Tools* button in the upper right of the map and then selecting *Limit search results to map extent* will filter the search results by those shown on the map.  Alternatively a polygon, line or point can be drawn on the map (by selecting the option in *Map Tools*) and buffered by a set distance to filter results by only those that fall within the defined buffer.

Time Filter
------------

Using the *Time Filter* allows one to filter data resources by dates associated with the resources. *Observation Start Time*, *Survey Date*, *Media Date*, *STR Status Data* or *Sample Date* can all be searched for by setting the date qualifier to either *Before*, *On*, or *After* a selected date.

Export
------------

Search results can be exported by clicking on the *Tools* button in the upper right.  Export can be in 3 possible formats:

- **.CSV** - comma delimited values (Excel viewable)
- **.KML** - keyhole markup language (Google Earth viewable)
- **.SHP** - shapefile (GIS software viewable)

Only the results that show up in the Search results list will be exported.  

Only Data Resources with geographic locations directly associated with them will show up in the **.KML** and **.SHP** exports.  These Resources inlcude Surveys, Segments, Zones, Pits and Media.
