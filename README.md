# nhs-cancer-registrations
Numbers of new cases, and rates per 100,000 population for the following types of cancer:

* malignant neoplasms (excluding non melanoma skin cancer).
* lung cancer, including cancers of the trachea and bronchus
* malignant female breast tumours
* colorectal cancers, constituting cancers of the colon, rectum and rectosigmoid junction
* malignant prostate tumours

Note that some information may have been suppressed or adjusted to preserve patient confidentiality. Cancer registration is a dynamic process: the incidence data presented here may differ from other published data relating to the same time period. Source: Scottish Cancer Registry (SMR06). For further information see ISD's Cancer Website


Statistics provided by NHS Information Services Division:  http://statistics.gov.scot/data/cancer-registrations

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nhs-cancer-registrations.git
```

Install npm dependencies

```
cd nhs-cancer-registrations
npm install
```

Run the API (from the nhs-cancer-registrations directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
