---
title: "How-to guide for MLDN metadata"
keywords: metadata
toc: true
tags: [metadata, eml]
summary: This is a how-to guide for collecting MLDN metadata.
---
The information below can also be viewed as a Microsoft Word document [here](https://github.com/ioos/marine_life_data_network/raw/gh-pages/assets/EML.Metadata.Template.docx).

# EML Metadata
<mark>Highlighted elements are required</mark> 
<br/>
<br/>
**<mark>Dataset shortname (will be the URL in the IPT, all lower case, no spaces):</mark>** <br/>
**<mark>Title:</mark>** <br/>
**Update Frequency (pick one):** Daily, Weekly, Monthly, Biannually, Annually, As Needed, Continually, Irregular, Not Planned, Unknown, Other Maintenance Period <br/>
**<mark>Data License (pick one):</mark>** CC-0, CC-BY, CC-BY-NC <br/>
**<mark>Description / Abstract:</mark>** <br/>
**<mark>Resource Contacts (include First Name, Last Name, Position, Organization, Email, can link to ORCID):</mark>** <br/>
**<mark>Resource Creators (include First Name, Last Name, Position, Organization, Email, can link to ORCID):</mark>** <br/>
**<mark>Metadata Providers (include First Name, Last Name, Position, Organization, Email, can link to ORCID):</mark>** <br/>

## Geographic Coverage
**Set global coverage: YES or NO (if NO rest is required)** <br/>
**Description:** <br/>
**West (decimal degrees):** <br/>
**East (decimal degrees):** <br/>
**South (decimal degrees):** <br/>
**North (decimal degrees):** <br/>

## Taxonomic Coverage
**Description:** <br/>
Scientific Name, Common Name, Taxon Rank for all species or at higher level if all part of one higher level rank

## Temporal Coverage
**Temporal Coverage Type (can select more than one but corresponding information must align with the type):** Single Date, Formation Period, Date Range, Living Time Period <br/>

## Keywords
**Thesaurus / Vocabulary:** <br/>
**Keyword List:** <br/>

## Associated Parties

**Associated Party (include First Name, Last Name, Position, Organization, Email, can link to ORCID):** <br/>
**Associated Party Role (pick one per person from table below):** <br/>
_`Role` information is also available at <https://ipt.gbif.org/manual/en/ipt/latest/manage-resources#associated-parties>._

| **Role**              | **Description**                                                                                                                                                                                           
|:----------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| author                | an agent who is an author of a publication that used the dataset, or author of a data paper                                                                                                           
| contentProvider       | an agent who contributed content to a dataset (the dataset being described may be a composite)                                                                                                        
| custodianSteward      | an agent who is responsible for/takes care of the dataset                                                                                                                                             
| distributor           | an agent involved in the publishing/distribution chain of a dataset                                                                                                                                   
| editor                | an agent associated with editing a publication that used the dataset, or a data paper                                                                                                                 
| metadataProvider      | an agent responsible for providing the metadata                                                                                                                                                       
| originator            | an agent who originally gathered/prepared the dataset                                                                                                                                                 
| owner                 | an agent who owns the dataset (may or may not be the custodian)                                                                                                                                       
| pointOfContact        | an agent to contact for further information about the dataset                                                                                                                                         
| principalInvestigator | a primary scientific contact associated with the dataset                                                                                                                                              
| processor             | an agent responsible for any post-collection processing of the dataset                                                                                                                                
| publisher             | the agent associated with the publishing of some entity (paper, article, book, etc) based on the dataset, or of a data paper                                                                          
| user                  | an agent that makes use of the dataset                                                                                                                                                                
| programmer            | an agent providing informatics/programming support related to the dataset                                                                                                                             
| curator               | an agent that maintains and documents the specimens in a collection. Some of their duties include preparing and labeling specimens so they are ready for identification, and protecting the specimens 
| reviewer              | person assigned to review the dataset and verify its data and/or metadata quality. This role is analogous to the role played by peer reviewers in the scholarly publication process.                  

_Note: Stephen Formel will be listed as the `publisher` if she loads the data into the IPT for you and publishes to GBIF and/or OBIS._

_Note: Mathew Biddle will be listed as the `distributor` with `US MBON` as the institution._

***For IOOS Regional Associations*** <br/>
All IOOS Regional Association affiliated datasets should include at least one **Associated Party** which lists the proper RA. The RA names must appear the same as they are listed in OceanExpert. This allows the dataset to show up on the Regional Association’s institutional dashboard. The metrics for your dataset will be tracked on this dashboard.

*Alaska Ocean Observing System* <br/>
OceanExpert: <br/>
OBIS Institute: <br/>

*Caribbean Coastal Ocean Observing System* <br/>
OceanExpert: <https://oceanexpert.org/institution/16063> <br/>
OBIS Institute: <https://obis.org/institute/16063> <br/>

*Central & Northern California Ocean Observing System* <br/>
OceanExpert: <https://oceanexpert.org/institution/23204> <br/>
OBIS Institute: <https://obis.org/institute/23204> <br/>

*Gulf of Mexico Coastal Ocean Observing System* <br/>
OceanExpert: <https://oceanexpert.org/institution/18936> <br/>
OBIS Institute: <https://obis.org/institute/18936> <br/>

*Mid-Atlantic Coastal Ocean Observing System* <br/>
OceanExpert: <br/>
OBIS Institute: <br/>

*Northeastern Regional Association of Coastal Ocean Observing Systems* <br/>
OceanExpert: <https://oceanexpert.org/institution/18301> <br/>
OBIS Institute: <https://obis.org/institute/18301> <br/>

*Northwest Association of Networked Ocean Observing Systems* <br/>
OceanExpert: <br/>
OBIS Institute: <br/>

*Pacific Islands Ocean Observing System* <br/>
OceanExpert: <https://oceanexpert.org/institution/20188> <br/>
OBIS Institute: <https://obis.org/institute/20188> <br/>

*Southern California Coastal Ocean Observing System* <br/>
OceanExpert: <br/>
OBIS Institute: <br/>

*Southeast Coastal Ocean Observing System* <br/>
OceanExpert: <https://oceanexpert.org/institution/20875> <br/>
OBIS Institute: <https://obis.org/institute/20875> <br/>

***For MBON*** <br/>
All `US MBON` affiliated datasets should include at least one **Associated Party** which is affiliated with `US MBON`. This allows the dataset to show up on the `US MBON` institutional dashboard. The metrics for your dataset will be tracked on this dashboard. This is possible because `US MBON` has an OceanExpert institute which links the various datasets together on the institute page.

*United States Marine Biodiversity Observation Network* <br/>
OceanExpert: <https://oceanexpert.org/institution/23070> <br/>
OBIS Institute: <https://obis.org/institute/23070> <br/>

***Appendices*** <br/>
_To create an **OceanExpert** institution, follow the 
[Appendix: How-to Create an OceanExpert Institution](#appendix-how-to-create-an-oceanexpert-institution)._

_NOAA and IOOS DMAC encourage the use of **Research Organization Registry** identifiers for organizations and institutions. See the [Appendix: More Information on ROR Identifiers](#appendix-more-information-on-ror-identifiers)._

## Project Data
_If including this section Title and Project Personnel are required_

**Title:** <br/>
**Identifier** <br/>
**Description:** <br/>
**Funding:** <br/>
**Study Area Description:** <br/>
**Design Description:** <br/>
**Project Personnel (First Name, Last Name, Role):** <br/>

***For MBON*** <br/>
Use this statement for **Funding:** This work was supported by the U.S. Marine Biodiversity Observation Network (MBON) co-organized by NOAA, NASA, BOEM, and ONR through the National Oceanographic Partnership Program (NOPP) [(add AGENCY grant # here if required/preferred)].

## Sampling Methods
_If including this section Study Extent, Sampling Description, Step Description are required)_

**Study Extent:** <br/>
**Sampling Description:** <br/>
**Quality Control:** <br/>
**Step Description:** <br/>

## Citations
**<mark>Resource Citation (can be autogenerated):</mark>** <br/>
**Resource Citation Identifier:** <br/>
**Bibliographic Citations:** <br/>

## Collection Data
**Collections:** <br/>
**Specimen Preservation Methods:** <br/>
**Curatorial Units:** <br/>

## External Links
**Resource Homepage:** <br/>
**Other Data Formats (Name, Character Set, Download URL, Data Format, Data Format Version):** <br/>

## Additional Metadata
**Resource Logo URL (or file upload):** <br/>
**Purpose:** <br/>
**Maintenance Description:** <br/>
**Additional Information:** <br/>
**Alternative Identifiers:** <br/>

## Appendix: How to create an OceanExpert institution

Before creating a new institution it's always good to first do a search to make sure your institution doesn't already 
exist in **OceanExpert**. You can search for institutions at <https://oceanexpert.org/advancedSearch>. Be sure to check 
various spellings and acronyms too!

To create an **OceanExpert** institution:
1. Create an **OceanExpert** account: <https://oceanexpert.org/register>
2. Once your account is created, log in and edit your profile:<br> 
![image](https://user-images.githubusercontent.com/8480023/207622140-89c3bbb5-1abd-4058-809b-8434635bfa54.png)
3. In the **Affiliation and Address** section of the profile there is a dropdown menu for `Organisation/Institution/Company`, select the first option `Cannot find my Institute - Create New`: <br>
![image](https://user-images.githubusercontent.com/8480023/207622420-52592ce2-bda7-4ba4-a40a-47417ca6bca7.png)
4. A new window will pop up and ask you to populate a new institution record:<br> 
![image](https://user-images.githubusercontent.com/8480023/207622801-e395e6af-dd61-4247-a865-b5a86dcaf787.png)
   1. The only required fields are: `Name`, `Type` (choose from Academic, Government, International / Intergovernmental, NGO, Private Commercial, Private non-profit, and Research), `Address`, `Zip Code`, and `City`.
5. Click **Add Institution**.
6. That should add the institution to the drop down list for `Organisation/Institution/Company` so that you can associate it with your profile.

To edit **OceanExpert** institution pages, send an email to <mailto:info@oceanexpert.org> with the requested changes.

## Appendix: More information on ROR identifiers
NOAA and IOOS DMAC encourage the use of [Research Organization Registry](https://ror.org/) (ROR) identifiers for institutions, but the current implementation of OBIS uses OceanExpert to create the institute dashboard. For more information about ROR identifiers and IOOS recommendations, see the [August 2024 DMAC tech webinar recording](https://youtu.be/P1WzR0twg_U). The documentation here regarding institution identifiers will be updated with new guidance when advances are made in linking RORs to OceanExpert identifiers and if RORs are implemented in other relevant repositories for IOOS marine life data.
