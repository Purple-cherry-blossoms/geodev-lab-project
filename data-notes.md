# Data notes

## GRID3 NGA - Operational LGA Boundaries
-Source:https://data.grid3.org/
-Downloaded: 04-09-2026
-774 features, Multipolygon
-Columns: glolbalid(text), Uniq_id(numeric), time_stamp(date), editor(text), lga_name(text), lgacode(numeric), statename(text), statecode(text), source(text), amapcode(text).
-No nulls in lga_name.
-Covers my LGA fully.

## OSM roads extracted via QuickOSM
-Query: highway=* within port harcourt lga
-Extracted: 05-09-2026
-7731 features, lines
-No surface tags identified, so paved and unpaved cannot be seperated.
-Coverage is quite good around the feature, sparse towards the bottom left and some edges.
