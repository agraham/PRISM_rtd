Team Lead Data Review Steps
============================

The steps below outline the easiest data flow to follow for the Team Lead to begin reviewing their data after uploading to PRISM.

*If a new option needs to be added to any of the dropdown lists talk with the Polaris Database Manager or Administrator*

1. Was a new team member(s) created?
---------------------------------

If a team member(s) was not available in the list of members and you created a new one (adding name and phone number), add the additional information to the entry for the new personnel.

- Go the *Search* page and in the *Search bar* at the top type in the new persons name
- When the search result shows up click on *Edit* under the entry
- On the *Edit form* add the team member's **Organization**, **Role**, **Email Address** and **Phone Number** if necessary
- If a new option needs to be added to any of the dropdown lists talk with the Polaris Database Manager or Administrator
- Click *Save* at the top (or *Discard* to start over)

2. Was a new Segment(s) created?
---------------------------------

If a new Segment(s) was created during the Survey add additional information to the new Segment entry.

- Go the *Search* page and in the *Search bar* at the top type in the new Segment ID
- When the search result shows up click on *Edit* under the entry
- On the *Edit form* add additional information if known
- Adjust the Segment geometry on the *Map*

  * The straight line that shows on the *Map* is drawn between the *Start* and *End* points created in the field
  * Use the cursor to click on and move the straight line to match the shoreline and modify the Segment geometry
  * Only change the Start/End points if absolutely necessary as these come from the GPS points collected in the field and should be fairly accurate

- Click *Save* at the top (or *Discard* to start over)

3. Upload GPX track file as a Media item
-----------------------------------------

- Download the **.GPX** file from your GPS or GPS app
- Review the file in a GPS software (such as `Garmin Base Camp <http://www.garmin.com/en-US/shop/downloads/basecamp>`_)

  * Make sure only today's data are part of the track (delete previous days track points)
  * Make sure on the field portion of the track is saved (delete portions that were recorded in the ICP or on the road traveling)
  
- Save the file with a new name following this convention:  **YYYY-MM-DD_TEAM-#.gpx**
- Create a new *Media* item for the GPX file

  * Click on *Resource Manager* and then *Media*
  * Upload the new GPX file
  * Select today's **Date**
  * For **Media Type** select *GPS trackline*
  * Add a **Caption** that includes the date and team
  * Add a **Media Tag** that includes the Team number
  * Leave the **Geometry** (Map) empty
  * Click *Save* at the top (or *Discard* to start over)
  
4. Review Observation Data
-----------------------------------------

Review the Observation, Zone, Pit and Photo data collected in the field.

- Find today's Survey conducted by your team

  * Go to the *Search* page and under *Popular Searches* select the search for Surveys by your team
  * Click on *Time Filter* at the top and select *Survey Date*, *On*, and today's date
  * Click on the Survey name in the Search results

- The list of Observations (by Segment) you visited will be at the top of the Survey report
- Right click on an Observation and *Open in a new window* 
- The Observation report for the Segment selected will open in a new window
- Review all the data in the report to make sure it is correct and nothing is missing
- To add/edit data for the **Observation** click on the *Edit* button at the top of the report

  * Edit data in the Observation Edit form and then select *Save* at the top (or *Discard* to start over)
  * Once saved close the window 
  * Refresh the Observation report to see the changes
  
- To add/edit data for a **Zone or Pit** click on the *Edit* button associated with the record

  * Edit data in the Zone or Pit Edit form and then select *Save* at the top (or *Discard* to start over)
  * Once saved close the window 
  * Refresh the Observation report to see the changes
  
- To add/edit data for a **Photo** click on the Photo and then the *Edit* at the top of the report

  * Edit data in the Photo form and then select *Save* at the top (or *Discard* to start over)
  * Once saved close the window
  * Refresh the Observation report to see the changes
  
- If an Observation is complete (including associated Zones, Pits and Photos) edit the Observation and change the **QA STATUS** to *TL Approved* 
- Repeat these steps for all of the Observations you completed today
- Once completed, double check the **QA Status** of all your Observations

  * Go to the *Search* page and select the *Observations-DRAFT* search
  * This will show all Observations (including those by other teams) which have not been changed to *TL Approved*
  * Refine the search by selecting the *Location Filter* at the top and zoom into the area you surveyed today, click on the *Map Tools* button and select *Limit search results to map extent*
  * This will help limit the search results to only those in the area you surveyed (although other Team's Observations may show up)
  * Check the Observation names, and if any of them are your Observations then repeat the steps above to review and change the **QA STATUS** to *TL Approved*
 
5. Create STRs
-----------------

Create any STRs that are necessary and relate them to the Zones they are associated with.

- Click on *Resource Manager* and then *Shoreline Treatment Recommendation*
- Set the **QA STATUS** to *Draft (TL Created)*
- Set the **STR Number** to your team number with an incremental number at the end that counts up with each STR you create (i.e. Team1-001, Team1-002, etc.)
- Fill in the appropriate STR data as necessary
- Click *Save* at the top (or *Discard* to start over)
- Relate the associated *Zones* to the *STR*

  * Go back to the Observations(s) that the Zones are a part of
  * Click on the *Edit* button next to the Zones and select *Related Resources* on the left
  * Click on *Find Resources* in the upper right
  * Click on *Attribute Filter* at the top and type in the STR number you just created in the *Search bar*
  * Click *Add Relationship* next to the STR in the Search results
  * Click the *Add* button and then *Save Edits*
  * Do this for all Zones related to the STR
 
- Repeat the process for each STR you create

6. Update the Survey/Daily Summary report
------------------------------------------

The Survey/Daily Summary report is an overview of the activities for your team for the day, it doubles as a Survey report and the team summary.

- Select the *Survey* you completed today and view the report
- Review the data and click on the *Edit* button in the upper right to edit
- Fill in additional information in the **Logistics/Safety** and **Survey Summary** sections
- Add your GPX trackline to the map (this will show your trackline on the map)

  * On the map click *Add Geometry*
  * Select *Add from .gpx,.kml, or .geojson* and select the GPX file you saved in Step 3 above
  
- Relate the GPX media resource to the Survey

  * Click *Related Resources* in the toolbar at the left
  * Click on *Find Resources* in the upper right
  * Click on *Attribute filter* at the top and type in the file name of the GPX file
  * Click *Add Relationship* next to the file in the Search results
  * Click the *Add* button and then *Save Edits*
