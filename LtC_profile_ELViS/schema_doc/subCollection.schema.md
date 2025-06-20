# ELViS Latimer Core Schema (subCollection)

- [1. The following properties are required](#autogenerated_heading_2)
- [2. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectGroup`](#ltc:hasObjectGroup)
  - [2.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectGroup > ObjectGroup`](#ltc:hasObjectGroup_ObjectGroup)
- [3. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification`](#ltc:hasObjectClassification)
  - [3.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 0`](#ltc:hasObjectClassification_allOf_i0)
    - [3.1.1. If (isTopParent = true)](#autogenerated_heading_3)
      - [3.1.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 0 > then > ltc:objectClassificationLevel`](#ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationLevel)
      - [3.1.1.2. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 0 > then > ltc:objectClassificationName`](#ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationName)
  - [3.2. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 1`](#ltc:hasObjectClassification_allOf_i1)
    - [3.2.1. If (ltc:isTopParent = false)](#autogenerated_heading_4)
      - [3.2.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 1 > then > ltc:objectClassificationLevel`](#ltc:hasObjectClassification_allOf_i1_then_ltc:objectClassificationLevel)
  - [3.3. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 2`](#ltc:hasObjectClassification_allOf_i2)
    - [3.3.1. If (ltc:hasParentOrganisationalUnit = "Anthropology")](#autogenerated_heading_5)
      - [3.3.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 2 > then > ltc:objectClassificationName`](#ltc:hasObjectClassification_allOf_i2_then_ltc:objectClassificationName)
  - [3.4. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 3`](#ltc:hasObjectClassification_allOf_i3)
    - [3.4.1. If (ltc:hasParentOrganisationalUnit = "Botany")](#autogenerated_heading_6)
      - [3.4.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 3 > then > ltc:objectClassificationName`](#ltc:hasObjectClassification_allOf_i3_then_ltc:objectClassificationName)
  - [3.5. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 4`](#ltc:hasObjectClassification_allOf_i4)
    - [3.5.1. If (ltc:hasParentOrganisationalUnit = "Zoology")](#autogenerated_heading_7)
      - [3.5.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 4 > then > ltc:objectClassificationName`](#ltc:hasObjectClassification_allOf_i4_then_ltc:objectClassificationName)
  - [3.6. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 5`](#ltc:hasObjectClassification_allOf_i5)
    - [3.6.1. If (ltc:hasParentOrganisationalUnit = "Microbiology")](#autogenerated_heading_8)
      - [3.6.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 5 > then > ltc:objectClassificationName`](#ltc:hasObjectClassification_allOf_i5_then_ltc:objectClassificationName)
  - [3.7. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 6`](#ltc:hasObjectClassification_allOf_i6)
    - [3.7.1. If (ltc:hasParentOrganisationalUnit = "Palaeontology")](#autogenerated_heading_9)
      - [3.7.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 6 > then > ltc:objectClassificationName`](#ltc:hasObjectClassification_allOf_i6_then_ltc:objectClassificationName)
  - [3.8. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 7`](#ltc:hasObjectClassification_allOf_i7)
    - [3.8.1. If (ltc:hasParentOrganisationalUnit = "Earth-Geology")](#autogenerated_heading_10)
      - [3.8.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 7 > then > ltc:objectClassificationName`](#ltc:hasObjectClassification_allOf_i7_then_ltc:objectClassificationName)
  - [3.9. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 8`](#ltc:hasObjectClassification_allOf_i8)
    - [3.9.1. If (ltc:hasParentOrganisationalUnit = "Astrogeology")](#autogenerated_heading_11)
      - [3.9.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 8 > then > objectClassificationName`](#ltc:hasObjectClassification_allOf_i8_then_objectClassificationName)
  - [3.10. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 9`](#ltc:hasObjectClassification_allOf_i9)
    - [3.10.1. If (ltc:hasParentOrganisationalUnit = "Ecology")](#autogenerated_heading_12)
      - [3.10.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 9 > then > ltc:objectClassificationName`](#ltc:hasObjectClassification_allOf_i9_then_ltc:objectClassificationName)
  - [3.11. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > ltc:isTopParent`](#ltc:hasObjectClassification_ltc:isTopParent)
  - [3.12. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > ltc:objectClassificationLevel`](#ltc:hasObjectClassification_ltc:objectClassificationLevel)
  - [3.13. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > ltc:objectClassificationName`](#ltc:hasObjectClassification_ltc:objectClassificationName)
  - [3.14. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > ltc:hasParentOrganisationalUnit`](#ltc:hasObjectClassification_ltc:hasParentOrganisationalUnit)
- [4. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasidentifier`](#ltc:hasidentifier)

**Title:** ELViS Latimer Core Schema (subCollection)

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                       | Pattern | Type   | Deprecated | Definition                                                                                                         | Title/Description                                 |
| -------------------------------------------------------------- | ------- | ------ | ---------- | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------- |
| + [ltc:hasObjectGroup](#ltc:hasObjectGroup )                   | No      | object | No         | In ../definitions/objectGroup.schema.json                                                                          | ELViS Latimer Core Schema (objectGroup)           |
| + [ltc:hasObjectClassification](#ltc:hasObjectClassification ) | No      | object | No         | In ../definitions/objectClassification.schema.json                                                                 | ELViS Latimer Core Schema (objectClassification)  |
| - [ltc:hasidentifier](#ltc:hasidentifier )                     | No      | object | No         | Same as [ELViS Latimer Core Schema (Identifier definition)](#ltc:hasObjectGroup_ObjectGroup_items_ltc:identifier ) | ELViS Latimer Core Schema (Identifier definition) |

## <a name="autogenerated_heading_2"></a>1. The following properties are required
* ltc:hasIdentifier

## <a name="ltc:hasObjectGroup"></a>2. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectGroup`

**Title:** ELViS Latimer Core Schema (objectGroup)

|                           |                                        |
| ------------------------- | -------------------------------------- |
| **Type**                  | `object`                               |
| **Required**              | Yes                                    |
| **Additional properties** | Any type allowed                       |
| **Defined in**            | ../definitions/objectGroup.schema.json |

| Property                                          | Pattern | Type   | Deprecated | Definition | Title/Description |
| ------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [ObjectGroup](#ltc:hasObjectGroup_ObjectGroup ) | No      | object | No         | -          | -                 |

### <a name="ltc:hasObjectGroup_ObjectGroup"></a>2.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectGroup > ObjectGroup`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

## <a name="ltc:hasObjectClassification"></a>3. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification`

**Title:** ELViS Latimer Core Schema (objectClassification)

|                           |                                                 |
| ------------------------- | ----------------------------------------------- |
| **Type**                  | `combining`                                     |
| **Required**              | Yes                                             |
| **Additional properties** | Any type allowed                                |
| **Defined in**            | ../definitions/objectClassification.schema.json |

| Property                                                                                           | Pattern | Type             | Deprecated | Definition | Title/Description                                                                                                                                            |
| -------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| + [ltc:isTopParent](#ltc:hasObjectClassification_ltc:isTopParent )                                 | No      | boolean          | No         | -          | true for a collection, false for a sub-collection.                                                                                                           |
| + [ltc:objectClassificationLevel](#ltc:hasObjectClassification_ltc:objectClassificationLevel )     | No      | enum (of string) | No         | -          | Classification level: ‘discipline’ or ‘category’, will be set to discipline conditionally if at collection level and to category if at sub-collection level. |
| + [ltc:objectClassificationName](#ltc:hasObjectClassification_ltc:objectClassificationName )       | No      | string           | No         | -          | Classification name. Will be a discipline or a category, depending on the level. (see the allOf condition below for its content)                             |
| - [ltc:hasParentOrganisationalUnit](#ltc:hasObjectClassification_ltc:hasParentOrganisationalUnit ) | No      | string           | No         | -          | Name of parent organizational unit (required to determine the discipline associated with a category).                                                        |

| All of(Requirement)                             |
| ----------------------------------------------- |
| [item 0](#ltc:hasObjectClassification_allOf_i0) |
| [item 1](#ltc:hasObjectClassification_allOf_i1) |
| [item 2](#ltc:hasObjectClassification_allOf_i2) |
| [item 3](#ltc:hasObjectClassification_allOf_i3) |
| [item 4](#ltc:hasObjectClassification_allOf_i4) |
| [item 5](#ltc:hasObjectClassification_allOf_i5) |
| [item 6](#ltc:hasObjectClassification_allOf_i6) |
| [item 7](#ltc:hasObjectClassification_allOf_i7) |
| [item 8](#ltc:hasObjectClassification_allOf_i8) |
| [item 9](#ltc:hasObjectClassification_allOf_i9) |

### <a name="ltc:hasObjectClassification_allOf_i0"></a>3.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 0`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_3"></a>3.1.1. If (isTopParent = true)

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                     | Pattern | Type             | Deprecated | Definition | Title/Description |
| ------------------------------------------------------------------------------------------------------------ | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationLevel](#ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationLevel ) | No      | const            | No         | -          | -                 |
| - [ltc:objectClassificationName](#ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationName )   | No      | enum (of string) | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationLevel"></a>3.1.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 0 > then > ltc:objectClassificationLevel`

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | No      |

Specific value: `"discipline"`

##### <a name="ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationName"></a>3.1.1.2. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 0 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Anthropology"
* "Botany"
* "Zoology"
* "Microbiology"
* "Palaeontology"
* "Other Biodiversity/Geodiversity"
* "Earth Geology"
* "Astrogeology"
* "Ecology"

### <a name="ltc:hasObjectClassification_allOf_i1"></a>3.2. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 1`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_4"></a>3.2.1. If (ltc:isTopParent = false)

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                     | Pattern | Type  | Deprecated | Definition | Title/Description |
| ------------------------------------------------------------------------------------------------------------ | ------- | ----- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationLevel](#ltc:hasObjectClassification_allOf_i1_then_ltc:objectClassificationLevel ) | No      | const | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i1_then_ltc:objectClassificationLevel"></a>3.2.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 1 > then > ltc:objectClassificationLevel`

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | No      |

Specific value: `"category"`

### <a name="ltc:hasObjectClassification_allOf_i2"></a>3.3. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 2`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_5"></a>3.3.1. If (ltc:hasParentOrganisationalUnit = "Anthropology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                   | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#ltc:hasObjectClassification_allOf_i2_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i2_then_ltc:objectClassificationName"></a>3.3.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 2 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Human remains"
* "Hominids remains"

### <a name="ltc:hasObjectClassification_allOf_i3"></a>3.4. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 3`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_6"></a>3.4.1. If (ltc:hasParentOrganisationalUnit = "Botany")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                   | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#ltc:hasObjectClassification_allOf_i3_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i3_then_ltc:objectClassificationName"></a>3.4.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 3 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Macrofungi, Lichens & Myxomycetes (Mycology)"
* "Algae"
* "Bryophytes"
* "Pteridophytes"
* "Seed plants"
* "Plant Genetic Resources"
* "Other botany objects"

### <a name="ltc:hasObjectClassification_allOf_i4"></a>3.5. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 4`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_7"></a>3.5.1. If (ltc:hasParentOrganisationalUnit = "Zoology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                   | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#ltc:hasObjectClassification_allOf_i4_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i4_then_ltc:objectClassificationName"></a>3.5.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 4 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Insects"
* "Arachnids"
* "Crustaceans & Myriapods"
* "Porifera (sponges)"
* "Mollusca"
* "Cnidaria"
* "Echinodermata"
* "Fishes"
* "Amphibians"
* "Reptiles"
* "Birds"
* "Mammals"
* "Animal Genetic Resources"
* "Other zoology objects"

### <a name="ltc:hasObjectClassification_allOf_i5"></a>3.6. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 5`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_8"></a>3.6.1. If (ltc:hasParentOrganisationalUnit = "Microbiology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                   | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#ltc:hasObjectClassification_allOf_i5_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i5_then_ltc:objectClassificationName"></a>3.6.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 5 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Pages"
* "Bacteria & Archaea"
* "Plasmids"
* "Protozoa"
* "Eukaryotic microorganisms"
* "Viruses (animal and plant viruses)"
* "Microfungi"
* "Algae (in microbiology collection)"
* "Other microbiology objects"

### <a name="ltc:hasObjectClassification_allOf_i6"></a>3.7. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 6`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_9"></a>3.7.1. If (ltc:hasParentOrganisationalUnit = "Palaeontology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                   | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#ltc:hasObjectClassification_allOf_i6_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i6_then_ltc:objectClassificationName"></a>3.7.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 6 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Botany fossils"
* "Invertebrate fossils"
* "Vertebrate fossils"
* "Other palaeontology objects"

### <a name="ltc:hasObjectClassification_allOf_i7"></a>3.8. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 7`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_10"></a>3.8.1. If (ltc:hasParentOrganisationalUnit = "Earth-Geology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                   | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#ltc:hasObjectClassification_allOf_i7_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i7_then_ltc:objectClassificationName"></a>3.8.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 7 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Minerals and gems"
* "Rocks"
* "Loose sediment sample"
* "Water-ice samples"
* "Liquid or gaseous matter sample"
* "Mixed geology objects"

### <a name="ltc:hasObjectClassification_allOf_i8"></a>3.9. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 8`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_11"></a>3.9.1. If (ltc:hasParentOrganisationalUnit = "Astrogeology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                           | Pattern | Type   | Deprecated | Definition | Title/Description |
| -------------------------------------------------------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [objectClassificationName](#ltc:hasObjectClassification_allOf_i8_then_objectClassificationName ) | No      | string | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i8_then_objectClassificationName"></a>3.9.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 8 > then > objectClassificationName`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

### <a name="ltc:hasObjectClassification_allOf_i9"></a>3.10. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 9`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_12"></a>3.10.1. If (ltc:hasParentOrganisationalUnit = "Ecology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                   | Pattern | Type   | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#ltc:hasObjectClassification_allOf_i9_then_ltc:objectClassificationName ) | No      | string | No         | -          | -                 |

##### <a name="ltc:hasObjectClassification_allOf_i9_then_ltc:objectClassificationName"></a>3.10.1.1. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > allOf > item 9 > then > ltc:objectClassificationName`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

### <a name="ltc:hasObjectClassification_ltc:isTopParent"></a>3.11. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > ltc:isTopParent`

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | Yes       |

**Description:** true for a collection, false for a sub-collection.

### <a name="ltc:hasObjectClassification_ltc:objectClassificationLevel"></a>3.12. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > ltc:objectClassificationLevel`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | Yes                |

**Description:** Classification level: ‘discipline’ or ‘category’, will be set to discipline conditionally if at collection level and to category if at sub-collection level.

Must be one of:
* "discipline"
* "category"

### <a name="ltc:hasObjectClassification_ltc:objectClassificationName"></a>3.13. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > ltc:objectClassificationName`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** Classification name. Will be a discipline or a category, depending on the level. (see the allOf condition below for its content)

### <a name="ltc:hasObjectClassification_ltc:hasParentOrganisationalUnit"></a>3.14. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasObjectClassification > ltc:hasParentOrganisationalUnit`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Name of parent organizational unit (required to determine the discipline associated with a category).

## <a name="ltc:hasidentifier"></a>4. Property `ELViS Latimer Core Schema (subCollection) > ltc:hasidentifier`

**Title:** ELViS Latimer Core Schema (Identifier definition)

|                           |                                                                                                           |
| ------------------------- | --------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                  |
| **Required**              | No                                                                                                        |
| **Additional properties** | Any type allowed                                                                                          |
| **Same definition as**    | [ELViS Latimer Core Schema (Identifier definition)](#ltc:hasObjectGroup_ObjectGroup_items_ltc:identifier) |

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2025-04-22 at 09:22:43 +0200
