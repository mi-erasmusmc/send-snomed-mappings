SPECIMEN -> SNOMED CT
=======================

**Mappings from the SEND Specimen code list to SNOMED CT**

### Principles specific to the specimen mappings

- When mapping towards anatomic parts only map towards SNOMED CT 'structure' concepts, do not map to 'part' and 'entire'
- If specimen does not refer to a part of the body prefer 'Substance' before other classes
- Do not use 'combined site' (CS) concepts, as these are not well integrated into the SNOMED.

**Principles that apply to all mappings:**

- There should not more than _one_ exact one to one mapping for each concept in each direction
- Mappings from the same subject with the same mapping_group constitute an 'and' mapping. Mappings with a different
  mapping_group are considered 'or' mappings
- Prefer a broad mapping for concepts that do not occur in humans, details on the term should be provided in the
  comments

