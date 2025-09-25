READ ME file for sargassum_econ_paper
2025-09-24
Allison Bailey
allison@soundgis.com


gee_sargassum_classify_econ_paper.py is the script that uses Google Earth Engine (GEE) to classify Sentinel-2 images to create presence/absence rasters of Sargassum.

The script requires two feature classes that are not part of the GEE data catalog.  These inputs are provided in the data subfolder and need to be imported into the users GEE assets.
	S2_sargassum_mask.shp
	samples_S2toa_20190507_allbands.shp


The lc_code values refer to the following:
	0 = sargassum
	1 = other vegetation
	2 = beach
	3 = buildings / roads
	4 = clouds


