# Awesome Building Science [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, libraries, datasets, and resources for building performance simulation and urban environmental analysis.

Legend: 🆓 open source / free · 💲 commercial

## Contents

- [Platforms & Workflows](#platforms--workflows)
- [Climate & Weather Data](#climate--weather-data)
- [Wind & CFD](#wind--cfd)
- [Solar & Daylight](#solar--daylight)
- [Building Energy](#building-energy)
- [Thermal Comfort & Urban Heat](#thermal-comfort--urban-heat)
- [Ventilation & Air Quality](#ventilation--air-quality)
- [Envelope & Hygrothermal](#envelope--hygrothermal)
- [Noise & Acoustics](#noise--acoustics)
- [Mobility & Transportation](#mobility--transportation)
- [Fire & Smoke](#fire--smoke)
- [Water & Flooding](#water--flooding)
- [Embodied Carbon & LCA](#embodied-carbon--lca)
- [Renewables](#renewables)
- [Urban Data & Geometry](#urban-data--geometry)
- [BIM & Interoperability](#bim--interoperability)
- [Controls, Metadata & Digital Twins](#controls-metadata--digital-twins)
- [Datasets](#datasets)
- [Standards & Rating Systems](#standards--rating-systems)
- [Learning Resources](#learning-resources)
- [Communities](#communities)
- [Related Lists](#related-lists)

## Platforms & Workflows

- [Ladybug Tools](https://www.ladybug.tools/) 🆓 - Grasshopper/Python plugins for climate, daylight, energy, comfort, and CFD analysis ([GitHub](https://github.com/ladybug-tools)).
- [ClimateStudio](https://www.solemma.com/climatestudio) 💲 - Rhino plugin for daylight, glare, energy, and thermal comfort.
- [Pollination](https://www.pollination.solutions/) 💲 - Cloud platform built on Ladybug Tools for large simulation jobs.

## Climate & Weather Data

- [Climate.OneBuilding.org](https://climate.onebuilding.org/) 🆓 - Largest free collection of EPW/TMY weather files.
- [EPWMap](https://www.ladybug.tools/epwmap/) 🆓 - Map interface for finding EPW files.
- [CBE Clima Tool](https://clima.cbe.berkeley.edu/) 🆓 - Web app for climate analysis from EPW files.
- [NSRDB](https://nsrdb.nlr.gov/) 🆓 - NLR (formerly NREL) National Solar Radiation Database.
- [ERA5 / Copernicus CDS](https://cds.climate.copernicus.eu/) 🆓 - Global hourly reanalysis data.
- [Meteonorm](https://meteonorm.com/) 💲 - Synthetic weather files, including future climate scenarios.
- [Global Wind Atlas](https://globalwindatlas.info/) 🆓 - High-resolution global wind resource maps.

## Wind & CFD

- [OpenFOAM](https://www.openfoam.com/) 🆓 - Open-source CFD toolbox; backbone of most open wind workflows.
- [Eddy3D](https://www.eddy3d.com/) 🆓 - Grasshopper plugin for outdoor wind and microclimate simulation using OpenFOAM.
- [Butterfly](https://github.com/ladybug-tools/butterfly) 🆓 - Ladybug Tools plugin for OpenFOAM.
- [PALM](https://palm.muk.uni-hannover.de/) 🆓 - LES model for atmospheric and urban boundary layer flows.
- [WRF](https://github.com/wrf-model/WRF) 🆓 - Mesoscale numerical weather prediction model.
- [Infrared.city](https://infrared.city/) 💲 - ML-based fast urban wind and comfort prediction.
- [SimScale](https://www.simscale.com/) 💲 - Cloud CFD for pedestrian wind comfort.

## Solar & Daylight

- [Radiance](https://www.radiance-online.org/) 🆓 - Validated physically based lighting simulation engine ([GitHub](https://github.com/LBNL-ETA/Radiance)).
- [Accelerad](https://nljones.github.io/Accelerad/) 🆓 - GPU-accelerated Radiance.
- [honeybee-radiance](https://github.com/ladybug-tools/honeybee-radiance) 🆓 - Python library for Radiance-based daylight modeling.
- [frads](https://github.com/LBNL-ETA/frads) 🆓 - Python framework for Radiance matrix-based simulation.
- [Daysim](https://github.com/MITSustainableDesignLab/Daysim) 🆓 - Climate-based daylight modeling.
- [VELUX Daylight Visualizer](https://www.velux.com/what-we-do/digital-tools/daylight-visualizer) 🆓 - Daylight simulation for designers.

## Building Energy

- [EnergyPlus](https://energyplus.net/) 🆓 - DOE whole-building energy simulation engine ([GitHub](https://github.com/NREL/EnergyPlus)).
- [OpenStudio](https://openstudio.net/) 🆓 - SDK and GUI around EnergyPlus ([GitHub](https://github.com/NREL/OpenStudio)).
- [eppy](https://github.com/santoshphilip/eppy) 🆓 - Python scripting for EnergyPlus IDF files.
- [Modelica Buildings Library](https://github.com/lbl-srg/modelica-buildings) 🆓 - Equation-based HVAC and controls modeling.
- [URBANopt](https://github.com/urbanopt) 🆓 - District-scale energy modeling SDK.
- [CityBES](https://citybes.lbl.gov/) 🆓 - City-scale building energy analysis platform.
- [ResStock](https://resstock.nlr.gov/) / [ComStock](https://comstock.nlr.gov/) 🆓 - US building stock energy models.
- [BOPTEST](https://github.com/ibpsa/project1-boptest) 🆓 - Benchmarking framework for building control algorithms.
- [TRNSYS](https://www.trnsys.com/) 💲 - Transient system simulation.
- [IDA ICE](https://www.equa.se/en/ida-ice) 💲 - Whole-building simulation.
- [DesignBuilder](https://designbuilder.co.uk/) 💲 - EnergyPlus GUI.

## Thermal Comfort & Urban Heat

- [pythermalcomfort](https://github.com/CenterForTheBuiltEnvironment/pythermalcomfort) 🆓 - Python package for PMV, SET, UTCI, adaptive comfort and more.
- [CBE Thermal Comfort Tool](https://comfort.cbe.berkeley.edu/) 🆓 - Web tool for ASHRAE 55 / ISO 7730 / EN 16798 compliance.
- [UMEP](https://umep-docs.readthedocs.io/) 🆓 - Urban Multi-scale Environmental Predictor for QGIS (includes SOLWEIG).
- [Urban Weather Generator](https://github.com/ladybug-tools/uwg) 🆓 - Morphs rural EPW files to account for urban heat island.
- [ENVI-met](https://www.envi-met.com/) 💲 - 3D microclimate model.

## Ventilation & Air Quality

- [CONTAM](https://www.nist.gov/el/energy-and-environment-division-73200/nist-multizone-modeling) 🆓 - NIST multizone airflow and contaminant transport.
- [OpenAQ](https://openaq.org/) 🆓 - Open global outdoor air quality measurements.

## Envelope & Hygrothermal

- [THERM](https://windows.lbl.gov/therm-software-downloads) / [WINDOW](https://windows.lbl.gov/software-tools) 🆓 - LBNL 2D heat transfer and window performance.
- [WUFI](https://wufi.de/) 💲 - Hygrothermal (heat and moisture) simulation.
- [DELPHIN](https://bauklimatik-dresden.de/en/software/delphin) 💲 - Coupled heat, air, moisture, and salt transport.

## Noise & Acoustics

- [NoiseModelling](https://github.com/Universite-Gustave-Eiffel/NoiseModelling) 🆓 - Environmental noise maps (CNOSSOS-EU) in GIS.
- [I-Simpa](https://github.com/Universite-Gustave-Eiffel/I-Simpa) 🆓 - 3D room and urban acoustic propagation.
- [Pachyderm Acoustic](https://github.com/PachydermAcoustic) 🆓 - Acoustic simulation for Rhino/Grasshopper.
- [pyroomacoustics](https://github.com/LCAV/pyroomacoustics) 🆓 - Python room acoustics simulation.
- [ODEON](https://odeon.dk/) 💲 - Room acoustics.
- [CadnaA](https://www.datakustik.com/products/cadnaa/) 💲 - Environmental noise prediction.

## Mobility & Transportation

- [SUMO](https://eclipse.dev/sumo/) 🆓 - Microscopic traffic simulation ([GitHub](https://github.com/eclipse-sumo/sumo)).
- [MATSim](https://www.matsim.org/) 🆓 - Agent-based transport simulation.
- [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner) 🆓 - Multimodal trip planning.
- [R5](https://github.com/conveyal/r5) 🆓 - Rapid multimodal routing for accessibility analysis.
- [OSMnx](https://github.com/gboeing/osmnx) 🆓 - Street network retrieval and analysis from OpenStreetMap.
- [Pandana](https://github.com/UDST/pandana) 🆓 - Fast network accessibility queries.
- [UrbanSim](https://github.com/UDST/urbansim) 🆓 - Land use and urban development modeling.
- [Urbano](https://urbano.io/) 🆓 - Grasshopper toolkit for mobility and amenity-based urban design.

## Fire & Smoke

- [FDS / Smokeview](https://github.com/firemodels/fds) 🆓 - NIST Fire Dynamics Simulator.
- [Pathfinder](https://www.thunderheadeng.com/pathfinder) 💲 - Agent-based egress simulation.

## Water & Flooding

- [SWMM](https://www.epa.gov/water-research/storm-water-management-model-swmm) 🆓 - EPA Storm Water Management Model.
- [PySWMM](https://github.com/pyswmm/pyswmm) 🆓 - Python interface to SWMM.

## Embodied Carbon & LCA

- [EC3](https://www.buildingtransparency.org/) 🆓 - Embodied Carbon in Construction Calculator.
- [openLCA](https://www.openlca.org/) 🆓 - Open-source life cycle assessment.
- [One Click LCA](https://www.oneclicklca.com/) 💲 - Building LCA and EPD platform.

## Renewables

- [pvlib-python](https://github.com/pvlib/pvlib-python) 🆓 - Photovoltaic performance modeling.
- [SAM](https://sam.nlr.gov/) 🆓 - NLR (formerly NREL) System Advisor Model for renewable energy systems.

## Urban Data & Geometry

- [OpenStreetMap](https://www.openstreetmap.org/) 🆓 - Crowd-sourced map data.
- [Overture Maps](https://overturemaps.org/) 🆓 - Open global map data incl. building footprints.
- [Global ML Building Footprints](https://github.com/microsoft/GlobalMLBuildingFootprints) 🆓 - Microsoft building footprints.
- [Google Open Buildings](https://sites.research.google/open-buildings/) 🆓 - Building footprints for Africa, Asia, Latin America.
- [3D BAG](https://3dbag.nl/) 🆓 - LoD2 3D buildings for the Netherlands.
- [PLATEAU](https://www.mlit.go.jp/plateau/) 🆓 - 3D city models of Japan.

## BIM & Interoperability

- [IfcOpenShell](https://github.com/IfcOpenShell/IfcOpenShell) 🆓 - IFC toolkit and geometry engine.
- [gbXML](https://www.gbxml.org/) 🆓 - Green Building XML schema for energy model exchange.
- [Speckle](https://speckle.systems/) 🆓 - Open data exchange across AEC tools.

## Controls, Metadata & Digital Twins

- [Brick Schema](https://brickschema.org/) 🆓 - Ontology for building systems metadata.
- [Project Haystack](https://project-haystack.org/) 🆓 - Tagging standard for building equipment data.

## Datasets

- [Building Data Genome 2](https://github.com/buds-lab/building-data-genome-project-2) 🆓 - Hourly meter data from 1,600+ non-residential buildings.
- [CBECS](https://www.eia.gov/consumption/commercial/) / [RECS](https://www.eia.gov/consumption/residential/) 🆓 - US commercial and residential energy surveys.
- [ASHRAE Global Thermal Comfort Database II](https://github.com/CenterForTheBuiltEnvironment/ashrae-db-II) 🆓 - Field thermal comfort observations.

## Standards & Rating Systems

- ASHRAE 55 (thermal comfort), 62.1 (ventilation), 90.1 (energy), 140 (simulation validation).
- ISO 7730 (thermal comfort), EN 16798 (indoor environment), EN 17037 (daylight).
- IES LM-83 (sDA / ASE daylight metrics).
- [LEED](https://www.usgbc.org/leed), [WELL](https://www.wellcertified.com/), [Passive House](https://passivehouse.com/), [BREEAM](https://bregroup.com/products/breeam).

## Learning Resources

- [Building Science Corporation](https://buildingscience.com/) - Articles and digests on envelope and moisture.
- [IBPSA](https://ibpsa.org/) - International Building Performance Simulation Association; conference proceedings.

## Communities

- [Unmet Hours](https://unmethours.com/) - Q&A for building energy modeling.
- [Ladybug Tools Forum](https://discourse.ladybug.tools/)
- [Radiance Discourse](https://discourse.radiance-online.org/)
- [CFD Online](https://www.cfd-online.com/)

## Related Lists

- [Awesome AECO](https://github.com/osama-ata/Awesome-AECO) - Open-source architecture, engineering, construction, and operations tools.
- [Awesome BIM](https://github.com/mitevpi/awesome-bim) - BIM development resources.
- [Awesome Urban Datasets](https://github.com/urban-toolkit/awesome-urban-datasets) - Open urban datasets (sunlight, noise, mobility, flooding).
- [Awesome Energy Models](https://github.com/rebase-energy/awesome-energy-models) - Python-based energy system models.
- [Awesome GIS](https://github.com/sshuair/awesome-gis) - Geospatial tools and data.
- [Awesome Climate Data](https://github.com/DaveParr/awesome-climate-data) - Climate data sources and libraries.
- [Awesome Transportation Network Data](https://github.com/chkwon/awesome-transportation-network-data) - Transport network datasets.

## Contributing

Contributions welcome. Open a PR adding an entry in the format `- [Name](link) 🆓/💲 - Short description.`
