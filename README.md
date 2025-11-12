# FOSS4G 2025: Hands-on DGGS and OGC DGGS-API with DGGRID and pydggsapi Workshop

https://2025.foss4g.org/program/schedule#event-4337-hands-on-dggs-and-ogc-dggs-api-with-dggrid-and-pydggsapi-workshop

Discrete Global Grid Systems (DGGS) are getting more attention, and with the new OGC API - DGGS standard released, it's a good time for the open-source community to get practical, hands-on experience. This workshop bridges the gap between the theory of DGGS and a working implementation.

We'll show you why DGGS are so useful for integrating and indexing different data sources and spatial data analysis without the usual headache of map projections. Then, we work through a complete, real-world data pipeline using FOSS tools.

## In this workshop, you will

- take a standard geospatial file (like a GeoTIFF or GeoPackage).
- use the command-line tool DGGRID (https://github.com/sahrk/DGGRID | https://dggrid.readthedocs.io/latest/ ), generate grids and index this data onto a hexagonal grid
- we will introduce hierarchical indexing for ISEA3H and ISEA7H with the new Z3 and Z7 indexing systems in DGGRID
- in the decond part, we set up and configure pydggsapi (https://github.com/LandscapeGeoinformatics/pydggsapi/ | https://pydggsapi.readthedocs.io/en/latest/), an open-source Python server that implements the newly (to be) released OGC API - DGGS standard.

- we then point pydggsapi at the data you just created and launch the service
- we explore several ways how to interact with your new web service using a browser, or curl/Python notebook, and maybe even QGIS, to make queries and retrieve data.

### Who should attend?

This workshop is for developers, data managers, and generally DGGS and geospatial enthusiasts who want to learn how to publish their data using this new paradigm.

## Prerequisites

Participants should be comfortable with the command line and have a basic understanding of what geospatial raster and vector data are. We can use Docker or plain Miniconda/Micromamba/Pixi Python environments to ensure the dependencies are easy to set up for everyone. Bring your laptop (Win, Mac, Linux, *BSD might all work).

By the end, you will understand the concepts of DGGS-indexed data and will have built a functioning DGGS-based web service yourself.