# Data Management Plan

## Introduction

## Data description and collection or re-use of existing data

### How will new data be collected or produced and/or how will existing data be re-used?

New data will be collected into two Google Sheet files, one for describing the objects and the other for describing the process of their digitization. Data provenance will be documented as well.

Data will be gleaned from at least two analog sources:
* the library's inventory book
* a published paper catalogue of selected works

### What data (for example the kind, formats, and volumes), will be collected or produced?

Data will be both textual (such as the poster's metadata) and images (the digitized versions of the posters themselves).

The digitization process will be carried out by using at most two types of devices, namely:
* scanner
* camera

In both cases, data will be stored in both RAW, TIFF (after processing) and PNG (for publishing) formats.

Images volume:
* RAW: ...
* TIFF: ...
* PNG: ...

Metadata volume:
* Object: ...
* Process: ...

## Documentation and data quality

### What metadata and documentation (for example the methodology of data collection and way of organising data) will accompany the data?

Object:
* id
* title
* people and role involved
* dimensions (with measurement units and types)
* date of creation
* keywords
* license
* language

Process:
* type of activity
* people and institutions involved
* input
* output
* time-span
* location
* techniques used
* tools used

The metadata schema that will be used is [CHAD-AP](https://w3id.org/dharc/ontology/chad-ap), a OWL-encoded application profile based on widely used standards such as CIDOC-CRM, LRMoo, CRMdig and AAT.

This information will be captured in both the tabular datasets and in the RDF generated from them, as well as in a dedicated text file.

### What data quality control measures will be used?

Tabular data quality will be controlled and documented via Python scripts and/or OpenRefine.

RDF data quality will be checked via SHACL.

## Storage and backup during the research process

### How will data and metadata be stored and backed up during the research?

Tabular data will be stored in the Google Sheet tables, on a local drive in CSV format, and on Sharepoint in CSV format.

RDF data will be store on a local drive and on Sharepoint.

Images will be stored on two local drives and on Sharepoint.

### How will data security and protection of sensitive data be taken care of during the research?

Access to tabular data, RDF data and images will be controlled and allowed only to the project's members.

## Legal and ethical requirements, codes of conduct

### How will other legal issues, such as intellectual property rights and ownership, be managed? What legislation is applicable?

Data owner: ...

License on metadata: CC0

License on images: ...

## Data sharing and long-term preservation

### How and when will data be shared? Are there possible restrictions to data sharing or embargo reasons?

Metadata (both in tabular and graph forms) will be published on a data repository such as Zenodo. Each will be given its own DOI and citation.

### How will data for preservation be selected, and where data will be preserved long-term (for example a data repository or archive)?

Where data will be deposited: ...

### What methods or software tools are needed to access and use data?

Data will be made accessible through a CMS that allows for user-friendly interactions for non experts, as well as communication with an API layer for more sophisticated, programmatic access.

## Data management responsibilities and resources

### Who (for example role, position, and institution) will be responsible for data management (i.e. the data steward)?

Roles and responsibilities: ...

### What resources (for example financial and time) will be dedicated to data management and ensuring that data will be FAIR (Findable, Accessible, Interoperable, Re-usable)?

Time and financial resources: ...