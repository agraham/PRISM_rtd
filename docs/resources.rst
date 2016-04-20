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

- **QA_STATUS** - Dropdown box, status of Observation in the QAQC process.
- **TIME_END** - Date field, date and time Observation ended.
- **TIME_START** - Date field, date and time Observaton started.
- **SURVEY_TYPE** - Dropdown box, survey type (or goals) of the Observation.
- **FORM_TYPE** - Dropdown box, form type used.
- **SURVEY_METHOD** - Dropdown box, vehicle used.
- **WEATHER** - Dropdown box w/ multiple additions, weather.
- **TIDE_HEIGHT** - Numeric field, tide height in feet.
- **TIDE_DIRECTION** - Dropdown box, tide direction.
- **WATER_LEVEL** - Dropdown box, predicted water level.
- **ESTIMATED_WATER_CHANGE** - Dropdown box, estimated water level change over the next 7 days (River/Stream).
- **ENTIRE_SEGMENT_SURVEYED** - YES/NO, was the entire segment surveyed?
- **SURVEYED_AREAS_NOO** - YES/NO, areas that were surveyed without a zone are considered NOO.
- **PERCENT_SEGMENT_SURVEYED** - Numeric field, % of segment surveyed.
- **AVG_INTERTIDAL_WIDTH** - Numeric field.
- **MAX_INTERTIDAL_WIDTH** - Numeric field.
- **BACKSHORE_WIDTH** - Numeric field.
- **UITZ_SHORELINE** - Dropdown box w/ multiple additions, UITZ shoreline type.
- **UITZ_SHORELINE_TYPE** - PRIMARY/SECONDARY, qualifies the UTIZ shoreline types chosen above.
- **LITZ_SHORELINE** - Dropdown box w/ multiple additions, LITZ shoreline type.
- **LITZ_SHORELINE_TYPE** - PRIMARY/SECONDARY, qualifies the LITZ shoreline types chosen above.
- **SUTZ_SHORELINE** - Dropdown box w/ multiple additions, SUTZ shoreline type.
- **SUTZ_SHORELINE_TYPE** - PRIMARY/SECONDARY, qualifies the SUTZ shoreline types chosen above.
- **OBSERVATION_ESI** - Dropdown box w/ multiple additions, ESI shoreline type.
- **ESI_TYPE** - PRIMARY/SECONDARY, qualifies the ESI shoreline types chosen above.
- **DOMINANT_VEGETATION_TYPE** - Text field, describes the dominant vegetation types present.
- **BACKSHORE** - Dropdown box w/ multiple additions, Backshore type.
- **BACKSHORE_TYPE** - PRIMARY/SECONDARY, qualifies the Backshore types chosen above.
- **STREAM_BED_FEATURE** - Dropdown box, stream bed character for River/Streams.
- **RIVER_CHANNEL_PATTERN** - Dropdown box, channel pattern for River/Streams.
- **RIVER_VALLEY_FORM** - Dropdown box, valley form for River/Streams.
- **CLIFF_HEIGHT** - Numeric field.
- **CLIFF_SLOPE** - Dropdown box.
- **PRIMARY_BACKSHORE_SUBSTRATE_TYPE** - Dropdown box.
- **BACKSHORE_VEGETATION_COVER** - Dropdown box, describes the vegetation cover in the backshore.
- **SHORELINE_WAVES** - Dropdown box, wave height observed in cm.
- **CHANNEL_WIDTH** - Numeric field, width of the River/Stream channel in meters.
- **ESTIMATED_WATER_DEPTH** - Numeric field, depth of the River/Stream channel in meters.
- **BAR_SHOAL_SUBSTRATE** - Dropdown box, substrate of Bar/Shoals if present.
- **FEATURE** - Dropdown box, list of Shoreline/River Features for Pre-Spill.
- **FEATURE_TYPE** - YES/NO, confirmation of Features listed above.
- **OPERATIONAL_ACCESS** - Dropdown box, Alongshore, Backshore and Backshore Staging Access items.
- **OPERATIONAL_ACCESS_TYPE** - YES/NO, confirmation of Features listed above.
- **ACCESS_RESTRICTIONS_FEATURES** - Text field, additional Access features/restrictions.
- **DEBRIS_AMOUNT** - Numeric field.
- **DEBRIS_AMOUNT_UNITS** - Dropdown box.
- **OILED_DEBRIS** - YES/NO.
- **DEBRIS_TYPE** - Dropdown box, list of primary debris type.
- **SURVEY_COMMENTS** - Text field, summary comments for Observation.
- **HUMAN_USE**
- **AVG_WATER_DEPTH_CORAL**
- **POTENTIAL_NEARBY_ACCESS**
- **ROAD_ACCESS_TYPE**
- **SITE_ACCESS_STAGING**
- **SITE_ACCESS_STAGING_TYPE**
- **SITE_ACCESS_INTERTIDAL**
- **SITE_ACCESS_INTERTIDAL_TYPE**
- **SITE_ACCESS_SUBTIDAL**
- **SITE_ACCESS_SUBTIDAL_TYPE**
- **ACCESS_ALONGSHORE_HEAVY_EQ_FEASIBILITY**
- **ACCESS_ALONGSHORE_HEAVY_EQ_FEASIBILITY_TYPE**
- **BEARING_CAPACITY_HEAVY_EQ_FEASIBILITY**
- **BEARING_CAPACITY_HEAVY_EQ_FEASIBILITY_TYPE**
- **BEACH_SLOPE_HEAVY_EQ_FEASIBILITY**
- **BEACH_SLOPE_HEAVY_EQ_FEASIBILITY_TYPE**
- **MAX_DISTANCE_TO_TEMP_STORAGE**
- **SEGMENT_PROTECTION_OBJECTIVES**
- **SEGMENT_PROTECTION_STRATEGIES**
- **POTENTIAL_PROTECTION_OPTIONS**
- **POTENTIAL_PROTECTION_OPTIONS_TYPE**
- **SHORELINE_TREATMENT_OBJECTIVES**
- **SHORELINE_TREATMENT_STRATEGIES**
- **POTENTIAL_TREATMENT_OPTIONS**
- **POTENTIAL_TREATMENT_OPTIONS_TYPE**
- **OTHER_POTENTIAL_OIL_BEHAVIOR**
- **SNOW_CONDITION**
- **SNOW_CONDITION_TYPE**
- **FROZEN_SPRAY_CONDITION**
- **FROZEN_SPRAY_CONDITION_TYPE**
- **FROZEN_SWASH_CONDITION**
- **FROZEN_SWASH_CONDITION_TYPE**
- **ICE_FOOT_CONDITION**
- **ICE_FOOT_CONDITION_TYPE**
- **ICE_PUSH_RIDGE_CONDITION**
- **ICE_PUSH_RIDGE_CONDITION_TYPE**
- **GROUNDED_FLOES_CONDITION**
- **GROUNDED_FLOES_CONDITION_TYPE**
- **GLACIER_ICE_CONDITION**
- **GLACIER_ICE_CONDITION_TYPE**
- **NEARSHORE_ICE_CONCENTRATION**
- **NEARSHORE_ICE_FORM**
- **NEARSHORE_ICE_AGE_AND_THICKNESS**
- **FAST_ICE**
- **TIDAL_CRACKS**
- **SURFACE_BEARING_CAPACITY**
- **SCAT_STATUS**
 
Zones
--------
Zones are part of an Observation and detail the surface oiling observed.  There can be multiple Zones within an Observation.

- **Entity 1** - description

  * Entity option1
  * Entity option2

- **Entity 2** - description

  * Entity option1
  * Entity option2
  
Pits
--------
Pits are part of a Zone and detail the subsurface oiling observed in the Zone.  There can be multiple Pits within a Zone.

- **Entity 1** - description

  * Entity option1
  * Entity option2

- **Entity 2** - description

  * Entity option1
  * Entity option2
  
Media
--------
Media are uploaded files to PRISM and can be Photographs, GPX files (GPS files) or scanned documents.

- **Entity 1** - description

  * Entity option1
  * Entity option2

- **Entity 2** - description

  * Entity option1
  * Entity option2
  
Shoreline Treatment Recommendations
------------------------------------
Shoreline Treatment Recommendations (STRs) detail the recommended work to be completed based on an Observation.  STRs are made up of one or many Zones.

- **Entity 1** - description

  * Entity option1
  * Entity option2

- **Entity 2** - description

  * Entity option1
  * Entity option2
