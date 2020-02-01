Rough Custom Drupal module example of a quick API consumption for MBTA.

## API Documentation
https://mbta.com/developers/v3-api

## Unknowns
1. UX and user options - how much control does the user have?  
    - Starting point
    - Destinations
    - Limit time range
    - date range
2. What other information are we going to present? 
    - full trip information?
    - maps?
    - Live updates and predictions?

## Moving forward
1. Plan out rest of the UI / Screens to be completed
2. Lock down better ways to interact with the API to get / interact and manipulate the data
    - this could include using the Migrate API to save some of the data locally as content in our DB to create static views for the routes page.
    - The interaction with the API would likely still be on the fly to grab the most up to the minute information from /predictions
3. Need to understand the API structure a little more and what information is actually available. Because the places were unfamiliar it took a bit more to understand differences in schedule, trip, route, etc.
4. How are we going to use filters for searching? Views exposed filters maybe? Potentially just some query params from a GET request. 


## Estimate
Depends on what the vision is for the final product. If you wanted to build https://www.mbta.com/schedules/Red/schedule it's going to be quite some time to put all the functionality and smoothness to it together. But the functionality requested for Phase 1 is almost ready and could likely be completed in a few more hours of work depending on what was expected, fully, out of the phase. 

