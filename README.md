# Awesome GIS NINA
Curated list of resources and tools for GIS

# Tools
- [GDAL](https://gdal.org) - GDAL is a translator library for raster and vector geospatial data formats
- [TiPG](https://github.com/developmentseed/tipg) - OGC Features and Tiles from PG database
- [PyGEOAPI](https://docs.pygeoapi.io/en/stable/)

# Vectors
- [PMTiles](https://docs.protomaps.com/pmtiles/) - PMTiles is a single-file archive format for pyramids of tiled data. A PMTiles archive can be hosted on a storage platform like S3, and enables low-cost, zero-maintenance map applications.

# Raster

## Cloud Optimized GEOTiff
[A Cloud Optimized GeoTIFF (COG)](https://www.cogeo.org/) is a regular GeoTIFF file, aimed at being hosted on a HTTP file server, with an internal organization that enables more efficient workflows on the cloud. It does this by leveraging the ability of clients issuing ​HTTP GET range requests to ask for just the parts of a file they need.

- [geotiff.js](https://geotiffjs.github.io/) is a small library to parse TIFF files for visualization or analysis including Cloud Optimized GeoTIFFs. It is written in pure JavaScript, and is usable in both the browser and node.js applications.
- [TiTiler](https://devseed.com/titiler/) is a set of python modules that focus on creating FastAPI application for dynamic tiling.
- [https://github.com/developmentseed/mosaicjson-spec](https://github.com/developmentseed/mosaicjson-spec)
- [https://github.com/GeoTIFF/geotiff-palette](https://github.com/GeoTIFF/geotiff-palette)

### Articles
- [https://medium.com/@_VincentS_/do-you-really-want-people-using-your-data-ec94cd94dc3f](https://medium.com/@_VincentS_/do-you-really-want-people-using-your-data-ec94cd94dc3f) - In this post we will focus on Cloud Optimized GeoTIFF and other formats used by public dataset (AWS pds, Digitalglobe Opendata, …).
- [COG Mosaic JSON](https://medium.com/devseed/cog-talk-part-2-mosaics-bbbf474e66df)
- [https://medium.com/devseed/cog-talk-part-1-whats-new-941facbcd3d1](https://medium.com/devseed/cog-talk-part-1-whats-new-941facbcd3d1)

# OGC API REST

## OGC Features
- [Mapblibre OGC features](https://github.com/opengeospatial/ogcapi-features/blob/master/implementations/clients/mapbox-gl-js.md)



# Metadata
- [PyCSW](https://pycsw.org/)
- [PyGeoMeta](https://github.com/geopython/pygeometa)

# MapLibre
- [Spec](https://maplibre.org/maplibre-style-spec/)
- [Maplibre COG](https://github.com/NINAnor/maplibre-gl-cog)
