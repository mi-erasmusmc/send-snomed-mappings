NON-NEOPLASTIC FINDING TYPE -> SNOMED CT
=======================

**Repository with manual mappings made for the eTransafe project**

Here you find mappings from the SEND specimen code list to SNOMED CT

At present there are still ~100 unmapped terms, please feel free to contribute mappings

## PRINCIPLES:

### Principles that apply to all mappings

- There should only be not more than one exact one to one mapping for each concept in each direction
- Mappings from the same subject with the same mapping_group constitute an 'and' mapping. Mappings with a different
  mapping_group are considered 'or' mappings
- Prefer a broad mapping for concepts that do not occur in humans, details on the term should be provided in the
  comments

### Principles that for Non-neoplastic finding type mappings

- Prefer first 'morphologic abnormality' concepts followed by 'disorder' concepts, only when there are no suitable terms
  in these classes consider other concept classes

