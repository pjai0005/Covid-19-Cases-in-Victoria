<<<<<<< HEAD
<<<<<<< HEAD
# METADATA FOR DIGITAL BOUNDARY FILES

Australian Statistical Geography Standard (ASGS) Volume 1 - Main Structure and Greater Capital City Statistical Areas (cat no. 1270.0.55.001)

**Data Currency**: 12 July 2016
**Presentation Format**: Digital boundaries
**Custodian**: Australian Bureau of Statistics (ABS)

## DESCRIPTION
**Abstract**:
The Australian Statistical Geography Standard (ASGS)  brings together in one framework all of the regions which the ABS and many others organisations use to collect, release and analyse geographically classified statistics. The ASGS ensures that these statistics are comparable and geospatially integrated and provides users with an coherent set of standard regions so that they can access, visualise, analyse and understand statistics.  The 2016 ASGS will be used for the 2016 Census of Population and Housing and progressively introduced into other ABS data collections. The ABS encourages the use of the ASGS by other organisations to improve the comparability and usefulness of statistics generally, and in analysis and visualisation of statistical and other data.

This publication, **Australian Statistical Geography Standard (ASGS) Volume 1 - Main Structure and Greater Capital City Statistical Areas** (cat no. 1270.0.55.001), deals with the ASGS Main Structure (Statistical Areas Level 1 - 4) and the Greater Capital City Statistical Areas (GCCSA). It outlines the conceptual basis of the ASGS Main Structure and the GCCSAs and their relationships to each other.  This product contains several elements including the ASGS manual, allocation tables, correspondences and the digital boundaries current for the ASGS Edition 2016 (date of effect 1 July 2016).

The digital boundaries for Volume 1 of the ASGS are the region types for the main structure and the GCCSAs. These region types are: 
* Mesh Block (MB) 
* Statistical Area Level 1 (SA1) 
* Statistical Area Level 2 (SA2) 
* Statistical Area Level 3 (SA3) 
* Statistical Area Level 4 (SA4) 
* Greater Capital City Statistical Areas (GCCSA)
* State and Territory (S/T).

**File Nomenclature**:
File names have the format `[type]_[YYYY]_[COVERAGE]` where: 
`[type]` represents the type of boundaries in each file
* MB = Mesh Block
* SA1 = Statistical Area Level 1 
* SA2 = Statistical Area Level 2 
* SA3 = Statistical Area Level 3 
* SA4 = Statistical Area Level 4 
* GCCSA = Greater Capital City Statistical Area 
* STE = State and Territory

`[YYYY]` represents the Australian Statistical Geography Standard (ASGS) Edition by year. `2016` is the current edition.
`[COVERAGE]` indicates the geographic area covered by the data as defined in the ASGS manual. Values will *usually* be `AUS` (for most boundaries) or `STE` (for Mesh Block boundaries).

**State and Territory Codes and Names**
Within the files, the States and Territories are identified by unique one digit codes.
| Code | State/Territory | 
|------|-----------------|
| 1 | New South Wales  |
| 2 | Victoria |
| 3 | Queensland |
| 4 | South Australia |
| 5 | Western Australia | 
| 6 | Tasmania |
| 7 | Northern Territory |
| 8 | Australian Capital Territory |
| 9 | Other Territories |

**Australia**
The code for Australia is shown as `036` where it appears as the parent geography of data released on a State and Territory level, or where coverage is for the whole of Australia.

This allows alignment with both the UN Statistical Division's *"Standard country or area codes for statistical use (M49)"* ( https://unstats.un.org/unsd/methodology/m49/ ) and ISO 3166-1 *"Codes for the representation of names of countries and their subdivisions"* alpha-3 codes ( https://www.iso.org/iso-3166-country-codes.html )

### File Attributes:
For each file type the field name, data type, and length is shown.

__Note__ - While metadata for each spatial unit in the ASGS is shown, any given file will only contain the referenced spatial unit, and the parent spatial units above it in the ASGS hierarchy. For instance, Mesh Block files have all parent levels, whilc SA4 only has SA4 and it's parents - STE and Australia.

**MapInfo (.mid/.mif & TAB) and Geopackage (.gpkg)**
| Count | Field               | Data Type | Length | Name                      |
|-------|---------------------|-----------|--------|---------------------------|
|  1    | MB_CODE_2016        | Character | 11     | 2016 Mesh Block Code       |
|  2    | MB_CATEGORY_2016    | Character | 50	   | 2016 Mesh Block Category   |
|  3    | SA1_MAINCODE_2016   | Character | 11     | 2016 SA1 Full Code        |
|  4    | SA1_7DIGITCODE_2016 | Character | 7      | 2016 SA1 7 digit Code     |
|  5    | SA2_MAINCODE_2016   | Character | 9      | 2016 SA2 Full Code        |
|  6    | SA2_5DIGITCODE_2016 | Character | 5      | 2016 SA2 5 digit Code     |
|  7    | SA2_NAME_2016       | Character | 50     | 2016 SA2 Name             |
|  8    | SA3_CODE_2016       | Character | 5      | 2016 SA3 Full Code        |
|  9    | SA3_NAME_2016       | Character | 50     | 2016 SA3 Name             |
| 10    | SA4_CODE_2016       | Character | 3      | 2016 SA4 Full Code        |
| 11    | SA4_NAME_2016       | Character | 50	   | 2016 SA4 Name             |
| 12    | GCCSA_CODE_2016     | Character | 5      | 2016 GCCSA Full Code      |
| 13    | GCCSA_NAME_2016     | Character | 50     | 2016 GCCSA Name           |
| 14    | STATE_CODE_2016     | Character | 1      | 2016 State/Territory Code |
| 15    | STATE_NAME_2016     | Character | 50     | 2016 State/Territory Name |
| 16    | AREA_ALBERS_SQKM    | Float     | -      | Area (Albers) in sq/km    |

**ESRI Shape Files (.shp)**
| Count | Field      | Data Type | Length | Name                      |
|-------|------------|-----------|--------|---------------------------|
|  1    | MB_CODE16  | Character | 11     | 2016 Mesh Block Code       |
|  2    | MB_CAT16   | Character | 50     | 2016 Mesh Block Category   |
|  3    | SA1_MAIN16 | Character | 11     | 2016 SA1 Full Code        |
|  4    | SA1_7DIG16 | Character | 7      | 2016 SA1 7 digit Code     |
|  5    | SA2_MAIN16 | Character | 9      | 2016 SA2 Full Code        |
|  6    | SA2_5DIG16 | Character | 5      | 2016 SA2 5 digit Code     |
|  7    | SA2_NAME16 | Character | 50     | 2016 SA2 Name             |
|  8    | SA3_CODE16 | Character | 5      | 2016 SA3 Full Code        |
|  9    | SA3_NAME16 | Character | 50     | 2016 SA3 Name             |
| 10    | SA4_CODE16 | Character | 3      | 2016 SA4 Full Code        |
| 11    | SA4_NAME16 | Character | 50     | 2016 SA4 Name             |
| 12    | GCC_CODE16 | Character | 5      | 2016 GCCSA Full Code      |
| 13    | GCC_NAME16 | Character | 50     | 2016 GCCSA Name           |
| 14    | STE_CODE16 | Character | 1      | 2016 State/Territory Code |
| 15    | STE_NAME16 | Character | 50     | 2016 State/Territory Name |
| 16    | AREASQKM16 | Float     | -      | Area (Albers) in sq/km    |

### XML METADATA FILE
The compressed download files include geospatial metadata data for each region type in Extensible Markup Language (XML) format. The geospatial metadata conforms to International Organisation for Standardization (ISO) geospatial metadata standard, `ISO 19115:2003`, and the associated XML implementation schema specified by `ISO 19139:2012`.

*DATA CURRENCY*
**Date of Effect**: 12 July 2016

*DATASET STATUS*
**Progress**: Completed dataset
**Maintenance and Update Frequency**:
No further updates for these boundaries planned. There will be a progressive release of the other regions that make up the ASGS until late 2018 (ASGS Volumes 2, 3, 4 and 5). The ASGS will be revised in 2021.

*ACCESS*
**Stored Data Format**:
Digital as separate files for each level of the Main Structure and GCCSA of the ASGS 2016.

**Available Format**:
The digital boundary files are in MapInfo TAB format (.TAB), MapInfo Interchange Format (.MID .MIF), Geopackage (.gpkg) and ESRI Shapefile (.shp) format. 

**Spatial Representation Type**: Vector

**Access Constraints**:
Copyright Commonwealth of Australia administered by the ABS.  Unless otherwise noted, content is licensed under a Creative Commons Attribution 2.5 Australia licence.

**Datum**: Geocentric Datum of Australia 1994 (GDA94)

**Projection**: Geographical (i.e. Latitudes and Longitudes)

**Geographic Extent**: Geographic Australia.

The Australian Statistical Geography Standard (ASGS) uses the Geographic definition of Australia, as set out in section 2B of the Acts Interpretation Act 1901, which currently defines Australia or the Commonwealth as meaning:

*"...the Commonwealth of Australia and, when used in a geographical sense, includes Norfolk Island, the Territory of Christmas Island and the Territory of Cocos (Keeling) Islands, but does not include any other external Territory."*

Included in this definition of Geographic Australia are the:
* States of New South Wales, Victoria, Queensland, South Australia, Western Australia and Tasmania
* Northern Territory
* Australian Capital Territory (ACT)
* Territory of Cocos (Keeling) Islands
* Territory of Christmas Island
* Jervis Bay Territory
* Territory of Norfolk Island

**Extent - Geographic Bounding Box**:

* North Bounding Latitude: -8
* South Bounding Latitude: -45
* West Bounding Latitude: 96
* East Bounding Latitude: 169

*DATA QUALITY*
**Lineage**:
Mesh Block boundaries were created using various sources including the PSMA digital datasets and ABS boundaries, zoning information from state planning agencies and imagery.

**Positional Accuracy**:
Positional accuracy is an assessment of the closeness of the location of the spatial objects in relation to their true positions on the earth's surface. The positional accuracy includes both a horizontal accuracy assessment and a vertical accuracy assessment. Positional accuracy for ABS boundaries is dependent on the accuracy of the features they have been aligned to. ABS boundaries are aligned to a number of layers supplied by the PSMA with an accuracy of `+/-50 mm`. PSMA layers and their positional accuracy are as follows: 
> ***Transport and Topography***
> `+/- 2 meters` in urban areas and `+/- 10 meters` in rural and remote areas
> ***CadLite***
> `+/- 2 meters` in urban areas and `+/- 10 meters` in rural and remote areas
> ***Administrative Boundaries***
> Derived from the cadastre data from each Australian State and Territory jurisdiction. 
> ***Greenspace and Hydrology*** 
> 90% of well-defined features are within `1mm` (at plot scale) of their true position, eg `1:500` equates to `+/- 0.5metre` and `1:25,000` equates to `+/- 25 metres`. 
> 
> Relative spatial accuracy of these themes reflects that of the jurisdictional source data. The accuracy is `+/- 2 metres` in urban areas and `+/- 10 metres` in rural and remote areas.

No "shift" of data as a means of "cartographic enhancement" to facilitate presentation has been employed for any real world feature. 

**Attribute Accuracy**:
All codes and labels for all levels within the ASGS Main Structure and GCCSAs are fully validated.

**Logical Consistency**:
Regions are closed polygons. Attribute records without spatial objects have been included in the data for administrative purposes.

**Completeness**:
All levels of the Main Structure and GCCSAs within the 2016 ASGS are represented.

*CONTACT INFORMATION*
**Contact Organisation**: Australian Bureau of Statistics
=======
=======
>>>>>>> mohammed_faizan
# METADATA FOR DIGITAL BOUNDARY FILES

Australian Statistical Geography Standard (ASGS) Volume 1 - Main Structure and Greater Capital City Statistical Areas (cat no. 1270.0.55.001)

**Data Currency**: 12 July 2016
**Presentation Format**: Digital boundaries
**Custodian**: Australian Bureau of Statistics (ABS)

## DESCRIPTION
**Abstract**:
The Australian Statistical Geography Standard (ASGS)  brings together in one framework all of the regions which the ABS and many others organisations use to collect, release and analyse geographically classified statistics. The ASGS ensures that these statistics are comparable and geospatially integrated and provides users with an coherent set of standard regions so that they can access, visualise, analyse and understand statistics.  The 2016 ASGS will be used for the 2016 Census of Population and Housing and progressively introduced into other ABS data collections. The ABS encourages the use of the ASGS by other organisations to improve the comparability and usefulness of statistics generally, and in analysis and visualisation of statistical and other data.

This publication, **Australian Statistical Geography Standard (ASGS) Volume 1 - Main Structure and Greater Capital City Statistical Areas** (cat no. 1270.0.55.001), deals with the ASGS Main Structure (Statistical Areas Level 1 - 4) and the Greater Capital City Statistical Areas (GCCSA). It outlines the conceptual basis of the ASGS Main Structure and the GCCSAs and their relationships to each other.  This product contains several elements including the ASGS manual, allocation tables, correspondences and the digital boundaries current for the ASGS Edition 2016 (date of effect 1 July 2016).

The digital boundaries for Volume 1 of the ASGS are the region types for the main structure and the GCCSAs. These region types are: 
* Mesh Block (MB) 
* Statistical Area Level 1 (SA1) 
* Statistical Area Level 2 (SA2) 
* Statistical Area Level 3 (SA3) 
* Statistical Area Level 4 (SA4) 
* Greater Capital City Statistical Areas (GCCSA)
* State and Territory (S/T).

**File Nomenclature**:
File names have the format `[type]_[YYYY]_[COVERAGE]` where: 
`[type]` represents the type of boundaries in each file
* MB = Mesh Block
* SA1 = Statistical Area Level 1 
* SA2 = Statistical Area Level 2 
* SA3 = Statistical Area Level 3 
* SA4 = Statistical Area Level 4 
* GCCSA = Greater Capital City Statistical Area 
* STE = State and Territory

`[YYYY]` represents the Australian Statistical Geography Standard (ASGS) Edition by year. `2016` is the current edition.
`[COVERAGE]` indicates the geographic area covered by the data as defined in the ASGS manual. Values will *usually* be `AUS` (for most boundaries) or `STE` (for Mesh Block boundaries).

**State and Territory Codes and Names**
Within the files, the States and Territories are identified by unique one digit codes.
| Code | State/Territory | 
|------|-----------------|
| 1 | New South Wales  |
| 2 | Victoria |
| 3 | Queensland |
| 4 | South Australia |
| 5 | Western Australia | 
| 6 | Tasmania |
| 7 | Northern Territory |
| 8 | Australian Capital Territory |
| 9 | Other Territories |

**Australia**
The code for Australia is shown as `036` where it appears as the parent geography of data released on a State and Territory level, or where coverage is for the whole of Australia.

This allows alignment with both the UN Statistical Division's *"Standard country or area codes for statistical use (M49)"* ( https://unstats.un.org/unsd/methodology/m49/ ) and ISO 3166-1 *"Codes for the representation of names of countries and their subdivisions"* alpha-3 codes ( https://www.iso.org/iso-3166-country-codes.html )

### File Attributes:
For each file type the field name, data type, and length is shown.

__Note__ - While metadata for each spatial unit in the ASGS is shown, any given file will only contain the referenced spatial unit, and the parent spatial units above it in the ASGS hierarchy. For instance, Mesh Block files have all parent levels, whilc SA4 only has SA4 and it's parents - STE and Australia.

**MapInfo (.mid/.mif & TAB) and Geopackage (.gpkg)**
| Count | Field               | Data Type | Length | Name                      |
|-------|---------------------|-----------|--------|---------------------------|
|  1    | MB_CODE_2016        | Character | 11     | 2016 Mesh Block Code       |
|  2    | MB_CATEGORY_2016    | Character | 50	   | 2016 Mesh Block Category   |
|  3    | SA1_MAINCODE_2016   | Character | 11     | 2016 SA1 Full Code        |
|  4    | SA1_7DIGITCODE_2016 | Character | 7      | 2016 SA1 7 digit Code     |
|  5    | SA2_MAINCODE_2016   | Character | 9      | 2016 SA2 Full Code        |
|  6    | SA2_5DIGITCODE_2016 | Character | 5      | 2016 SA2 5 digit Code     |
|  7    | SA2_NAME_2016       | Character | 50     | 2016 SA2 Name             |
|  8    | SA3_CODE_2016       | Character | 5      | 2016 SA3 Full Code        |
|  9    | SA3_NAME_2016       | Character | 50     | 2016 SA3 Name             |
| 10    | SA4_CODE_2016       | Character | 3      | 2016 SA4 Full Code        |
| 11    | SA4_NAME_2016       | Character | 50	   | 2016 SA4 Name             |
| 12    | GCCSA_CODE_2016     | Character | 5      | 2016 GCCSA Full Code      |
| 13    | GCCSA_NAME_2016     | Character | 50     | 2016 GCCSA Name           |
| 14    | STATE_CODE_2016     | Character | 1      | 2016 State/Territory Code |
| 15    | STATE_NAME_2016     | Character | 50     | 2016 State/Territory Name |
| 16    | AREA_ALBERS_SQKM    | Float     | -      | Area (Albers) in sq/km    |

**ESRI Shape Files (.shp)**
| Count | Field      | Data Type | Length | Name                      |
|-------|------------|-----------|--------|---------------------------|
|  1    | MB_CODE16  | Character | 11     | 2016 Mesh Block Code       |
|  2    | MB_CAT16   | Character | 50     | 2016 Mesh Block Category   |
|  3    | SA1_MAIN16 | Character | 11     | 2016 SA1 Full Code        |
|  4    | SA1_7DIG16 | Character | 7      | 2016 SA1 7 digit Code     |
|  5    | SA2_MAIN16 | Character | 9      | 2016 SA2 Full Code        |
|  6    | SA2_5DIG16 | Character | 5      | 2016 SA2 5 digit Code     |
|  7    | SA2_NAME16 | Character | 50     | 2016 SA2 Name             |
|  8    | SA3_CODE16 | Character | 5      | 2016 SA3 Full Code        |
|  9    | SA3_NAME16 | Character | 50     | 2016 SA3 Name             |
| 10    | SA4_CODE16 | Character | 3      | 2016 SA4 Full Code        |
| 11    | SA4_NAME16 | Character | 50     | 2016 SA4 Name             |
| 12    | GCC_CODE16 | Character | 5      | 2016 GCCSA Full Code      |
| 13    | GCC_NAME16 | Character | 50     | 2016 GCCSA Name           |
| 14    | STE_CODE16 | Character | 1      | 2016 State/Territory Code |
| 15    | STE_NAME16 | Character | 50     | 2016 State/Territory Name |
| 16    | AREASQKM16 | Float     | -      | Area (Albers) in sq/km    |

### XML METADATA FILE
The compressed download files include geospatial metadata data for each region type in Extensible Markup Language (XML) format. The geospatial metadata conforms to International Organisation for Standardization (ISO) geospatial metadata standard, `ISO 19115:2003`, and the associated XML implementation schema specified by `ISO 19139:2012`.

*DATA CURRENCY*
**Date of Effect**: 12 July 2016

*DATASET STATUS*
**Progress**: Completed dataset
**Maintenance and Update Frequency**:
No further updates for these boundaries planned. There will be a progressive release of the other regions that make up the ASGS until late 2018 (ASGS Volumes 2, 3, 4 and 5). The ASGS will be revised in 2021.

*ACCESS*
**Stored Data Format**:
Digital as separate files for each level of the Main Structure and GCCSA of the ASGS 2016.

**Available Format**:
The digital boundary files are in MapInfo TAB format (.TAB), MapInfo Interchange Format (.MID .MIF), Geopackage (.gpkg) and ESRI Shapefile (.shp) format. 

**Spatial Representation Type**: Vector

**Access Constraints**:
Copyright Commonwealth of Australia administered by the ABS.  Unless otherwise noted, content is licensed under a Creative Commons Attribution 2.5 Australia licence.

**Datum**: Geocentric Datum of Australia 1994 (GDA94)

**Projection**: Geographical (i.e. Latitudes and Longitudes)

**Geographic Extent**: Geographic Australia.

The Australian Statistical Geography Standard (ASGS) uses the Geographic definition of Australia, as set out in section 2B of the Acts Interpretation Act 1901, which currently defines Australia or the Commonwealth as meaning:

*"...the Commonwealth of Australia and, when used in a geographical sense, includes Norfolk Island, the Territory of Christmas Island and the Territory of Cocos (Keeling) Islands, but does not include any other external Territory."*

Included in this definition of Geographic Australia are the:
* States of New South Wales, Victoria, Queensland, South Australia, Western Australia and Tasmania
* Northern Territory
* Australian Capital Territory (ACT)
* Territory of Cocos (Keeling) Islands
* Territory of Christmas Island
* Jervis Bay Territory
* Territory of Norfolk Island

**Extent - Geographic Bounding Box**:

* North Bounding Latitude: -8
* South Bounding Latitude: -45
* West Bounding Latitude: 96
* East Bounding Latitude: 169

*DATA QUALITY*
**Lineage**:
Mesh Block boundaries were created using various sources including the PSMA digital datasets and ABS boundaries, zoning information from state planning agencies and imagery.

**Positional Accuracy**:
Positional accuracy is an assessment of the closeness of the location of the spatial objects in relation to their true positions on the earth's surface. The positional accuracy includes both a horizontal accuracy assessment and a vertical accuracy assessment. Positional accuracy for ABS boundaries is dependent on the accuracy of the features they have been aligned to. ABS boundaries are aligned to a number of layers supplied by the PSMA with an accuracy of `+/-50 mm`. PSMA layers and their positional accuracy are as follows: 
> ***Transport and Topography***
> `+/- 2 meters` in urban areas and `+/- 10 meters` in rural and remote areas
> ***CadLite***
> `+/- 2 meters` in urban areas and `+/- 10 meters` in rural and remote areas
> ***Administrative Boundaries***
> Derived from the cadastre data from each Australian State and Territory jurisdiction. 
> ***Greenspace and Hydrology*** 
> 90% of well-defined features are within `1mm` (at plot scale) of their true position, eg `1:500` equates to `+/- 0.5metre` and `1:25,000` equates to `+/- 25 metres`. 
> 
> Relative spatial accuracy of these themes reflects that of the jurisdictional source data. The accuracy is `+/- 2 metres` in urban areas and `+/- 10 metres` in rural and remote areas.

No "shift" of data as a means of "cartographic enhancement" to facilitate presentation has been employed for any real world feature. 

**Attribute Accuracy**:
All codes and labels for all levels within the ASGS Main Structure and GCCSAs are fully validated.

**Logical Consistency**:
Regions are closed polygons. Attribute records without spatial objects have been included in the data for administrative purposes.

**Completeness**:
All levels of the Main Structure and GCCSAs within the 2016 ASGS are represented.

*CONTACT INFORMATION*
**Contact Organisation**: Australian Bureau of Statistics
<<<<<<< HEAD
>>>>>>> yanhui_li
=======
>>>>>>> mohammed_faizan
For further information email <client.services@abs.gov.au> or contact the National Information and Referral Service (NIRS) on `1300 135 070`.