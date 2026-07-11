# rajshahi-city-education-service-analysis

## Spatial Service Area Analysis of Primary Schools in Rajshahi City Corporation (RCC)

## Project Overview

This project evaluates the spatial accessibility of primary education
facilities within Rajshahi City Corporation (RCC), Bangladesh.

The study uses GIS-based spatial analysis techniques to identify: -
Served areas - Overserved areas - Underserved areas

A 500-meter service area was considered as the standard accessibility
distance for primary schools.

## Study Area

Rajshahi City Corporation (RCC), Bangladesh.

### Projection: Bangladesh Transverse Mercator (BTM)

All spatial calculations were performed using meter-based projection for
accurate distance and area measurement.

## Project Objectives

1.  Prepare RCC boundary polygon using ward boundary spatial data.

2.  Generate 500-meter service areas around primary schools.

3.  Calculate percentage of:

    -   Served area
    -   Overserved area
    -   Underserved area

4.  Perform accessibility analysis:

    -   Entire RCC area
    -   Ward-wise analysis
    -   Comparison with RCC area
    -   Comparison with ward area

5.  Calculate population accessibility:

    -   Served population
    -   Overserved population
    -   Underserved population

6.  Identify multiple service coverage:

    -   Double served areas
    -   Triple served areas
    -   Multiple served areas

## Input Data

1.  Education Facilities

Description: Point dataset containing locations of primary education
facilities.

Geometry: Point

Purpose: - Generate school service areas - Analyze spatial distribution
of facilities

2.  Ward Boundaries

Description: Polygon dataset containing RCC ward boundaries.

Geometry: Polygon

Purpose: - Prepare RCC boundary - Perform ward-level accessibility
analysis

## Methodology Workflow

Ward Boundary Data

        |
        v

Dissolve Ward Polygons

        |
        v

Create RCC Boundary

        |
        v

Prepare Education Facility Locations

        |
        v

Generate 500m Service Areas

        |
        v

Overlay Analysis

        |
        v

Accessibility Classification

        |
        v

Area and Population Statistics

        |
        v

##Maps and Reports

##Spatial Analysis

Service Area Standard: 500 meters

Served Area

Area covered by at least one primary school service area.

Condition: Service Count >= 1

Overserved Area

Area covered by multiple school service areas.

Double Served: Service Count = 2

Triple Served: Service Count = 3

Multiple Served: Service Count > 3

Underserved Area

Area outside all primary school service areas.

Condition: Service Count = 0

Required Outputs

The project should contain:

1.  RCC Boundary Map

File: rcc_boundary_map.png

2.  Primary School Location Map

File: primary_school_locations_map.png

3.  500m Service Area Map

File: 500m_school_service_area_map.png

4.  Served, Overserved and Underserved Map

File: served_overserved_underserved_map.png

5.  Multiple Service Coverage Map

File: multiple_service_coverage_map.png

## Statistical Outputs

##Area Analysis:

-   Total RCC area
-   Served area percentage
-   Overserved area percentage
-   Underserved area percentage

## Ward Analysis:

-   Ward ID
-   Ward area
-   Served percentage
-   Overserved percentage
-   Underserved percentage

## Population Analysis:

-   Total population
-   Served population
-   Overserved population
-   Underserved population

## Project Folder Structure

Project_02_RCC_Service_Area_Analysis/

|– README.txt | |– Raw_Data/ | |– Education Facilities | |– Ward
Boundaries | |– outputs/ | |– Maps | |– Tables | |– Analysis Results |
|– Project_description.docx | |– Project_Solution.docx

## Software Used

GIS Software: - ArcGIS and ArcGIS Pro

Spatial Analysis Tools: - Buffer - Dissolve - Clip - Intersect - Spatial
Join - Overlay Analysis - Field Calculator

## Coordinate Reference System

Projection: Bangladesh Transverse Mercator (BTM)

Unit: Meters

Project Deliverables

-   RCC boundary polygon
-   Primary school service area analysis
-   500m accessibility assessment
-   Served area calculation
-   Overserved area identification
-   Underserved area detection
-   Ward-level accessibility statistics
-   Population accessibility assessment
-   Multiple service coverage analysis
-   GIS maps and reports

## Limitations

-   Results depend on the accuracy of input spatial datasets.
-   A fixed 500-meter service distance was applied.
-   Population results depend on available demographic information.
-   Actual accessibility may vary due to roads and physical barriers.

# Author

Sarwar Jony

GIS Analyst

License

This project is shared for academic and research purposes.

# External datasets remain subject to their original licenses and restrictions.
