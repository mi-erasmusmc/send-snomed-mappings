NEOPLASM TYPE -> SNOMED CT
=======================

**Mappings from the SEND Neoplasm Type code list to SNOMED CT**

### Principles specific to the non-neoplastic finding type mappings

- Prefer first 'morphologic abnormality' concepts followed by 'disorder' concepts, only when there are no suitable terms
  in these classes consider other concept classes.
- Use 'morphologic abnormality' for benign or malignant when required (do not use 'qualifier values')

**Principles that apply to all mappings:**

- There should not more than _one_ exact one to one mapping for each concept in each direction
- Mappings from the same subject with the same mapping_group constitute an 'and' mapping. Mappings with a different
  mapping_group are considered 'or' mappings
- Prefer a broad mapping for concepts that do not occur in humans, details on the term should be provided in the
  comments
