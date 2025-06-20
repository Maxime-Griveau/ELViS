# ELViS Latimer Core Schema (Instrument or service)

- [1. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:hasOrganisationalUnit`](#ltc:hasOrganisationalUnit)
  - [1.1. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:hasOrganisationalUnit > ltc:organisationalUnit`](#ltc:hasOrganisationalUnit_ltc:organisationalUnit)
    - [1.1.1. The following properties are required](#autogenerated_heading_2)
- [2. Property `ELViS Latimer Core Schema (Instrument or service) > schema:image`](#schema:image)
  - [2.1. ELViS Latimer Core Schema (Instrument or service) > schema:image > schema:image items](#schema:image_items)
- [3. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:identifier`](#ltc:identifier)
  - [3.1. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:identifier > ltc:identifierSource`](#ltc:identifier_ltc:identifierSource)
  - [3.2. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:identifier > ltc:identifierType`](#ltc:identifier_ltc:identifierType)
  - [3.3. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:identifier > ltc:identifierValue`](#ltc:identifier_ltc:identifierValue)

**Title:** ELViS Latimer Core Schema (Instrument or service)

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                   | Pattern | Type            | Deprecated | Definition                                       | Title/Description                                 |
| ---------------------------------------------------------- | ------- | --------------- | ---------- | ------------------------------------------------ | ------------------------------------------------- |
| + [ltc:hasOrganisationalUnit](#ltc:hasOrganisationalUnit ) | No      | object          | No         | In ../definitions/organisationalUnit.schema.json | ELViS Latimer Core Schema (Organisational Unit)   |
| - [schema:image](#schema:image )                           | No      | array of string | No         | -                                                | -                                                 |
| - [ltc:identifier](#ltc:identifier )                       | No      | object          | No         | In ../definitions/identifier.schema.json         | ELViS Latimer Core Schema (Identifier definition) |

## <a name="ltc:hasOrganisationalUnit"></a>1. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:hasOrganisationalUnit`

**Title:** ELViS Latimer Core Schema (Organisational Unit)

|                           |                                               |
| ------------------------- | --------------------------------------------- |
| **Type**                  | `object`                                      |
| **Required**              | Yes                                           |
| **Additional properties** | Any type allowed                              |
| **Defined in**            | ../definitions/organisationalUnit.schema.json |

| Property                                                                       | Pattern | Type   | Deprecated | Definition | Title/Description |
| ------------------------------------------------------------------------------ | ------- | ------ | ---------- | ---------- | ----------------- |
| - [ltc:organisationalUnit](#ltc:hasOrganisationalUnit_ltc:organisationalUnit ) | No      | object | No         | -          | -                 |

### <a name="ltc:hasOrganisationalUnit_ltc:organisationalUnit"></a>1.1. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:hasOrganisationalUnit > ltc:organisationalUnit`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

#### <a name="autogenerated_heading_2"></a>1.1.1. The following properties are required
* ltc:organisationalUnitName
* ltc:organisationalUnitType
* ltc:hasAddres

## <a name="schema:image"></a>2. Property `ELViS Latimer Core Schema (Instrument or service) > schema:image`

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

| Each item of this array must be           | Description |
| ----------------------------------------- | ----------- |
| [schema:image items](#schema:image_items) | -           |

### <a name="schema:image_items"></a>2.1. ELViS Latimer Core Schema (Instrument or service) > schema:image > schema:image items

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Format**   | `uri`    |

## <a name="ltc:identifier"></a>3. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:identifier`

**Title:** ELViS Latimer Core Schema (Identifier definition)

|                           |                                       |
| ------------------------- | ------------------------------------- |
| **Type**                  | `object`                              |
| **Required**              | No                                    |
| **Additional properties** | Any type allowed                      |
| **Defined in**            | ../definitions/identifier.schema.json |

| Property                                                        | Pattern | Type   | Deprecated | Definition | Title/Description                                         |
| --------------------------------------------------------------- | ------- | ------ | ---------- | ---------- | --------------------------------------------------------- |
| + [ltc:identifierSource](#ltc:identifier_ltc:identifierSource ) | No      | string | No         | -          | The source or creator of the identifier.                  |
| + [ltc:identifierType](#ltc:identifier_ltc:identifierType )     | No      | string | No         | -          | The type and format of the value in the identifier field. |
| + [ltc:identifierValue](#ltc:identifier_ltc:identifierValue )   | No      | string | No         | -          | An unambiguous reference.                                 |

### <a name="ltc:identifier_ltc:identifierSource"></a>3.1. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:identifier > ltc:identifierSource`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** The source or creator of the identifier.

**Examples:**

```json
"GBIF Registry"
```

```json
"CETAF"
```

### <a name="ltc:identifier_ltc:identifierType"></a>3.2. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:identifier > ltc:identifierType`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** The type and format of the value in the identifier field.

**Example:**

```json
"CETAF_ID"
```

### <a name="ltc:identifier_ltc:identifierValue"></a>3.3. Property `ELViS Latimer Core Schema (Instrument or service) > ltc:identifier > ltc:identifierValue`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** An unambiguous reference.

**Example:**

```json
"https://cetaf.org/botanic-garden-meise-0"
```

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2025-04-22 at 09:22:43 +0200
