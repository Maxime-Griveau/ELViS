# ELViS Latimer Core Schema (Identifier definition)

- [1. Property `ELViS Latimer Core Schema (Identifier definition) > ltc:identifierSource`](#ltc:identifierSource)
- [2. Property `ELViS Latimer Core Schema (Identifier definition) > ltc:identifierType`](#ltc:identifierType)
- [3. Property `ELViS Latimer Core Schema (Identifier definition) > ltc:identifierValue`](#ltc:identifierValue)

**Title:** ELViS Latimer Core Schema (Identifier definition)

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                         | Pattern | Type   | Deprecated | Definition | Title/Description                                         |
| ------------------------------------------------ | ------- | ------ | ---------- | ---------- | --------------------------------------------------------- |
| + [ltc:identifierSource](#ltc:identifierSource ) | No      | string | No         | -          | The source or creator of the identifier.                  |
| + [ltc:identifierType](#ltc:identifierType )     | No      | string | No         | -          | The type and format of the value in the identifier field. |
| + [ltc:identifierValue](#ltc:identifierValue )   | No      | string | No         | -          | An unambiguous reference.                                 |

## <a name="ltc:identifierSource"></a>1. Property `ELViS Latimer Core Schema (Identifier definition) > ltc:identifierSource`

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

## <a name="ltc:identifierType"></a>2. Property `ELViS Latimer Core Schema (Identifier definition) > ltc:identifierType`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** The type and format of the value in the identifier field.

**Example:**

```json
"CETAF_ID"
```

## <a name="ltc:identifierValue"></a>3. Property `ELViS Latimer Core Schema (Identifier definition) > ltc:identifierValue`

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
