# Brunel Centre Data Hub – Open Data Downloads

This repository provides downloadable datasets used in the Brunel Centre Data Hub for the South West of England and selected local authority areas.  
The datasets support tables, charts, and visualisations published on the Data Hub website.

Data are made available to support transparency, reuse, and reproducibility. They are organised by sector and topic and are provided primarily as Excel workbooks.

---

## Geography coverage

The Data Hub uses a constructed geography referred to as the **Greater West of England**.  
This geography consists of the following local authority areas:

- Bath and North East Somerset  
- Bristol, City of  
- North Somerset  
- South Gloucestershire  
- Gloucestershire  
- Swindon  
- Wiltshire  

Where data are presented for the Greater West of England, local authority data have been aggregated.  
Details of included areas are provided in the metadata for each dataset.

England excluding London, selected combined authority areas, or UK-level geographies are used as comparators for some datasets, depending on availability.

---

## Sectors covered

Datasets in this repository are grouped under the following sectors:

- Labour Market  
- Economy  
- Population  
- Poverty and Deprivation  
- Health  
- Environment  
- Transport  
- Housing and Land Use 

Each sector contains topic-level folders and individual datasets linked to specific Data Hub outputs.

---

## Dataset structure and formats

Each dataset is provided as a single Excel workbook and corresponds to one visualisation published on the Data Hub website.

Where a blog contains multiple visualisations, each visualisation is supported by a separate dataset.

### Excel file contents

Each Excel file contains **two or three worksheets**, depending on the source data.

#### 1. `analysis_data`
This sheet contains the data used directly in the published chart or table.  
It includes any filtering, re-formatting, or aggregation required to reproduce the visualisation.

#### 2. `metadata`
This sheet provides descriptive and quality information for the dataset, including:
- publisher and source organisation  
- source dataset and publication  
- date of extraction  
- geography and time coverage  
- definitions and units  
- details of any aggregation to constructed geographies  
- known caveats or limitations  

#### 3. `raw_data` (where applicable)
For some datasets, a `raw_data` sheet is included.  
This contains the original downloaded data (for example, from Nomis) prior to analysis.

Where raw data are not included, the metadata sheet provides a link to the original source dataset.

---


## Data sources

Datasets are primarily derived from publicly available official statistics, including data published by UK government departments and public bodies such as the Office for National Statistics.

---

## Data quality and caveats

Some datasets are based on survey data or management information and are therefore subject to sampling variability or differences in data coverage between areas.

Quality considerations, including small population counts, missing information, or known limitations of the source data, are documented in the metadata for each dataset.

---

## Updates and version control

Datasets are updated in line with Data Hub releases.  
Major updates are recorded in `CHANGELOG.md`.

File and folder names are kept stable where possible to support direct linking from the Data Hub website.

---

## How to download data

- **Single dataset**  
  Open the relevant dataset folder and download the Excel workbook.

- **All datasets**  
  Select **Code** and choose **Download ZIP** to download the full repository.

- **Reproducible access**  
  Clone the repository using Git:

```bash
git clone https://github.com/thebrunelcentre/datahub-data.git
```

## Licensing and reuse

Unless otherwise stated, datasets are shared under the same licence terms as the original source data.

Many datasets are published under the Open Government Licence (OGL).
Users must comply with the licence conditions of the original data producers.

Further information is provided in LICENCE.md.


## Contact

For questions about the datasets or the Data Hub, please visit the Brunel Centre website or contact the Data Hub team.
