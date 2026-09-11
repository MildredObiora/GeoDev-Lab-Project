# Data Notes

## GRID3_NGA_health_facilities_v2.0

- Source: https://data.grid3.org
- Downloaded: 7th September, 2026
- 218 features, points
- Columns: fid (Integer), OBJECTID (Integer), globalid(Text (string), nhfr_uid(Integer (32 bit), nhfr_facility_code(Text (string), country(Text (string), iso(Text(string), state(Text (string), lga(Text), lga_name_disagreement(Decimal), ward(Text), ward_name_disagreement(Decimal), facility_name(Text (string), facility_name_source(Text), ownership (Text), ownership_type (Text), facility_level (Text), facility_level_option (Text), latitude(Decimal), longitude(Decimal), geocoordinates_source(Text), last_updated(Text)
- No null value in health facility name
- Covers my Local government fully.


##GRID3 NGA – Roads v1.0 

- Source: https://data.grid3.org
- Downloaded: 7th September, 2026
- 6414, Line
- Column: fid (Integer), OBJECTID (Integer), id (Text), country (Text), iso3 (Text), source_id (Text), class (Text), speed_estimate (Integer), speed_estimate_method (Text), road_surface (Text), names (Text), subclass (Text), speed_limits (Text), date (Double), source_acronym (Text)
- No null value in Road name, just empty.
- Covers my Local government fully.


## GRID3 NGA – Operational Wards v1.0

- Source: https://data.grid3.org
- Downloaded: 7th September, 2026
- 33, Polygon
- Column: fid (Integer), globalid (Text), uniq_id (Integer), timestamp (Date), editor (Text), wardname (Text), wardcode (Text), lganame (Text), lgacode (Text), statename (Text), statecode (Text), amapcode (Text), status (Text), source (Text), urban (Text)
- No null value in Ward name
- Covers my Local government fully.

##GRID3 NGA – Operational LGA Boundaries

- Source: https://data.grid3.org
- Downloaded: 7th September, 2026
- 2, Polygon
- Column: fid (Integer), globalid (Text),uniq_id (Integer), timestamp (Text), editor (Text), lganame (Text), lgacode (Text), statename (Text), statecode (Text), source (Text), amapcode (Text)
- No null value in LGA name
- Covers my Local government fully.


## GRID3 NGA – Operational State Boundaries 

- Source: https://data.grid3.org
- Downloaded: 7th September, 2026
- 1, Polygon
- Column: fid (Integer), Shape_Leng (Decimal), Shape_Area (Decimal), ADM1_EN (Text), ADM1_PCODE (Text), ADM1_REF (Text), ADM1ALT1EN (Text), ADM1ALT2EN (Text), ADM0_EN (Text), ADM0_PCODE (Text), date (Date), validOn (Date), validTo (Date)
- No null value in State name
- Covers my State fully.
