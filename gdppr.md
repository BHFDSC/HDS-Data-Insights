## GDPPR - General Practice Extraction Service (GPES) Data for Pandemic Planning and Research

### Description
GDPPR = General Practice Extraction Service (GPES) Data for Pandemic Planning and Research. This dataset is an extract/subset from primary care (GP) systems - designed to address the urgent need for GP data in response to Covid-19 planning & research. The dataset does not contain all information held in primary care systems (e.g., registration, long-term conditions, etc.) but rather it looks to meet the needs of a particular data use case. The data is in a long format, with one patient having many records for even a single GP appointment, and each record describing one patient date-code combination.

### Links
NHS Digital - https://digital.nhs.uk/coronavirus/gpes-data-for-pandemic-planning-and-research/guide-for-analysts-and-users-of-the-data
Health Data Research Innovation Gateway - https://web.www.healthdatagateway.org/dataset/696cfc9f-090d-4328-94ac-140760a77c73

### Table names
db.table
db.table

### Data Summary Notebook
Workspaces\path

### Need to Know

- Includes patients:
  - alive on or after 1 November 2019
  - from participating practices in England (98%)
  - with SNOMED-CT codes relevant to pandemic planning and research
- Includes SNOMED-CT codes deemed applicable for COVID-19 research (~X out of X) 
- Data coverage varies according to SNOMED-CT code cluster 
- GDPPR includes ~61m individuals, GP list size estimates ~62m individuals, ONS population estimates ~57m 
- No registration data available 
- Individuals and records are not removed from the extract in monthly batch updates 
- Patients who have opted out (X) are not removed; data no longer flows from the point of opt out
- Not possible to reliably infer number of GP appointments/consultations
- Small number of SNOMED-CT codes in GDPPR not matching to the GDPPR reference set


### Dataset Notes

#### Inclusion Criteria

The GDPPR extract only includes patients with active, current registrations at participating practices (98%) and deceased patients with a date of death on or after 1 November 2019.

https://digital.nhs.uk/coronavirus/gpes-data-for-pandemic-planning-and-research/guide-for-analysts-and-users-of-the-data#patient-inclusion-exclusion

#### Code Cluster

The GDPPR extract only includes a subset of the available SNOMED-CT codes i.e., those included in the GDPPR cluster reference set that were deemed applicable for COVID-19 research. The reference table listing the available codes can be downloaded from the link below and is also available in the dss_corporate workspace (with prefix “gpdata_snomed”) within the TRE.

https://digital.nhs.uk/coronavirus/gpes-data-for-pandemic-planning-and-research/guide-for-analysts-and-users-of-the-data#code-clusters-and-content

https://digital.nhs.uk/binaries/content/assets/website-assets/coronavirus/gpes-data-for-planning-and-research/gdppr_cluster_refset_1000230_20211221.zip

Further details around which codes have been included are provided in “Supplementary Table 7: Summary of codes included in the primary care dataset” of the BMJ paper.

https://www.bmj.com/content/373/bmj.n826


ETC

[Previous page](/index.md) | [Next page](hes_apc.md)

#### [Home](./index.md) 
