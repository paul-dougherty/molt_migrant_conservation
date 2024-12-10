# molt_migrant_conservation

Scripts for "Molting strategy influences vulnerability to climate change in migratory birds."

All Daymet, eBird, and Breeding Bird Survey Data are available to download at https://daymet.ornl.gov/getdata, https://ebird.org/data/download, and https://www.pwrc.usgs.gov/bbs/rawdata/, respectively. We used the ``bbsBayes" package in Program R to retrieve and process all Breeding Bird Survey data.

## Repository Structure:

* **precip_data_prep:** scripts for downloading and wrangling Daymet precipitation data
  
* **ebird_arrival_mods:** scripts for preparing and analyzing eBird data to estimate interannual variation in stopover behavior
  * **ebird data prep:** prepares raw eBird data for modeling
  * **arrival_gams:** runs models and extracts posterior estimates for species molt stopover characteristics
  * **lazb_arrival_mods:** runs models exploring the relationship between interannual variaiton in molt stopover and monsoon conditions
 
* **bbs_data_prep:**
  * **trend_estimating_functions:** 

* **bbs_analysis:**


