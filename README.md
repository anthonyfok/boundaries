# boundaries
Boundary geometries for model results.  All geometries in this repo are generated in GeoPackage format.

 - Geometry_ADAUID.gpkg
	- Aggregate dissemination area geometry
 - Geometry_CANADA.gpkg
	- Canada outline geometry
 - Geometry_CDUID.gpkg
	 - Census Division geometry
 - Geometry_CSDUID.gpkg
	- Census Subdivision geometry, simplified polygon at 0.005 degrees. 
 - Geometry_DAUID.gpkg
	- Dissemination Area geometry
 - Geometry_ERUID.gpkg
	- Economic Region geometry
 - Geometry_FSAUID.gpkg
	- Forward Sortation Area geometry
 - Geometry_SAUID.gpkg
	 -  Settled area geometry
 - opendrr-boundaries.sql
 	 - SQL backup of boundaries schema used in OpenDRR PostgresSQL database.  Contains all geopackages in this repository, indexed.
 - LandGov_v1.csv
	 - Record of all settled areas and whether they are managed under provincial/territorial authority or through other land management frameworks such as Indian Land, Indian Reserve or Land Claims.
 
  Adapted from Statistics Canada, 2016 Census - Boundary files, 2020. This does not constitute an endorsement by Statistics Canada of this product.

## hexbin_4326

The hex grid collection is a series of hexagonal geometries and tables developed to help users view the national human settlement layers at different hexagonal aggregation levels outside of the conventional census boundaries.  The hex grid geometries were created in QGIS with the MMQGIS plugin using the Canadian, provincial, and territorial boundary extents at various x grid spacings.  The reference tables are generated and contains information needed for aggregation purposes of the national human settlement layers up to the given hex grid geometry.  

 - HexGrid_1km_{P/T}.gpkg, HexGrid_1km_{P/T}\_unclipped.gpkg
    - Clipped/unclipped hexagonal geometry of provinces and territories based on a x grid spacing of approximately 0.01 degrees.
 - HexGrid_5km.gpkg, HexGrid_5km_unclipped.gpkg,
    - Clipped/unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 0.05 degrees.
 - HexGrid_10km.gpkg, HexGrid_10km_unclipped.gpkg
    - Clipped/unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 0.1 degrees.
 - HexGrid_25km.gpkg, HexGrid_25km_unclipped.gpkg
    - Clipped/unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 0.25 degrees.
 - HexGrid_50km_unclipped.gpkg
    - Unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 0.5 degrees.
 - HexGrid_100km_unclipped.gpkg
    - Unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 1 degree.
 - HexGrid_GlobalFabric.gpkg
    - Hexagonal geometry extents of Canada based off GEM’s global fabric hex grid.
 - SAUID_HexGrid.gpkg, SAUID_HexGrid_unclipped.gpkg
	- Table referencing the centroid of each settled area id (SAUID) to the various HexGrid geometries (5km,10km,25km,50km,100km) used for aggregation purposes.
- SAUID_HexGrid_1km_intersect.gpkg, SAUID_HexGrid_1km_intersect_unclipped.gpkg
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_1km_{P/T} geometry used for aggregation purposes.
- SAUID_HexGrid_5km_intersect.gpkg, SAUID_HexGrid_5km_intersect_unclipped.gpkg
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_5km geometry used for aggregation purposes.
- SAUID_HexGrid_10km_intersect.gpkg, SAUID_HexGrid_10km_intersect_unclipped.gpkg
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_10km geometry used for aggregation purposes.
- SAUID_HexGrid_25km_intersect.gpkg, SAUID_HexGrid_25km_intersect_unclipped.gpkg
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_25km geometry used for aggregation purposes.
- SAUID_HexGrid_50km_intersect_unclipped.gpkg
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_50km geometry used for aggregation purposes.
- SAUID_HexGrid_100km_intersect_unclipped.gpkg
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_100km geometry used for aggregation purposes.
- SAUID_HexGrid_GlobalFabric_intersect.gpkg
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_GlobalFabric geometry used for aggregation purposes.
