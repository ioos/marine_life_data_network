# Marine Life Data Network Vision
## *This document is in development.*

### Intent of this document
The intent of this document is to clearly identify IOOS' vision for a Marine Life Data Network (MLDN) data management and cyberinfrastructure so we can effectively communicate with IOOS partners and start to build out the network. This document will lay out IOOS’ current data network architecture and where IOOS would like the MLDN to be in the next five years.

### Vision
To serve as the aggregator of marine life observations for the IOOS data enterprise and to provide data and products for a range of applications for conservation, sustainable development, management, climate response, environmental monitoring, and modeling. These observations will also feed into standardized data products, like the Ocean Biodiversity Information System ([OBIS](https://obis.org)) and the Global Biodiversity Information Facility ([GBIF](https://www.gbif.org)), which serve the broader scientific community and contribute to the development of biological and ecosystem indicators.

### Definition
Marine life observations are any observations of, or proxies for, life in aquatic environments.

Observational methods include but are not limited to:
- Acoustic and satellite telemetry
- Passive and active acoustic monitoring
- Imaging Flow Cytobots (IFCBs)
- Image and video analyses
- Environmental DNA (eDNA)
- Net tows
- Bottle samples
- Quadrat surveys

For a list of commonly used acronyms you may come across in this repository, please see the [glossary](https://github.com/ioos/marine_life_data_network/blob/main/glossary.md).

### [Essential Ocean Variables for Biology and Ecology](https://goosocean.org/what-we-do/framework/essential-ocean-variables/)
- Phytoplankton biomass/diversity
- Zooplankton biomass/diversity
- Fish abundance/distribution
- Sea turtle abundance/distribution
- Sea bird abundance/distribution
- Marine mammal abundance/distribution
- Hard coral cover and composition
- Seagrass cover and composition
- Macroalgal canopy cover and composition
- Mangrove cover and composition
- Ocean sound (cross-disciplinary)
- Ocean color (cross-disciplinary)
- Microbe biomass/diversity (pilot)
- Invertebrate abundance/distribution (pilot)

### Goals and Requirements
- Provide an inventory of Marine Life data collected by the IOOS enterprise.
- Ensure marine life observations align with the FAIR principles.
- Data are made available ASAP.
- Serve as a national aggregator of marine life observations.
- Leverage existing resources for the management of marine life observations.
- Ensure observations make it to Global Ocean Observing System.
- Ensure data are available for integration into national products (IOOS data catalog, infographics, etc.)
- Provides standardized web services.
- Implements schema.org (connection to ODIS/OIH?)
- Support long term archive at NOAA's National Centers for Environmental Information (NCEI).
- Provide guidance to IOOS network on data management of marine life observations
- Promote open source software and open source community engagement.
- Occurrence data are available in OBIS/GBIF.

### Current Implementation
- Share raw data using community accepted services (ERDDAP) preferably through IOOS Regional Association cyberinfrastructure. 
- Align species occurrence data to the Darwin Core standard and share with OBIS-USA.
- Share planned/current sampling activities on GOOS BioEco portal.
- Long term archival at NOAA’s NCEI.
- Leverage work from NCEI, AOML, USGS, OBIS, GBIF
- Data flow diagrams:
  - Tabular data - https://github.com/ioos/mbon-docs/issues/40
  - eDNA - https://github.com/ioos/mbon-docs/issues/6
  - Passive acoustic monitoring - https://github.com/ioos/mbon-docs/issues/41
  - Acoustic tag tracking data - https://github.com/ioos/ioos-atn-data/issues/77
  - ATN satellite telemetry - https://github.com/ioos/ioos-atn-data/issues/27 
  - HABs
  - IFCB
  - Corals/high level data flow - https://iooc.us/sites/default/files/2022-12/BioIce_Introduction_Final.pdf

### Purposes of this Repository
This repository is multipurpose. It provides a place for documentation, long term planning, task tracking, and user stories for the IOOS Marine Life Data Network in a transparent manner to encourage community participation and collaboration.

If you have questions about this repository, the Animal Telemetry Network (ATN), or Marine Biodiversity Observation Network (MBON) that are not answered here in the readme or in the contributing guide, you can send an email to us.mbon@noaa.gov or atndac@listserver.mbari.org.
 
### How to Contribute
If you would like to contribute to the IOOS Marine Life Data Network, please see the [contributing guide](https://github.com/ioos/marine_life_data_network/blob/main/contributing.md).
 
### Questions We Want the MLDN to Answer
- Do we want to build a monolithic assembly center? One DAC to rule them all?
- Do we want to connect various assembly centers together?
- What technologies are we looking at?
- What data formats are we working with?
- Do we need to consider observing methodologies?
- What capabilities exist?
- What are we doing now?
- What do we want to grow up to become?
- What might that cost?
- Who are our stakeholders? What do they need?
- Where do IOOS' services stop? Do we build products or provide standardized data access and other folks develop products on those?
- Are we simply an education → implementation facility? Teach folks about the standards and where to put data, but we don’t host anything?
- How do we track where data are?

### Who?
#### IOOS Team
- IOOS DMAC
- IOOS Advisory Committee

#### Data Providers and Generators
- [IOOS Regional Associations](https://ioos.noaa.gov/about/regional-associations/)
- [Marine Biodiversity Observation Network](https://marinebon.org)
- [Animal Telemetry Network](https://atn.ioos.us)
- [National Harmful Algal Bloom Observing Network](https://ioosassociation.org/nhabon/) (NHABON)
- [SanctSound](https://sanctsound.ioos.us)
- SoundCoop (website in progress)
- [Passive Acoustic Cetacean Monitoring](https://apps-nefsc.fisheries.noaa.gov/pacm/#/) (PACM)

#### Data User Community
- [Bureau of Ocean Energy Management](https://www.boem.gov/)
- [NOAA Climate, Ecosystems, and Fisheries Initiative](https://noaa-psl.github.io/cefi-cookbook/content/intro.html)
- [Regional Wildlife Science Collaborative for Offshore Wind](https://rwsc.org)
- General ocean, ecosystem, and species modeling communities

### Future Directions
- Establishing and maintaining communities of practice relevant to marine life observations
  - Working groups, TDWG, Cluster
  - Engagement between scientists and data managers
 
### Related Resources
If you are interested in a particular subset of the Marine Life Data Network, such as ATN or MBON, below you will find links to other helpful resources.
- [IOOS Marine Life Website](https://ioos.noaa.gov/ioos-in-action/marine-life/)
- [ATN Documentation](https://github.com/ioos/ioos-atn-data)
- [MBON Documentation](https://ioos.github.io/mbon-docs/)
- [MBON Data Portal](https://mbon.ioos.us/)
