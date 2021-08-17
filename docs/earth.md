# Earth science in Julia

> Climate modeling, ecology, cartography, GIS, Meteorology, etc.

**Organizations**

- [Julia space](https://github.com/JuliaSpace)
- [Julia Geo](https://github.com/JuliaGeo)
- [Julia earth](https://github.com/JuliaEarth)
- [EcoJulia](https://ecojulia.org)
- [Julia climate](https://github.com/JuliaClimate)
- [Julia ocean](https://github.com/JuliaOcean)

## Space

- [ReferenceFrameRotations.jl](https://github.com/JuliaSpace/ReferenceFrameRotations.jl) : Functions related to rotations of coordinate frames, angle2dcm, dcm2angle.

## Climatology

[Wikipedia: Climatology](https://en.wikipedia.org/wiki/Category:Climatology)

- [ClimateTools.jl](https://github.com/Balinus/ClimateTools.jl) : This package is a collection of commonly-used tools in Climate Science.
- [INMET.jl](https://github.com/JuliaClimate/INMET.jl) : Julia API to access data from the [Instituto Nacional de Metereologia (INMET)](https://portal.inmet.gov.br/).
- [Mimi.jl](https://github.com/anthofflab/Mimi.jl) : Integrated Assessment Modeling Framework for climate change.

## Ecology

[Wikipedia: Ecology](https://en.wikipedia.org/wiki/Category:Ecology)

- [Diversity.jl](https://github.com/EcoJulia/Diversity.jl) : Diversity analysis package for Julia, with submodules containing standard ecological and other diversity measures.
- [EcologicalNetwork.jl](https://github.com/EcoJulia/EcologicalNetworks.jl) : Measure various aspects of the structure of ecological networks in Julia.
- [FishABM.jl](https://github.com/jangevaare/FishABM.jl) : An agent based life cycle model for managed fisheries. (No `Project.toml`)
- [GBIF.jl](https://github.com/EcoJulia/GBIF.jl) : Functions and types to access GBIF data from Julia.
- [SpatialEcology.jl](https://github.com/EcoJulia/SpatialEcology.jl) : Julia framework for spatial ecology - data types and utilities.

### Agronom and Forest Modelling

- [Wikipedia: Agronomy](https://en.wikipedia.org/wiki/Category:Agronomy)
- [Wikipedia: Forest Modelling](https://en.wikipedia.org/wiki/Category:Forest_modelling)

---

- [LeafAreaIndex.jl](https://github.com/ETC-UA/LeafAreaIndex.jl) : Package to calculate Leaf Area Index from Hemisperical Images. [LAIscript](https://github.com/ETC-UA/LAIscript) : scripts to automatically run Leaf Area Index (LAI) calculations with ODBC link to custom database. Needs `LeafAreaIndex.jl`.

### Aquatic Ecology

- [AIBECS.jl](https://github.com/JuliaOcean/AIBECS.jl) : Algebraic Implicit Biogeochemical Elemental Cycling System (AIBECS) for exploring global marine biogeochemical cycles.
- [OceanRobots.jl](https://github.com/gaelforget/OceanRobots.jl) : simulating data collected by autonomous, remotely operated, or manned vehicles in the Ocean. [JuliaCon 2021 video](https://youtu.be/oC-rikXfVo8)

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [Iceberg.jl](https://github.com/njwilson23/Iceberg.jl) : Ice-seawater interface calculations using level set methods.

</details>

**Resources**

[Modeling Marine Ecosystems At Multiple Scales Using Julia](https://youtu.be/UCIRrXz2ZS0), a workshop @ JuliaCon 2021.

## Cartography

[Wikipedia: Cartography](https://en.wikipedia.org/wiki/Category:Cartography)

- [Proj4.jl](https://github.com/JuliaGeo/Proj4.jl) : Julia wrapper for PROJ.4 cartographic projections library.

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [PyProj.jl](https://github.com/kshramt/PyProj.jl) : A Julia wrapper of [PyProj](https://pypi.python.org/pypi/pyproj), that performs cartographic transformations and geodetic computations.

</details>

## Geographic information system (GIS)

[Wikipedia: GIS](https://en.wikipedia.org/wiki/Geographic_information_system)

- [GDAL.jl](https://github.com/JuliaGeo/GDAL.jl) : Thin Julia wrapper for [GDAL](http://gdal.org/) - Geospatial Data Abstraction Library. See also [ArchGDAL.jl](https://github.com/yeesian/ArchGDAL.jl) for a high level API for `GDAL.jl`.
- [Geodesy.jl](https://github.com/JuliaGeo/Geodesy.jl) : Work with points defined in various coordinate systems.
- [GeographicLibPy.jl](https://github.com/kshramt/GeographicLibPy.jl) : Thin wrapper of [geographiclib](https://pypi.python.org/pypi/geographiclib) Python package.
- [GeoInterface.jl](https://github.com/JuliaGeo/GeoInterface.jl) : A Julia Protocol for Geospatial Data.
- [GeoIP.jl](https://github.com/JuliaWeb/GeoIP.jl) : estimating the geographic location of IP addresses.
- [GeoJSON.jl](https://github.com/JuliaGeo/GeoJSON.jl) : Utilities for working with GeoJSON data in Julia.
- [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) : An extensible framework for high-performance geostatistics in Julia.
- [GMT.jl](https://github.com/joa-quim/GMT.jl) :Julia wrapper for the [Generic Mapping Tools](https://github.com/GenericMappingTools/gmt)(GMT).
- [OpenStreetMap.jl](https://github.com/tedsteiner/OpenStreetMap.jl) : The Julia OpenStreetMap package provides basic functionality for parsing, viewing, and working with OpenStreetMap map data.
- [OpenStreetMapPlotter.jl](https://github.com/juliusgeo/OpenStreetMapPlotter.jl) : Plotting focused library for OpenStreetMap data.
- [OpenStreetMapX.jl](https://github.com/pszufe/OpenStreetMapX.jl) : OpenStreetMap support for Julia 1.0. The package can parse `*.osm` and `*.pbf` (contributed by @blegat) files and generate a LightGraphs representation along the metadata. [JuliaCon2021 tutorial](https://pszufe.github.io/OpenStreetMapX_Tutorial/JuliaCon2021/)
- [OpenStreetMapXPlot.jl](https://github.com/pszufe/OpenStreetMapXPlot.jl) : plotting companion for the `OpenStreetMapX.jl` package.
- [Turf.jl](https://github.com/philoez98/Turf.jl) : A geospatial engine encoding the collections of simple geographical features using the JS lib Turfjs in the GeoJSON format.

---

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [DtPlot.jl](https://github.com/dejakaymac/DtPlot.jl)
- 🏚️ [EarthSphere.jl](https://github.com/cuevasclemente/EarthSphere.jl) : A library for measuring approximate distance and location given latitudes and longitudes.
- 🏚️ [FlowNetworks.jl](https://github.com/scheidan/FlowNetworks.jl) : Types and function to represent hydrological flow networks.
- 🏚️ [GIS.jl](https://github.com/wkearn/GIS.jl) : A package for the visualization and manipulation of geographic data.
- 🏚️ [hillerislambers](https://github.com/wkearn/hillerislambers) : Julia implementation of the HilleRisLambers et al. 2001 model of arid vegetation dynamics.
- 🏚️ [Jultran.jl](https://github.com/jsbj/Jultran.jl) : Julia interface for the HITRAN database of spectral lines, based on Ray Pierrehumbert's PyTran.
- 🏚️ [OpenStreetMap.jl](https://github.com/tedsteiner/OpenStreetMap.jl) : Julia OpenStreetMap Package
- 🏚️ [OpenStreetMapParser.jl](https://github.com/yeesian/OpenStreetMapParser.jl) : This package provides basic functionality for parsing OpenStreetMap data in Julia.
- 🏚️ [Tyndall.jl](https://github.com/jsbj/Tyndall.jl) : Radiative transfer in Julia.
- 🏚️ [Watershed.jl](https://github.com/seung-lab/Watershed.jl) : Julia version of watershed.

</details>

## GPS

- 🏚️ [NMEA.jl](https://github.com/templarlabs/NMEA.jl) : Julia package for parsing GPS NMEA messages.

## Meteorology

[ Wikipedia: Meteorology](https://en.wikipedia.org/wiki/Meteorology)

<details> <summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [CAIRS.jl](https://github.com/scheidan/CAIRS.jl) : Continous Assimilation of Integrating Rain Sensors.
- 🏚️ [Met_Plots_Models.jl](https://github.com/zhujinxuan/Met_Plots_Models.jl) : A simple wrapper of matlibplot for a meteorologist.
- 🏚️ [TTCal.jl](https://github.com/mweastwood/TTCal.jl) : A bandpass calibration routine developed for the [OVRO](https://en.wikipedia.org/wiki/Owens_Valley_Radio_Observatory) LWA.

</details>
