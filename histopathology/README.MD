NON-NEOPLASTIC FINDING TYPE -> SNOMED CT
=======================

**Mappings from the eTox Histopathology Ontology to SNOMED CT**

At present there are still ~500 unmapped terms, please feel free to contribute mappings

### Principles specific to the non-neoplastic finding type mappings

- Prefer first 'morphologic abnormality' concepts followed by 'disorder' concepts, only when there are no suitable terms
  in these classes consider other concept classes

**Principles that apply to all mappings:**

- There should not more than _one_ exact one to one mapping for each concept in each direction
- Mappings from the same subject with the same mapping_group constitute an 'and' mapping. Mappings with a different
  mapping_group are considered 'or' mappings
- Prefer a broad mapping for concepts that do not occur in humans, details on the term should be provided in the
  comments
