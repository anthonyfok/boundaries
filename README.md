# boundaries
Boundary geometries for model results.  All geometries in this repo are generated in GeoPackage format.

 - Geometry_ADAUID.gpkg
	- Aggregate dissemination area geometry
 - Geometry_CANADA.gpkg
	- Canada outline geometry
 - Geometry_CDUID.gpkg
	 - Census Division geometry
 - Geometry_CSDUID.gpkg
	- Census Subdivision geometry
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
 
  Adapted from Statistics Canada, 2016 Census - Boundary files, 2020. This does not constitute an endorsement by Statistics Canada of this product.

## hexbin_4326

Hexbin geometries generated in various grid spacing sizes.

 - HexGrid_5km.gpkg
 - HexGrid_10km.gpkg
 - HexGrid_25km.gpkg
 - HexGrid_50km.gpkg
 - HexGrid_100km.gpkg
 - SAUID_HexGrid.gpkg
	- Lookup table linking settled areas to all the hexgrid geometries.
- SAUID_HexGrid_5km_intersect.gpkg
	- Table with settled areas intersected on hexgrid 5km with calculated area and area ratios (intersected area / settled area).
- SAUID_HexGrid_10km_intersect.gpkg
	- Table with settled areas intersected on hexgrid 10km with calculated area and area ratios (intersected area / settled area).
- SAUID_HexGrid_25km_intersect.gpkg
	- Table with settled areas intersected on hexgrid 25km with calculated area and area ratios (intersected area / settled area).
- SAUID_HexGrid_50km_intersect.gpkg
	- Table with settled areas intersected on hexgrid 50km with calculated area and area ratios (intersected area / settled area).
- SAUID_HexGrid_100km_intersect.gpkg
	- Table with settled areas intersected on hexgrid 100km with calculated area and area ratios (intersected area / settled area).
