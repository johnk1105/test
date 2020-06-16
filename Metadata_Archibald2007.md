# University of Victoria Spatial Data Repository

Created by JMK 16-06-2020
Maintained by the Restoration Futures Lab

### Metadata description --

This database includes spatial data of natural features and management activities at the University of Victoria (Harrop-Archibald, 2007). All attributes listed in the raw GIS files are listed and described. 

*** 

##<b>Data table metadata</b>
| File name | Shrub layer |	
| :---: | :---: |						
| Date created |varied|							
|Date last updated|16-06-2020|						
|Number of records|			
|Projection|EPSG:3005 - NAD83 - BC Albers|		

##<b>Data table structure and attribute description</b>
| Attribute   name      | Definition                                                                                                         | Unit | Type        | Attribute description                 |
|:-----------------------:|:-----------------------------------------------------------|------|-------------|---------------------------------------|
| Polynumber | Polygon | |Integer| |
| DomSpecies | Dominant species | | String | Refer to speices code |
| DomPercent | Dominant species percent | | Double |                                       |
| CodSpecies | Codominant species                                                                                                 |      |             |                                       |
| CodPercent            | Codominant species percent                                                                                         |      |             |                                       |
| SubSpecies            |                                                                                                                    |      |             |                                       |
| SubSpecies   Percent  |                                                                                                                    |      |             |                                       |
| Other#                | Other species presence, from   ascending order where 1 is the most prevalent (in %) compare to "other   species".  |      |             | e.g. Other1, Other2, Other3… Other(n) |
| Perecent#             | Other species percent occurance,   from ascending order where 1 is the most prevalent other species.               |      | Double      |                                       |
| Area                  | Area of patch                                                                                                      |      | real number |                                       |
***