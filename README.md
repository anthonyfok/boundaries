# boundaries
Boundary geometries for model results.  All geometries in this repo are generated in Geopackage format.

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
	
#### / Reference
 - Reference_SAUID_points.gpkg
		 - Settled area points generated from the settled area polygons used to create the lookup table.  The point is the centroid of the settled area polygons if it is within the polygon extents.  If not the point is a random generated point within the settled area polygon.
