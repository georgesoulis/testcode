figshare_Dijkstra

The script is made it to run in google collab straight out of the box when having all the inputs.
In case it is needed to be ran locally, python 3 version and above is needed. 
The following packages are installed in google collab %pip install geopandas %pip install rasterio
%pip install shapely %pip insall networkx. 
Which are needed manual installation by the user if not locally available.

Inputs: 
	roads.shp
	rndm10m_pnts.shp
	Farm_point.shp
	Power_plant.shp
	dembuff (this is a raster)

Output files created (after running figshare_dijkstra.ipynb):
	ALLOFPOINTS_withindexes
	initial_road_segments_withpixeldist
	its_adjusted_network (network with all three distance metrics)
	test_route (this is the outcome of Dijkstra routine with three distances)
	sequence