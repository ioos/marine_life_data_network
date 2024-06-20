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
- Share raw data using community accepted services (ERDDAP™) preferably through IOOS Regional Association cyberinfrastructure. 
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

### Questions We Want the MLDN to Answer
- Do we want to build a monolithic assembly center? One DAC to rule them all?
  - We don't necessarily want a singular Data Assembly Center as the needs are vast and the assembly center might never reach the deliverable.
  - A catalog of available datasets may suffice to meet the need to "find all available IOOS Marine Life data".
- Do we want to connect various assembly centers together?
  - The concept of the [Ocean Data Information System (ODIS)](https://odis.org/) and example implementation through the [Ocean InfoHub Project](https://book.oceaninfohub.org/index.html) is appealing as it connects various assebly centers together using technology that most (if not all??) repositories, that IOOS works with, are already implementing.
- What technologies are we looking at?
  - Cloud
    - Cloud storage? PAM, plankton monitoring? Others?
    - Cloud computing? Does MBON/RAs need cloud computing resources?
  - ERDDAP
  - Stand up IOOS/NOAA Integrated publishing toolkit ([IPT](https://www.gbif.org/ipt))? (for control, access to metrics, leverage NOAA as direct stakeholder in OBIS)
    - Can we cost this out?
  - schema.org / Science on schema.org (SOSO)
    - https://schema.org/
    - https://github.com/ESIPFed/science-on-schema.org 
- What data formats are we working with?
  - Darwin Core, Ecological Markup Language (EML), csv, netCDF gridded data (seascapes), images, audio? (PAM)
- Do we need to consider observing methodologies?
  - YES - but what does this question mean exactly?
- What capabilities exist?
- What are we doing now?
- **What do we want to grow up to become?**
  - What might that cost?
- **Who are our stakeholders? What do they need?**
  - MBON
  - ATB
  - Finance and venture capital - data to support evidence-based indicators, biodiversity metrics (which ones?) and decisions
  - GOOS - variables
    - What product is needed here? Eg. OceanOps - not connecting now but OBIS is/planning to be.
  - National plankton database (federated) so we can get to CPR, IFCB, etc info for not just HABs
    - U.S. EcoTaxa?
  - Product hosting and help building products (eg infographics) from obs data
  - FACT
  - ACT
  - OTN Nodes
  - MBARI
  - ONMS
  - N-PAC
  - OBIS/GBIF
  - NCEI
  - OTN
  - MBON Projects
  - RA's
- Where do IOOS' services start/stop? Do we build products or provide standardized data access and other folks develop products on those? What about product hosting?
  - How does this question and the MLDN overall relate to the Ecosystem Change work in the IRA Topic 2 project?
  - Are we simply an education → implementation facility? Teach folks about the standards and where to put data, but we don’t host anything?
  - For example, Foie Gras - state space model (SSM) - is this what we should be investing in?
    - Scientists see cool product but download raw data then reanalyze for the same product.
      - Species Distribution Models
      - SSMs too
  - What about when users pay for a product? 
    - Serving as a match-making service.
- How do we track where data are?
  - This seems particularly important to nail down for metrics/PARR requirements
  - Funding DOIs, ROR identifiers, DOIs generally, what else can we leverage to help make this easier?
    - Keep up to date with ACDO conversations about this because it seemed relevant/on their minds at EDMW


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
- Passive Acoustic Monitoring National Cyberinfrastructure Center (SoundCoop; website in progress)
- [Passive Acoustic Cetacean Monitoring](https://apps-nefsc.fisheries.noaa.gov/pacm/#/) (PACM)

#### Data User Community
- [Bureau of Ocean Energy Management](https://www.boem.gov/) (BOEM)
- [NOAA Climate, Ecosystems, and Fisheries Initiative](https://noaa-psl.github.io/cefi-cookbook/content/intro.html) (CEFI)
- [Regional Wildlife Science Collaborative for Offshore Wind](https://rwsc.org)
- General ocean, ecosystem, and species modeling communities
- Marine resource and sanctuary managers

### Future Directions
- Establishing and maintaining communities of practice relevant to marine life observations
  - Working groups, TDWG, ESIP Clusters
  - Engagement between scientists and data managers
  - Facilitating opportunities for marine life data managers to learn about relevant standards and data management best practices
 
### Related Resources
If you are interested in a particular subset of the Marine Life Data Network, such as ATN or MBON, below you will find links to other helpful resources.
- [IOOS Marine Life Website](https://ioos.noaa.gov/ioos-in-action/marine-life/)
- [ATN Documentation](https://github.com/ioos/ioos-atn-data)
- [MBON Documentation](https://ioos.github.io/mbon-docs/)
- [MBON Data Portal](https://mbon.ioos.us/)
