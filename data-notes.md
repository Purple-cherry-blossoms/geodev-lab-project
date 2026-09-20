# Data notes

## GRID3 NGA - Operational LGA Boundaries
-Source:https://data.grid3.org/
-Downloaded: 04-09-2026
-774 features, Multipolygon
-Columns: glolbalid(text), Uniq_id(numeric), time_stamp(date), editor(text), lga_name(text), lgacode(numeric), statename(text), statecode(text), source(text), amapcode(text).
-No nulls in lga_name.
-Covers my LGA fully.

## OSM roads extracted via QuickOSM
- Query: highway=* within port harcourt lga
- Extracted: 05-09-2026
- 7731 features, lines
- Only quiet a few surface tags identified, paved and unpaved cannot be seperated, bunt will check for reliability.
- Coverage is quite good around the feature, sparse towards the bottom left and some edges.


## OSM roads Port Harcourt LGA
- Extracted: 05-09-2026 via, QuickOSM highway=* 
- 7733 features, lines.
- Completeness: Very good in built-up areas. Compared familiar streets 90% are named and present.
- Currency: Most edits 2020-2025
- Positional: Roads align well with Esri sattelite street maps
- Attribute: Only quite a few surface tags identified, paved and unpaved cannot be seperated, will check for reliability.
- Fitness:Fit for adequuate analysis in main areas. Not fit for paved road questons.


## OSM roads Port Harcourt LGA
- Extracted:05-09-2026 via, QuickOSM highway=* 
- 190 features, Points.
- Completeness:Very spares within boundary region but a large cluster towards the NE area slightly outsidde the bounadry.
- Currency: Most edits 2020-2025
- Positional: Most points are null but aligned
- Attribute: Only 2% tags are mentioned. 
- Fitness: FIt for locating certain features but not enough for analysis.

- 



