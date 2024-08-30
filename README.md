# Awesome NINA
Curated list of resources and tools used in NINA

# Development
## Tools
- [MITM Proxy](https://mitmproxy.org/) - a proxy service that can intercept request/response between different containers, useful to debug
- [DBeaver](https://dbeaver.io/) - a GUI software that allows to connect to lot's of different databases (available on Firmaportalen)
- [Nix](https://nixos.org/) - a CLI that allows to install different software without the need of administrator rights
- [Bruno](https://www.usebruno.com/) - A FOSS postman alternative, all requests are saved on your filesystem and can be saved in git
- [DuckDB](https://duckdb.org/) - A swiss-army knife for reading and manipuling data from different sources (Postgres, CSV, Excel, SQLServer, JSON, etc..), also has spatial support built-in


# GIS
## Tools
- [GDAL](https://gdal.org) - GDAL is a translator library for raster and vector geospatial data formats
- [TiPG](https://github.com/developmentseed/tipg) - OGC Features and Tiles from PG database
- [PyGEOAPI](https://docs.pygeoapi.io/en/stable/) -  provides an API to geospatial data.
- [Terracotta](https://github.com/DHI-GRAS/terracotta) - A light-weight, versatile XYZ tile server, built with Flask and Rasterio 🌍
- [TiTiler](https://devseed.com/titiler/) is a set of python modules that focus on creating FastAPI application for dynamic tiling.
- [Martin](https://github.com/maplibre/martin) - Blazing fast and lightweight PostGIS, MBtiles and PMtiles tile server, tile generation, and mbtiles tooling.

## Vectors
- [PMTiles](https://docs.protomaps.com/pmtiles/) - PMTiles is a single-file archive format for pyramids of tiled data. A PMTiles archive can be hosted on a storage platform like S3, and enables low-cost, zero-maintenance map applications.

## Raster

### Cloud Optimized GEOTiff
[A Cloud Optimized GeoTIFF (COG)](https://www.cogeo.org/) is a regular GeoTIFF file, aimed at being hosted on a HTTP file server, with an internal organization that enables more efficient workflows on the cloud. It does this by leveraging the ability of clients issuing ​HTTP GET range requests to ask for just the parts of a file they need.

- [geotiff.js](https://geotiffjs.github.io/) is a small library to parse TIFF files for visualization or analysis including Cloud Optimized GeoTIFFs. It is written in pure JavaScript, and is usable in both the browser and node.js applications.
- [TiTiler](https://devseed.com/titiler/) is a set of python modules that focus on creating FastAPI application for dynamic tiling.
- [https://github.com/developmentseed/mosaicjson-spec](https://github.com/developmentseed/mosaicjson-spec)
- [https://github.com/GeoTIFF/geotiff-palette](https://github.com/GeoTIFF/geotiff-palette)
- [COGServer](https://github.com/rouault/cogserver) Expose any GDAL recognized raster file as a HTTP accessible on-the-fly COG

#### Articles
- [https://medium.com/@_VincentS_/do-you-really-want-people-using-your-data-ec94cd94dc3f](https://medium.com/@_VincentS_/do-you-really-want-people-using-your-data-ec94cd94dc3f) - In this post we will focus on Cloud Optimized GeoTIFF and other formats used by public dataset (AWS pds, Digitalglobe Opendata, …).
- [COG Mosaic JSON](https://medium.com/devseed/cog-talk-part-2-mosaics-bbbf474e66df)
- [https://medium.com/devseed/cog-talk-part-1-whats-new-941facbcd3d1](https://medium.com/devseed/cog-talk-part-1-whats-new-941facbcd3d1)

## OGC API REST

### OGC Features
- [Mapblibre OGC features](https://github.com/opengeospatial/ogcapi-features/blob/master/implementations/clients/mapbox-gl-js.md)



## Metadata
- [PyCSW](https://pycsw.org/)
- [PyGeoMeta](https://github.com/geopython/pygeometa)

## MapLibre
MapLibre GL JS is an open-source library for publishing maps on your websites or webview based apps. Fast displaying of maps is possible thanks to **GPU-accelerated vector tile rendering**.
- [Spec](https://maplibre.org/maplibre-style-spec/)
- [Maplibre COG](https://github.com/NINAnor/maplibre-gl-cog)
- [Maplibre style editor](https://maplibre.org/maputnik)

# ML

## Data Annotation

- [LabelStudio](https://labelstud.io/): Open source annotation software for all types of data and tasks.

## Object detection

- [Pytorch Wildlife](https://github.com/microsoft/CameraTraps/blob/main/megadetector.md): model weights for detection of wild animals in camera trap pictures.
- [Detectron2](https://github.com/facebookresearch/detectron2): Library providing SOTA models for object detection, segmentation algorithms. Maintained by Meta.

## Acoustic 

- [BEATs](https://github.com/microsoft/unilm/tree/master/beats): Model weights for SOTA acoustic classifier. There was a tensor shape error that was fixed [here](https://github.com/NINAnor/rare_species_detections)

## Utils libraries

- [Audiomentation](https://github.com/iver56/audiomentations): Provide lots of utilitary functions for audio data augmentation. Alternative to [torchaudio](https://pytorch.org/audio/stable/index.html).
