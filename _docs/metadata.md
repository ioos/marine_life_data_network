---
title: "Metadata Formatting"
keywords: metadata
tags: [biology, metadata]
toc: true
summary: This is Marine Life Data Network (MLDN) metadata recommendations.
---

# Metadata and Documentation

Descriptive metadata and documentation are critical to maintaining data quality. Metadata is “data
about the data” that describes and contextualizes the dataset to ensure it is understandable to
future users. Beyond standardized metadata, useful documentation might include standard operating
procedures, field notes, etc., from which metadata may be derived or referenced.

Throughout the data lifecycle, both the metadata and documentation must be recorded and updated to
reflect the actions taken to the data. This includes collection, acquisition, processing, quality
review, and analysis, as well as any other stage of the data lifecycle.

The dataset’s metadata and/or documentations (or a link to it) must be distributed with the dataset. 

## Metadata

Metadata describes information about a dataset to ensure that it can be understood and re-used
properly in the future. Content of the metadata record includes where the data were collected, who
is responsible for the data, why the data were created, how the data are organized, and any derived
data calculation methods (e.g. for fish abundance estimate) that were used. Metadata generally
follows a standard format to ensure the semantics of metadata fields are understood by creators and
consumers of the metadata, to ease the use of the metadata in catalog and discovery systems, and
simplify automatic machine-to-machine transfer of records.

There are two recomended metadata formats.
1. Ecological Markup Language (EML) - [https://eml.ecoinformatics.org/](https://eml.ecoinformatics.org/)
2. ISO 19115 family of standards - [https://www.fgdc.gov/metadata/iso-standards](https://www.fgdc.gov/metadata/iso-standards)

### EML
The EML project is an open source, community oriented project dedicated to providing a high-quality metadata 
specification for describing data relevant to diverse disciplines that involve observational research like ecology, 
earth, and environmental science. The specification is maintained by voluntary project members who donate their time 
and experience in order to advance information management for ecology. Project decisions are made by consensus of the 
current maintainers on the project.

See this documentation for more information:
Matthew B. Jones, Margaret O’Brien, Bryce Mecum, Carl Boettiger, Mark Schildhauer, Mitchell Maier, Timothy Whiteaker, 
Stevan Earl, Steven Chong. 2019. Ecological Metadata Language version 2.2.0. KNB Data Repository. doi:[10.5063/F11834T2](https://dx.doi.org/10.5063/F11834T2)


### ISO
It is recommended to use the ISO 19115-2 XML for metadata standards following the ISO 19115 guidance from
[NCEI](https://www.ncei.noaa.gov/sites/default/files/2021-03/AB-GUID-02823_R1_Guidance%20for%20The%20NCEI%20Collection%20Level%20Metadata%20Template%20v1.1._0.pdf).
See also [NCEI's guidance on metadata](https://www.ncei.noaa.gov/resources/metadata).

Methods for generating metadata:
* Various software packages exist to create EML metadata. See the list of tools in the [standardizing marine biological 
data guide](https://ioos.github.io/bio_data_guide/tools.html#tools). 
* If data are being served by ERDDAP, then ERDDAP will automatically generate the ISO XML documents.
* If using the [Research Workspace](https://researchworkspace.com/intro/) to submit data, an
integrated metadata editor is included to generate metadata in the FGDC-endorsed ISO 19110 and
19115-2 standards for geospatial metadata. Refer to the
[Metadata Best Practices](https://www.axiomdatascience.com/best-practices/MetadataBestPractices.html#metadata-best-practices)
section for help creating scientific metadata using the Research Workspace metadata editor. This
document provides field-by-field guidance on how to write high-quality metadata.

## Additional Data Documentation

* Save documentation about the data in non-proprietary file formats, such as .txt, .xml, or .pdf.
* Images, pictures, or figures should be saved as JPEG or GIF files.
* The name of the documentation should follow a logical naming convention identical to the related
data file(s), but indicating that the file is a metadata record, e.g. `[data_file_name]_METADATA.xml`.
* For complicated datasets, supplemental documentation is more useful when structured as a user’s
guide for the data. When constructing such a guide, include enough detail for someone with
sufficient domain knowledge to understand, trust, and reuse your data 20+ years in the future.
