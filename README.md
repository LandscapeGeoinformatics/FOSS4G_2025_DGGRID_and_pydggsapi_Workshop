# FOSS4G 2025: Hands-on DGGS and OGC DGGS-API with DGGRID and pydggsapi Workshop

https://2025.foss4g.org/program/schedule#event-4337-hands-on-dggs-and-ogc-dggs-api-with-dggrid-and-pydggsapi-workshop

Discrete Global Grid Systems (DGGS) are getting more attention, and with the new OGC API - DGGS standard released, it's a good time for the open-source community to get practical, hands-on experience. This workshop bridges the gap between the theory of DGGS and a working implementation.

We'll show you why DGGS are so useful for integrating and indexing different data sources and spatial data analysis without the usual headache of map projections. Then, we work through a complete, real-world data pipeline using FOSS tools.

## License

<a href="https://landscapegeoinformatics.github.io/FOSS4G_2025_DGGRID_and_pydggsapi_Workshop/">Hands-on DGGS and OGC DGGS-API with DGGRID and pydggsapi Workshop</a> © 2025 by <a href="https://landscape-geoinformatics.ut.ee/">Alexander Kmoch, Wai Tik Chan, Iris Luik, Kajetan Marcin Chrapkiewicz, Evelyn Uuemaa</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

You are free to:

- Share — copy and redistribute the material in any medium or format for any purpose, even commercially.
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.
- The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

- Attribution — You must give appropriate credit , provide a link to the license, and indicate if changes were made . You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Notices:

You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation .

No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.


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