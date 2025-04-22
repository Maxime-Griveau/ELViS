# ELViS Latimer Core Schema (Modular)

**Title:** ELViS Latimer Core Schema (Modular)


| Property                         | Pattern | Type   | Deprecated | Definition | Title/Description |
| -------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [Institution](#Institution )   | No      | object | No         | -          | -                 |
| - [required](#required )         | No      | object | No         | -          | -                 |
| - [oneOf](#oneOf )               | No      | object | No         | -          | -                 |
| - [errorMessage](#errorMessage ) | No      | object | No         | -          | -                 |

## <a name="Institution"></a>1. Property `ELViS Latimer Core Schema (Modular) > Institution`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                   | Pattern | Type  | Deprecated | Definition | Title/Description |
| ------------------------------------------ | ------- | ----- | ---------- | ---------- | ----------------- |
| - [Collections](#Institution_Collections ) | No      | array | No         | -          | -                 |
| - [Facilities](#Institution_Facilities )   | No      | array | No         | -          | -                 |

### <a name="Institution_Collections"></a>1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections`

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | No      |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                          | Description |
| ------------------------------------------------------------------------ | ----------- |
| [ELViS Latimer Core Schema (collection)](#Institution_Collections_items) | -           |

#### <a name="Institution_Collections_items"></a>1.1.1. ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection)

**Title:** ELViS Latimer Core Schema (collection)

|                           |                                   |
| ------------------------- | --------------------------------- |
| **Type**                  | `object`                          |
| **Required**              | No                                |
| **Additional properties** | Any type allowed                  |
| **Defined in**            | ./entities/collection.schema.json |

| Property                                                                                     | Pattern | Type   | Deprecated | Definition                                                                                                                                              | Title/Description                                 |
| -------------------------------------------------------------------------------------------- | ------- | ------ | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| + [ltc:hasObjectGroup](#Institution_Collections_items_ltc:hasObjectGroup )                   | No      | object | No         | In ../definitions/objectGroup.schema.json                                                                                                               | ELViS Latimer Core Schema (objectGroup)           |
| + [ltc:hasIdentifier](#Institution_Collections_items_ltc:hasIdentifier )                     | No      | object | No         | Same as [ELViS Latimer Core Schema (Identifier definition)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:identifier )        | ELViS Latimer Core Schema (Identifier definition) |
| - [ltc:hasAddress](#Institution_Collections_items_ltc:hasAddress )                           | No      | object | No         | Same as [ELViS Latimer Core Schema (addresses definition)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:hasStorageLocation ) | ELViS Latimer Core Schema (addresses definition)  |
| + [ltc:hasObjectClassification](#Institution_Collections_items_ltc:hasObjectClassification ) | No      | object | No         | In ../definitions/objectClassification.schema.json                                                                                                      | ELViS Latimer Core Schema (objectClassification)  |

##### <a name="Institution_Collections_items_ltc:hasObjectGroup"></a>1.1.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectGroup`

**Title:** ELViS Latimer Core Schema (objectGroup)

|                           |                                        |
| ------------------------- | -------------------------------------- |
| **Type**                  | `object`                               |
| **Required**              | Yes                                    |
| **Additional properties** | Any type allowed                       |
| **Defined in**            | ../definitions/objectGroup.schema.json |

| Property                                                                        | Pattern | Type   | Deprecated | Definition | Title/Description |
| ------------------------------------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [ObjectGroup](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup ) | No      | object | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup"></a>1.1.1.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectGroup > ObjectGroup`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

##### <a name="Institution_Collections_items_ltc:hasIdentifier"></a>1.1.1.2. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasIdentifier`

**Title:** ELViS Latimer Core Schema (Identifier definition)

|                           |                                                                                                                                         |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                                                |
| **Required**              | Yes                                                                                                                                     |
| **Additional properties** | Any type allowed                                                                                                                        |
| **Same definition as**    | [ELViS Latimer Core Schema (Identifier definition)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:identifier) |

##### <a name="Institution_Collections_items_ltc:hasAddress"></a>1.1.1.3. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasAddress`

**Title:** ELViS Latimer Core Schema (addresses definition)

|                           |                                                                                                                                                |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                                                       |
| **Required**              | No                                                                                                                                             |
| **Additional properties** | Any type allowed                                                                                                                               |
| **Same definition as**    | [ELViS Latimer Core Schema (addresses definition)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:hasStorageLocation) |

**Description:** A hierarchical representation of an address.

##### <a name="Institution_Collections_items_ltc:hasObjectClassification"></a>1.1.1.4. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification`

**Title:** ELViS Latimer Core Schema (objectClassification)

|                           |                                                 |
| ------------------------- | ----------------------------------------------- |
| **Type**                  | `combining`                                     |
| **Required**              | Yes                                             |
| **Additional properties** | Any type allowed                                |
| **Defined in**            | ../definitions/objectClassification.schema.json |

| Property                                                                                                                         | Pattern | Type             | Deprecated | Definition | Title/Description                                                                                                                                            |
| -------------------------------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| + [ltc:isTopParent](#Institution_Collections_items_ltc:hasObjectClassification_ltc:isTopParent )                                 | No      | boolean          | No         | -          | true for a collection, false for a sub-collection.                                                                                                           |
| + [ltc:objectClassificationLevel](#Institution_Collections_items_ltc:hasObjectClassification_ltc:objectClassificationLevel )     | No      | enum (of string) | No         | -          | Classification level: ‘discipline’ or ‘category’, will be set to discipline conditionally if at collection level and to category if at sub-collection level. |
| + [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_ltc:objectClassificationName )       | No      | string           | No         | -          | Classification name. Will be a discipline or a category, depending on the level. (see the allOf condition below for its content)                             |
| - [ltc:hasParentOrganisationalUnit](#Institution_Collections_items_ltc:hasObjectClassification_ltc:hasParentOrganisationalUnit ) | No      | string           | No         | -          | Name of parent organizational unit (required to determine the discipline associated with a category).                                                        |

| All of(Requirement)                                                           |
| ----------------------------------------------------------------------------- |
| [item 0](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i0) |
| [item 1](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i1) |
| [item 2](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i2) |
| [item 3](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i3) |
| [item 4](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i4) |
| [item 5](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i5) |
| [item 6](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i6) |
| [item 7](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i7) |
| [item 8](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i8) |
| [item 9](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i9) |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i0"></a>1.1.1.4.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 0`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_2"></a>1.1.1.4.1.1. If (isTopParent = true)

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                   | Pattern | Type             | Deprecated | Definition | Title/Description |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationLevel](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationLevel ) | No      | const            | No         | -          | -                 |
| - [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationName )   | No      | enum (of string) | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationLevel"></a>1.1.1.4.1.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 0 > then > ltc:objectClassificationLevel`

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | No      |

Specific value: `"discipline"`

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i0_then_ltc:objectClassificationName"></a>1.1.1.4.1.1.2. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 0 > then > ltc:objectClassificationName`

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

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i1"></a>1.1.1.4.2. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 1`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_3"></a>1.1.1.4.2.1. If (ltc:isTopParent = false)

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                   | Pattern | Type  | Deprecated | Definition | Title/Description |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------- | ----- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationLevel](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i1_then_ltc:objectClassificationLevel ) | No      | const | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i1_then_ltc:objectClassificationLevel"></a>1.1.1.4.2.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 1 > then > ltc:objectClassificationLevel`

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | No      |

Specific value: `"category"`

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i2"></a>1.1.1.4.3. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 2`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_4"></a>1.1.1.4.3.1. If (ltc:hasParentOrganisationalUnit = "Anthropology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                 | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i2_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i2_then_ltc:objectClassificationName"></a>1.1.1.4.3.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 2 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Human remains"
* "Hominids remains"

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i3"></a>1.1.1.4.4. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 3`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_5"></a>1.1.1.4.4.1. If (ltc:hasParentOrganisationalUnit = "Botany")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                 | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i3_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i3_then_ltc:objectClassificationName"></a>1.1.1.4.4.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 3 > then > ltc:objectClassificationName`

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

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i4"></a>1.1.1.4.5. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 4`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_6"></a>1.1.1.4.5.1. If (ltc:hasParentOrganisationalUnit = "Zoology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                 | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i4_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i4_then_ltc:objectClassificationName"></a>1.1.1.4.5.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 4 > then > ltc:objectClassificationName`

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

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i5"></a>1.1.1.4.6. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 5`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_7"></a>1.1.1.4.6.1. If (ltc:hasParentOrganisationalUnit = "Microbiology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                 | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i5_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i5_then_ltc:objectClassificationName"></a>1.1.1.4.6.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 5 > then > ltc:objectClassificationName`

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

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i6"></a>1.1.1.4.7. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 6`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_8"></a>1.1.1.4.7.1. If (ltc:hasParentOrganisationalUnit = "Palaeontology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                 | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i6_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i6_then_ltc:objectClassificationName"></a>1.1.1.4.7.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 6 > then > ltc:objectClassificationName`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

Must be one of:
* "Botany fossils"
* "Invertebrate fossils"
* "Vertebrate fossils"
* "Other palaeontology objects"

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i7"></a>1.1.1.4.8. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 7`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_9"></a>1.1.1.4.8.1. If (ltc:hasParentOrganisationalUnit = "Earth-Geology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                 | Pattern | Type             | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i7_then_ltc:objectClassificationName ) | No      | enum (of string) | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i7_then_ltc:objectClassificationName"></a>1.1.1.4.8.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 7 > then > ltc:objectClassificationName`

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

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i8"></a>1.1.1.4.9. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 8`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_10"></a>1.1.1.4.9.1. If (ltc:hasParentOrganisationalUnit = "Astrogeology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                         | Pattern | Type   | Deprecated | Definition | Title/Description |
| -------------------------------------------------------------------------------------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i8_then_objectClassificationName ) | No      | string | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i8_then_objectClassificationName"></a>1.1.1.4.9.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 8 > then > objectClassificationName`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i9"></a>1.1.1.4.10. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 9`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_11"></a>1.1.1.4.10.1. If (ltc:hasParentOrganisationalUnit = "Ecology")

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                                                                                 | Pattern | Type   | Deprecated | Definition | Title/Description |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [ltc:objectClassificationName](#Institution_Collections_items_ltc:hasObjectClassification_allOf_i9_then_ltc:objectClassificationName ) | No      | string | No         | -          | -                 |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_allOf_i9_then_ltc:objectClassificationName"></a>1.1.1.4.10.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > allOf > item 9 > then > ltc:objectClassificationName`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_ltc:isTopParent"></a>1.1.1.4.11. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > ltc:isTopParent`

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | Yes       |

**Description:** true for a collection, false for a sub-collection.

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_ltc:objectClassificationLevel"></a>1.1.1.4.12. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > ltc:objectClassificationLevel`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | Yes                |

**Description:** Classification level: ‘discipline’ or ‘category’, will be set to discipline conditionally if at collection level and to category if at sub-collection level.

Must be one of:
* "discipline"
* "category"

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_ltc:objectClassificationName"></a>1.1.1.4.13. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > ltc:objectClassificationName`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** Classification name. Will be a discipline or a category, depending on the level. (see the allOf condition below for its content)

###### <a name="Institution_Collections_items_ltc:hasObjectClassification_ltc:hasParentOrganisationalUnit"></a>1.1.1.4.14. Property `ELViS Latimer Core Schema (Modular) > Institution > Collections > ELViS Latimer Core Schema (collection) > ltc:hasObjectClassification > ltc:hasParentOrganisationalUnit`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Name of parent organizational unit (required to determine the discipline associated with a category).

### <a name="Institution_Facilities"></a>1.2. Property `ELViS Latimer Core Schema (Modular) > Institution > Facilities`

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | No      |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                         | Description |
| ----------------------------------------------------------------------- | ----------- |
| [ELViS Latimer Core Schema (facilities)](#Institution_Facilities_items) | -           |

#### <a name="Institution_Facilities_items"></a>1.2.1. ELViS Latimer Core Schema (Modular) > Institution > Facilities > ELViS Latimer Core Schema (facilities)

**Title:** ELViS Latimer Core Schema (facilities)

|                           |                                 |
| ------------------------- | ------------------------------- |
| **Type**                  | `object`                        |
| **Required**              | No                              |
| **Additional properties** | Any type allowed                |
| **Defined in**            | ./entities/facility.schema.json |

| Property                                                                                | Pattern | Type            | Deprecated | Definition                                                                                                                                              | Title/Description                                 |
| --------------------------------------------------------------------------------------- | ------- | --------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| + [ltc:hasOrganisationalUnit](#Institution_Facilities_items_ltc:hasOrganisationalUnit ) | No      | object          | No         | Same as [ELViS Latimer Core Schema (Organisational Unit)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:hasorganisationUnit ) | ELViS Latimer Core Schema (Organisational Unit)   |
| - [schema:image](#Institution_Facilities_items_schema:image )                           | No      | array of string | No         | -                                                                                                                                                       | -                                                 |
| - [ltc:identifier](#Institution_Facilities_items_ltc:identifier )                       | No      | object          | No         | Same as [ELViS Latimer Core Schema (Identifier definition)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:identifier )        | ELViS Latimer Core Schema (Identifier definition) |
| - [ltc:address](#Institution_Facilities_items_ltc:address )                             | No      | object          | No         | Same as [ELViS Latimer Core Schema (addresses definition)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:hasStorageLocation ) | ELViS Latimer Core Schema (addresses definition)  |

##### <a name="Institution_Facilities_items_ltc:hasOrganisationalUnit"></a>1.2.1.1. Property `ELViS Latimer Core Schema (Modular) > Institution > Facilities > ELViS Latimer Core Schema (facilities) > ltc:hasOrganisationalUnit`

**Title:** ELViS Latimer Core Schema (Organisational Unit)

|                           |                                                                                                                                                |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                                                       |
| **Required**              | Yes                                                                                                                                            |
| **Additional properties** | Any type allowed                                                                                                                               |
| **Same definition as**    | [ELViS Latimer Core Schema (Organisational Unit)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:hasorganisationUnit) |

##### <a name="Institution_Facilities_items_schema:image"></a>1.2.1.2. Property `ELViS Latimer Core Schema (Modular) > Institution > Facilities > ELViS Latimer Core Schema (facilities) > schema:image`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of string` |
| **Required** | No                |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                        | Description |
| ---------------------------------------------------------------------- | ----------- |
| [schema:image items](#Institution_Facilities_items_schema:image_items) | -           |

###### <a name="Institution_Facilities_items_schema:image_items"></a>1.2.1.2.1. ELViS Latimer Core Schema (Modular) > Institution > Facilities > ELViS Latimer Core Schema (facilities) > schema:image > schema:image items

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Format**   | `uri`    |

##### <a name="Institution_Facilities_items_ltc:identifier"></a>1.2.1.3. Property `ELViS Latimer Core Schema (Modular) > Institution > Facilities > ELViS Latimer Core Schema (facilities) > ltc:identifier`

**Title:** ELViS Latimer Core Schema (Identifier definition)

|                           |                                                                                                                                         |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                                                |
| **Required**              | No                                                                                                                                      |
| **Additional properties** | Any type allowed                                                                                                                        |
| **Same definition as**    | [ELViS Latimer Core Schema (Identifier definition)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:identifier) |

##### <a name="Institution_Facilities_items_ltc:address"></a>1.2.1.4. Property `ELViS Latimer Core Schema (Modular) > Institution > Facilities > ELViS Latimer Core Schema (facilities) > ltc:address`

**Title:** ELViS Latimer Core Schema (addresses definition)

|                           |                                                                                                                                                |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                                                       |
| **Required**              | No                                                                                                                                             |
| **Additional properties** | Any type allowed                                                                                                                               |
| **Same definition as**    | [ELViS Latimer Core Schema (addresses definition)](#Institution_Collections_items_ltc:hasObjectGroup_ObjectGroup_items_ltc:hasStorageLocation) |

**Description:** A hierarchical representation of an address.

## <a name="required"></a>2. Property `ELViS Latimer Core Schema (Modular) > required`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

## <a name="oneOf"></a>3. Property `ELViS Latimer Core Schema (Modular) > oneOf`

**Title:** ltc:ConditionOffAccess conditionnal logic


**Description** : This mean that either the collections OR the sub-collection (but only one of them) must have an ltc:conditionOfAccess property filled in.


|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | OneOff — LtC:conditionsOfAccess           |
| **Additional properties** | Any type allowed |


----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2025-04-22 at 09:22:43 +0200
