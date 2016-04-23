Team Lead Data Entry
=====================

The Search Page provides multiple ways to filter and query PRISM data and multiple formats to export the data.  Search results are present in list form on the page and can be clicked on to view the assocaited data report.  Alternatively, the related data resources of the item or a map showing its location can be viewed instead.

Clicking on the *Location Filter* initially will bring up the map and show all available data resources.  Additional features of the  *Location Filter* are discussed below.

**The search options below are additive and can be use singly or together to help refine the search.**

Popular Searches
------------

*Popular Searches* are initially presented on the Search Page, allowing key searches to performed with a single click.

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
