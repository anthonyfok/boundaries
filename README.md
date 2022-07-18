  All geometries in this repo are generated in GeoPackage format and compressed in 7-Zip format.
  7-Zip can be downloaded and installed at https://www.7-zip.org/

# boundaries
Boundary geometries for model results. All geometries in EPSG 4326.

 - Geometry_ADAUID.7z
	- Aggregate dissemination area geometry
 - Geometry_CANADA.7z
	- Canada outline geometry
 - Geometry_CDUID.7z
	 - Census Division geometry
 - Geometry_CSDUID.7z
	- Census Subdivision geometry, simplified polygon at 0.005 degrees. 
 - Geometry_DAUID.7z
	- Dissemination Area geometry
 - Geometry_ERUID.7z
	- Economic Region geometry
 - Geometry_FSAUID.7z
	- Forward Sortation Area geometry
 - Geometry_SAUID.7z
	 -  Settled area geometry
 - LandGov_v1.csv
	 - Record of all settled areas and whether they are managed under provincial/territorial authority or through other land management frameworks such as Indian Land, Indian Reserve or Land Claims.
 
  Adapted from Statistics Canada, 2016 Census - Boundary files, 2020. This does not constitute an endorsement by Statistics Canada of this product.

## hexgrid_4326

The hex grid collection is a series of hexagonal geometries and tables developed to help users view the national human settlement layers at different hexagonal aggregation levels outside of the conventional census boundaries.  The hex grid geometries were created in QGIS with the MMQGIS plugin using the Canadian, provincial, and territorial boundary extents at various x grid spacings.  The reference tables are generated and contains information needed for aggregation purposes of the national human settlement layers up to the given hex grid geometry.  All geometries in EPSG 4326.

 - HexGrid_1km_{P/T}.gpkg, HexGrid_1km_{P/T}\_unclipped.7z
    - Clipped/unclipped hexagonal geometry of provinces and territories based on a x grid spacing of approximately 0.01 degrees.
 - HexGrid_5km.7z, HexGrid_5km_unclipped.7z
    - Clipped/unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 0.05 degrees.
 - HexGrid_10km.7z, HexGrid_10km_unclipped.7z
    - Clipped/unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 0.1 degrees.
 - HexGrid_25km.7z, HexGrid_25km_unclipped.7z
    - Clipped/unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 0.25 degrees.
 - HexGrid_50km_unclipped.7z
    - Unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 0.5 degrees.
 - HexGrid_100km_unclipped.7z
    - Unclipped hexagonal geometry of Canada based on a x grid spacing of approximately 1 degree.
 - HexGrid_GlobalFabric.7z
    - Hexagonal geometry extents of Canada based off GEM’s global fabric hex grid.
 - SAUID_HexGrid.7z, SAUID_HexGrid_unclipped.7z
	- Table referencing the centroid of each settled area id (SAUID) to the various HexGrid geometries (5km,10km,25km,50km,100km) used for aggregation purposes.
- SAUID_HexGrid_1km_intersect.7z, SAUID_HexGrid_1km_intersect_unclipped.7z
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_1km_{P/T} geometry used for aggregation purposes.
- SAUID_HexGrid_5km_intersect.7z, SAUID_HexGrid_5km_intersect_unclipped.7z
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_5km geometry used for aggregation purposes.
- SAUID_HexGrid_10km_intersect.7z, SAUID_HexGrid_10km_intersect_unclipped.7z
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_10km geometry used for aggregation purposes.
- SAUID_HexGrid_25km_intersect.7z, SAUID_HexGrid_25km_intersect_unclipped.7z
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_25km geometry used for aggregation purposes.
- SAUID_HexGrid_50km_intersect_unclipped.7z
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_50km geometry used for aggregation purposes.
- SAUID_HexGrid_100km_intersect_unclipped.7z
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_100km geometry used for aggregation purposes.
- SAUID_HexGrid_GlobalFabric_intersect.7z
	- Table referencing the settled area id (SAUID) area, and its percentage of area intersect with respect to HexGrid_GlobalFabric geometry used for aggregation purposes.

## hexgrid_900913

Hex grid collection similar to hexgrid_4326 but created in EPSG 900913. Refer to hexgrid_4326 for description.