SEND TO SNOMED CT MAPPINGS
=======================

**Repository with manual mappings made for the [eTransafe](https://etransafe.eu/) project**

This repository contains manual mappings from [SEND](https://www.cdisc.org/standards/foundational/send)
to [SNOMED CT](https://www.snomed.org/) in order to aid translational drug safety research.

The following SEND code lists have been mapped:

- Specimen (C77529)
- Non-Neoplastic Finding Type (C120531)
- Neoplasm Type (C88025) (expected here January 2023)
- Laboratory Test Name (C67154) (expected here January 2023)

## ABOUT:

- All mappings are provided in [SSSOM](https://github.com/mapping-commons/sssom)-like format, with an
  additional `mapping_group` column
- Initial mappings were made by staff members of the Erasmus Medical Centre Department for Medical Informatics and
  reviewed by other eTransafe consortium members.

### VOCABULARIES

For the mappings we have used:

**SEND** \
SEND Controlled Terminology as published [here](https://evs.nci.nih.gov/ftp1/CDISC/SEND/) on 2022-09-30

**SNOMED CT** \
SNOMED CT as published through [Athena](https://athena.ohdsi.org/vocabulary/list) and last updated on
28-Jan-2022

### MAPPING PRINCIPLES:

**Principles that apply to all mappings:**

- There should not more than _one_ exact one to one mapping for each concept in each direction
- Mappings from the same subject with the same mapping_group constitute an 'and' mapping. Mappings with a different
  mapping_group are considered 'or' mappings
- Prefer a broad mapping for concepts that do not occur in humans, details on the term should be provided in the
  comments
- *Each folder contains additional domain specific information about the mappings*

### CONTRIBUTIONS:

Contributions welcome, feel free to open an issue or get in touch via other means.

### LICENSE:

The mappings in this repository are licensed under
a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons
Attribution 4.0 International License</a>.<br /> \
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />
