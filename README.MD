SEND -> SNOMED CT MAPPINGS
=======================

**Repository with manual mappings made for the [eTransafe](https://etransafe.eu/) project**

This repository contains manual mappings from [SEND](https://www.cdisc.org/standards/foundational/send)
to [SNOMED CT](https://www.snomed.org/) in order to aid translational drug safety research.

The following SEND code lists have been mapped:

- Laboratory Test Name (C67154)
- Neoplasm Type (C88025)
- Non-Neoplastic Finding Type (C120531)
- Specimen (C77529)

## ABOUT

- All mappings are provided in [SSSOM](https://github.com/mapping-commons/sssom)-like format, with an
  additional `mapping_group` column in order to specify an 'and' relationship between terms of the same mapping_group.
- Initial mappings were made by staff members of the Erasmus Medical Centre Department for Medical Informatics and
  reviewed by other eTransafe consortium members.

### VOCABULARIES USED

**SEND** \
SEND Controlled Terminology as published [here](https://evs.nci.nih.gov/ftp1/CDISC/SEND/) on 2022-09-30

**SNOMED CT** \
SNOMED CT as published through [Athena](https://athena.ohdsi.org/vocabulary/list) and last updated on
28-Jan-2022

### MAPPING PRINCIPLES

**Principles that apply to all mappings:**

- There should not more than _one_ exact one to one mapping for each concept in each direction
- Mappings from the same subject with the same mapping_group constitute an 'and' mapping. Mappings with a different
  mapping_group are considered 'or' mappings
- Prefer a broad mapping for concepts that do not occur in humans, details on the term should be provided in the
  comments

**Each folder contains additional domain specific information about the mappings**

### CONTRIBUTIONS

Contributions welcome, feel free to open an issue or get in touch via other means.

### LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>
<br />
The _mappings_ in this repository are licensed under
a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons
Attribution 4.0 International License</a>.
<br />

"SNOMED" and "SNOMED CT" are registered trademarks of the IHTSDO. Use of SNOMED CT content is subject to the terms and
conditions set forth in the SNOMED CT Affiliate License Agreement. It is the responsibility of those implementing this
product to ensure that they are appropriately licensed. For more information on the license, including how to
register as an Affiliate Licensee, please refer to https://www.snomed.org/snomed-ct/get-snomed-ct or info@snomed.org.
Under the terms of the Affiliate License, use of SNOMED CT in countries that are not IHTSDO Members is subject to
reporting and fee payment obligations.
