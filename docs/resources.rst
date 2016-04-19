Data Types (Resources)
========

Data Types (or Data Resources) are the items that can be collected and stored within PRISM.  These include Surveys, Segments, Observations, Zones, Pits, Media and Shoreline Treatment Recommedations.  These resources can be queried, viewed and exported within the PRISM application.

Surveys
--------
Surveys are specific to a single team on a single day.

- **Team Number** - Dropown list, team number (i.e. 1, 2, 7, etc.).

- **Survey Date** - Date field, day the survey took place on.

- **Season** - Dropdown list, season the survey took place in.

  * *Shoreline/Lake/River/Stream*
  
   * Wet
   * Dry
   * Winter/Ice
  * *Arctic*
  
   * Breakup/Thaw
   * Open Water
   * Freeze up transition
   * Frozen period

- **Logistics/Safety** - Text field, describes logistical and safety information for the entire survey.

- **Survey Summary** - Text field, describes survey activities and observations.

Segments
--------
Segments are geographic locations on a shoreline with a start and end point and usually defined by a homogenous shoreline type.

- **Segment ID** - Text field, a unique identifier for each Segment

- **Segment Length** - Numeric field, the length of the segment in meters.

- **Operational Division** - Text field, identifier of the OPS division the segment resides in.

- **Bank Position (River/Stream ony)** - Dropdown list, identifies the descending side of the river/stream the segment is on.

  * Left
  * Middle
  * Right

- **Administrative Subdivision** - Text field, lists the Subdivision Name and a dropbown box with options for Subdivision Type/Category.

  * *Subdivision Type/Category*
  
   * State
   * County
   * Municipality
   * Landowner
   * Local Name

- **Mapsheet** - Text field, identifier of possible Map Sheets the Segment may be referenced on.

- **Fetch Window** - Dropdown list, the angle (degrees) of potential wave exposure of the segment.

  * < 45
  * 45 - 120
  * 121 - 180
  * > 180
   
- **Fetch Distance** - Dropdown list, the potential distance (km) over water the wind may blow waves towards the segment.

  * < 5 km
  * 5 - 10 km
  * 10 - 50 km
  * > 50 km
 
Observations
-------------
Observations are data collected for one Segment on one day by a team.  This is the traditional SOS form (incuding Zones/Pits below).

- **Observation Start/End Time** - Date field, start and end date and times.

- **Survey Form** - Dropbown box, form type used for Observation.

  * CSOS
  * Lake
  * River
  * Stream
  * Tidal Flat
  * Mangrove
  * Wetland
  * Coral Reef
  * Arctic
  * Winter-CSOS
  * Winter-Lake
  * Winter-River
  * Winter-Stream
  * Winter-Tidal Flat
  * Winter-Wetland
  * Pre-Spill Shoreline
  * Pre-Spill River/Stream
  * Pre-Spill Lake
  * Pre-Spill Arctic

- **Survey Type** - Dropdown box, type of survey or purpose of the Observation.

  * SCAT
  * PIST
  * SIR
  * Other

- **Survey Method** - Dropdown box, vehicle used for Observation.

  * Foot
  * Boat
  * Airboat
  * Helicopter
  * Car
  * ATV
  * Aircraft
  * Overlook
  * Imagery
  * Video
  * Other

- **Entire Segment Surveyed** - YES/NO, does the Observation include the entire Segment length.

- **Percent Segment Surveyed** - Numeric, what percent of the Segment was surveyed.

- **Areas without Zones are NOO** - YES/NO, if there is not a Zone on part of the Segment that area is considered NOO.

- **Weather** - Dropdown box with multiple additions, weather observed during the Observation.

  * Entity option1
  * Entity option2

- **Tide Height** - Numeric, tide height in feet.

- **Tide Direction** - Dropdown box, direction of tide during Observation.

  * Rising
  * Falling
  * Slack

- **Water level** - Dropdown box, water level relative to that predicted.

  * Entity option1
  * Entity option2
 
- **Estimated Water Change (River/Stream)** - Dropdown box, estimated water level change over the next 7 days.

  * Rising
  * Falling
  * Same
  * Unknown

- **Shoreline Waves** - Dropdown box, waves height observed on shoreline.

  * Entity option1
  * Entity option2

- **Segment Comments** - Text field, general comments specific to the Observation.
 
- **SCAT Status** - Dropdown box, defined Status for the Observation/Segment at that time.

  * Entity option1
  * Entity option2
 
Zones
--------
Zones are ...

- **Entity 1** - description

  * Entity option1
  * Entity option2

- **Entity 2** - description

  * Entity option1
  * Entity option2
  
Pits
--------
Pits are ...

- **Entity 1** - description

  * Entity option1
  * Entity option2

- **Entity 2** - description

  * Entity option1
  * Entity option2
  
Media
--------
Media are ...

- **Entity 1** - description

  * Entity option1
  * Entity option2

- **Entity 2** - description

  * Entity option1
  * Entity option2
  
Shoreline Treatment Recommendations
------------------------------------
Shoreline Treatment Recommendations are ...

- **Entity 1** - description

  * Entity option1
  * Entity option2

- **Entity 2** - description

  * Entity option1
  * Entity option2
