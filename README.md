# Marine Life Data Network Vision
## *This document is in development.*

### Intent of this document
The intent of this document is to clearly identify what IOOS' vision is for a Marine Life Data Network’s DMAC capability/infrastructure so we can effectively communicate with IOOS partners and start to build out “the network”. This document will lay out IOOS’ current data network architecture and where IOOS would like the network to be in the next five years.

### Vision
To serve as the aggregator of marine life observations and data needed for a range of applications for conservation, sustainable development, management, climate response, environmental monitoring, and modeling. These observations will also feed into standardized data products, like OBIS and GBIF, which contribute to the development of indicators.

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

### IOOS Core Variables related to biology ([notebook](https://colab.research.google.com/drive/1BOgOMjYhw0ISif9A3kZ6YRVQexiLLSH5?usp=sharing))
- sea_bird_abundance_and_distribution
- dissolved_nutrients
- sea_turtle_abundance_and_distribution
- invertebrate_abundance_and_distribution
- ocean_sound
- optical_properties
- total_suspended_matter
- phytoplankton_biomass_and_diversity
- zooplankton_biomass_and_diversity
- acidity
- mangrove_cover_and_composition
- cdom
- pco2
- dissolved_oxygen
- microbe_biomass_and_diversity
- hard_coral_cover_and_composition
- marine_mammal_abundance_and_distribution
- seagrass_cover_and_composition
- contaminants
- fish_abundance_and_diversity
- macroalgal_canopy_cover_and_composition
- pathogens
- ocean_color

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
 
### Questions To Answer
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
- IOOS DMAC
- IOOS Advisory Committee

### Future Directions
- Establishing and maintaining communities of practice relevant to marine life observations
  - Working groups, TDWG, Cluster
  - Engagement between scientists and data managers
