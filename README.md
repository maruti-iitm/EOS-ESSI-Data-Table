# Current status of ESI:
Current Status: Remote sensing in-combination of field and ancillary data has transformed the development of the Earth system model (ESM). Satellite remote sensing data has a long and rich history from aerial imagery of the early nineteenth century [Necsoiu, 2013] to the present-day’s Google Earth Engine (GEE) [Gorellic, 2013] and Unmanned Aerial Vehicles (UAV) [Singh and Frazier, 2018]. Vast repositories of satellite data like Landsat, environment data for monitoring the earth’s surface, and high resolution Sentinel data are made FREE and OPEN by USGS, NOAA, and Copernicus open hub respectively to the public to facilitate research and development. Thus, the current state-of-the-art remote sensing provides an edge over the traditional methods for monitoring natural resources and disasters. The transformation from desktop analysis to cloud computing increased transparency, reduced costs, enhanced global to local scale analysis.

State-of-the-art satellite remote sensing data has been INTEGRATED with GIS across disciplines like agriculture, forestry, urban etc., with ancillary data like knowledge/literature-based and ground observations of features on the Earth’s surface to protect the natural resources, mitigate disasters and forecast natural calamities. The quest for high resolution and accurate information has escalated the demand for sensors like Sentinel and Planet labs [Ammani et al., 2021], which produces data in the order of the Terabyte scale. Contemporary developments in data science packages (e.g., TensorFlow, PyTorch) and containerization (e.g., docker) facilitated interoperability and allowed us to analyze this Terabyte scale sensor data.

# Global forest watch and Open Street Map:

Global Forest Watch was developed based on the capabilities of GEE. The introduction of interactive, user-friendly interfaces with various informatics tools has empowered people to analyze data on the fly and derive results about the trees which are present and absent in near real-time. The algorithm applied for works both offline and online. Forest watcher App is an interface that links satellite surveillance to footsteps on the ground helping to detect illegal activities within the forests. Thus, a COORDINATED effort increases our understanding of locating destruction. Another example of COORDINATION can be seen by the volunteers who work on the ground and help mapping vulnerable communities and places. Various tools on the OSM which is OPEN and FREE assist in this effort. According to FAIR principles, this team is committed to bringing its relevance to the real world by solving social, health, and emergency issues. In this effort, volunteers worldwide collaborate and focus from regional-scale to local-scale, providing open-source apps and community mapping to address Sustainable Development Goals.

# A table that summarizes the FAIR data sources, infrastructure, and informatics tools for the EOS article
In this Github link, we provide a table that summarizes `FAIR (Findable, Accessible, Interoperable, and Reusable)` data repositories. 
This table is for Earth and Space Science Informatics EOS-article. 
To summarize, high-quality data is needed to develop accurate, reliable, and fast Earth system models (ESM). 
This information encompasses field, experimental, space, and metadata sets collected from various campaigns across the world. 
The collected data is standardized, stored, and made open-source for Earth and space science communities. 
Below, summarizes popular and FAIR data sources for the development of ESM models. 
The field and metadata are then processed and ingested into the ESM models using a coupled modeling-experimental (ModEx) approach.

| **Data sources, infrastructure, and informatics tools** | **Description of the resource (Field/Experimental/Remotely sensed)** | **Resource links** |
| :-----------------------------------------------------: | :-----------------------------: | :----------------: |
| AmeriFlux Network  | AmeriFlux Network provides long-term carbon, water, and energy flux measurements and site metadata within Americas.  | https://ameriflux.lbl.gov/  |
|Atmospheric Radiation Measurement (ARM) User Facility  | The ARM User Facility provides in situ and remote sensing observatories designed to improve the understanding and representation in climate and Earth system models, clouds and aerosols, and interactions and coupling with the Earth’s surface.  | https://www.arm.gov  |
| The National Ecological Observatory Network (NEON)  | NEON provides ecological data based on continental-scale research instruments.  | https://www.neonscience.org/  |
| Surface Atmosphere Integrated Field Laboratory (SAIL)  | SAIL provides integrated atmosphere-to-bedrock observational data. This data is used to characterize key physical processes that impact mountain hydrology across scales.  | https://sail.lbl.gov/  |
| The ECOsystem Spaceborne Thermal Radiometer Experiment on Space Station (ECOSTRESS)  | ECOSTRESS provides data related to plant stress by accurately measuring the temperature of plants.  | https://ecostress.jpl.nasa.gov/  |
| Geoscience Data Acquisition for Western Nevada (GeoDAWN)  | GeoDAWN provides airborne geophysical and LIDAR survey data on undiscovered geothermal, critical minerals, and groundwater resources in Nevada and California.  | https://www.usgs.gov/media/images/geodawn-geoscience-data-acquisition-western-nevada  |
| SPAtially Referenced Regressions On Watershed attributes (SPARROW)  | SPARROW provides data on streamflow, Nitrogen, Phosphorus, and suspended sediment loads in all watershed in the USA.  | https://www.usgs.gov/mission-areas/water-resources/science/sparrow-mappers?qt-science_center_objects=0#qt-science_center_objects  |
| Next Generation Ecosystem Experiment – Arctic (NGEE-Arctic)  | NGEE-Arctic provides data on permafrost ecology and carbon cycle dynamics in high-latitude terrestrial ecosystems.  | https://ngee.ornl.gov/  |
| Next Generation Ecosystem Experiment – Tropics (NGEE-Tropics)  | NGEE-Tropics provides data on tropical forest ecosystems.  | https://ngee-tropics.lbl.gov/  |
| Spruce and Peatland Responses Under Changing Environments (SPRUCE)  | SPRUCE provides data on the peatland ecosystems to disturbances such as temperature and elevated atmospheric CO<sub>2</sub> concentrations.  | https://mnspruce.ornl.gov/  |
| Fine-Root Ecology Database (FRED)  | FRED provides data on root traits across the globe on fine-root processes.  | https://roots.ornl.gov  |
| KBase  | KBase is a data analytics platform that provides tools to predict and design biological function from the biomolecular scale to the ecological scale.  | https://www.kbase.us/  |
| Mercury Aqueous Speciation Database (AQUA-MER)  | AQUA-MER provides data to investigate mercury speciation in specific defined environments.  | https://aquamer.ornl.gov  |
| Catchment Attributes and Meteorology for Large-sample Studies (CAMELS)  | CAMELS provides data on the hydrometeorological time series and the catchment attributes for 671 basins in the US.  | https://ral.ucar.edu/solutions/products/camels  |
| Environmental Systems Science Data Infrastructure for a Virtual Ecosystem (ESS-DIVE)  | ESS-DIVE is a data repository for Earth and environmental science data on terrestrial and subsurface ecosystems.  | https://ess-dive.lbl.gov/  |
| Worldwide Hydrobiogeochemical Observation Network for Dynamic River Systems (WHONDRS)  | WHONDRS provide data that aims to understand to understand coupled hydrologic, biogeochemical, and microbial function within river corridors.  | https://www.pnnl.gov/projects/WHONDRS  |
| Pangeo  | Pangeo is a community platform for Big data geoscience to promote open, reproducible, and scalable science.  | https://pangeo.io/  |
| Geothermal Data Repository (GDR)  | GDR provides data collected and synthesized on geothermal systems.  | https://gdr.openei.org/  |
| OpenEI  | OpenEI provide energy data, information, analyses, tools, and maps for policymakers and researchers.  | https://openei.org/wiki/Main_Page  |
| Energy Data eXchange (EDX)  | EDX provides a platform to acquire, preserve, and synthesize energy data products, data, and tools  | https://edx.netl.doe.gov/  |
|   | NASA Direct Readout Laboratory (DRL).  | https://directreadout.sci.gsfc.nasa.gov/  |
|   | NASA's Land, Atmosphere Near real-time Capability for EOS (LANCE).  | https://lance.modaps.eosdis.nasa.gov/  |
|   | NASA RapidScat Portal.  | https://www.nasa.gov/rapidscat/  |
|   | NOAA Physical Oceanographic Real-Time System (PORTS®).  | https://tidesandcurrents.noaa.gov/ports_info.html  |
|   | NOAA's Near Real-Time Altimeter Validation System (NRTAVS).  | https://www.star.nesdis.noaa.gov/socd/lsa/NearRealTime/NRT_NRTAVS.php  |
| Open-source  satellite imagery, data products, visualization, and informatics tools from Europe (e.g., Copernicus) and USA (e.g, NASA, NOAA, USGA, US EPA, USDA)  | USGS EROS Center.  |  https://www.usgs.gov/centers/eros |
|   | U.S. EPA AIRNow Program.  | https://www.airnow.gov/  |
|   | USDA/NASA Global Reservoirs and Lakes Monitor (G-REALM) system.  | https://ipad.fas.usda.gov/cropexplorer/global_reservoir/  |
|   | ESA Copernicus Open Access Hub.  | https://scihub.copernicus.eu/  |
|   | Copernicus Atmosphere Monitoring Service (CAMS).  | https://atmosphere.copernicus.eu/  |
|   | Copernicus Atmosphere Data Store.  | https://ads.atmosphere.copernicus.eu/#!/home  |
|   | Datasets from European Centre for Medium-Range Weather Forecasts (ECMWF).  | https://www.ecmwf.int/ <br /> https://apps.ecmwf.int/datasets/  |
|   | NASA Worldview.  |  https://worldview.earthdata.nasa.gov/ |
|   | NASA's Fire Information for Resource Management System (FIRMS).  |  https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms |
| Well-known data tools to view satellite images and create visualizations of data products, thus providing information in real-time or near real-time to support disasters and emergency management  | NASA Disasters Mapping Portal.  |  https://maps.disasters.nasa.gov/ |
|   | USGS FarEarth Observer.  | https://earthnow.usgs.gov/observer/ <br /> https://live.farearth.com/ |
|   | USGS Hazards Data Distribution System (HDDS) Explorer.  | https://hddsexplorer.usgs.gov/ |
|   | USGS Collection Management Tool (CMT).  |  https://cmt.usgs.gov/ |
