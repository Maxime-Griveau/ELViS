# ELViS Latimer Core Schema (addresses definition)

- [1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry`](#schema:addressCountry)
  - [1.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressCountry`](#schema:addressCountry_schema:addressCountry)
    - [1.1.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressCountry > code`](#schema:addressCountry_schema:addressCountry_code)
  - [1.2. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressRegion`](#schema:addressCountry_schema:addressRegion)
    - [1.2.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressRegion > name`](#schema:addressCountry_schema:addressRegion_name)
  - [1.3. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality`](#schema:addressCountry_schema:addressLocality)
    - [1.3.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > name`](#schema:addressCountry_schema:addressLocality_name)
    - [1.3.2. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:streetAddress`](#schema:addressCountry_schema:addressLocality_schema:streetAddress)
    - [1.3.3. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:postalCode`](#schema:addressCountry_schema:addressLocality_schema:postalCode)
    - [1.3.4. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:GeoCoordinates`](#schema:addressCountry_schema:addressLocality_schema:GeoCoordinates)
      - [1.3.4.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:GeoCoordinates > latitude`](#schema:addressCountry_schema:addressLocality_schema:GeoCoordinates_latitude)
      - [1.3.4.2. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:GeoCoordinates > longitude`](#schema:addressCountry_schema:addressLocality_schema:GeoCoordinates_longitude)

**Title:** ELViS Latimer Core Schema (addresses definition)

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

**Description:** A hierarchical representation of an address.

| Property                                           | Pattern | Type   | Deprecated | Definition | Title/Description |
| -------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [schema:addressCountry](#schema:addressCountry ) | No      | object | No         | -          | -                 |

## <a name="schema:addressCountry"></a>1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

| Property                                                                   | Pattern | Type   | Deprecated | Definition | Title/Description                           |
| -------------------------------------------------------------------------- | ------- | ------ | ---------- | ---------- | ------------------------------------------- |
| + [schema:addressCountry](#schema:addressCountry_schema:addressCountry )   | No      | object | No         | -          | The country in which the entity is located. |
| - [schema:addressRegion](#schema:addressCountry_schema:addressRegion )     | No      | object | No         | -          | The region in the country.                  |
| - [schema:addressLocality](#schema:addressCountry_schema:addressLocality ) | No      | object | No         | -          | The locality in the region.                 |

### <a name="schema:addressCountry_schema:addressCountry"></a>1.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressCountry`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | Yes              |
| **Additional properties** | Any type allowed |

**Description:** The country in which the entity is located.

| Property                                                     | Pattern | Type   | Deprecated | Definition | Title/Description                          |
| ------------------------------------------------------------ | ------- | ------ | ---------- | ---------- | ------------------------------------------ |
| + [code](#schema:addressCountry_schema:addressCountry_code ) | No      | string | No         | -          | The country code using ISO 3166 (Alpha 3). |

#### <a name="schema:addressCountry_schema:addressCountry_code"></a>1.1.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressCountry > code`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** The country code using ISO 3166 (Alpha 3).

**Examples:**

```json
"AFG"
```

```json
"FRA"
```

```json
"FIN"
```

### <a name="schema:addressCountry_schema:addressRegion"></a>1.2. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressRegion`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

**Description:** The region in the country.

| Property                                                    | Pattern | Type   | Deprecated | Definition | Title/Description       |
| ----------------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------------- |
| - [name](#schema:addressCountry_schema:addressRegion_name ) | No      | string | No         | -          | The name of the region. |

#### <a name="schema:addressCountry_schema:addressRegion_name"></a>1.2.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressRegion > name`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** The name of the region.

**Examples:**

```json
"Pays-de-la-Loire"
```

```json
"Valais"
```

### <a name="schema:addressCountry_schema:addressLocality"></a>1.3. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

**Description:** The locality in the region.

| Property                                                                                        | Pattern | Type    | Deprecated | Definition | Title/Description                            |
| ----------------------------------------------------------------------------------------------- | ------- | ------- | ---------- | ---------- | -------------------------------------------- |
| + [name](#schema:addressCountry_schema:addressLocality_name )                                   | No      | string  | No         | -          | The name of the locality.                    |
| + [schema:streetAddress](#schema:addressCountry_schema:addressLocality_schema:streetAddress )   | No      | string  | No         | -          | The street address.                          |
| - [schema:postalCode](#schema:addressCountry_schema:addressLocality_schema:postalCode )         | No      | integer | No         | -          | The postal code of the address.              |
| - [schema:GeoCoordinates](#schema:addressCountry_schema:addressLocality_schema:GeoCoordinates ) | No      | object  | No         | -          | The geographical coordinates of the address. |

#### <a name="schema:addressCountry_schema:addressLocality_name"></a>1.3.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > name`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** The name of the locality.

**Examples:**

```json
"Geneva"
```

```json
"Paris"
```

```json
"London"
```

#### <a name="schema:addressCountry_schema:addressLocality_schema:streetAddress"></a>1.3.2. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:streetAddress`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** The street address.

**Examples:**

```json
"Rue de la Navigation 52"
```

```json
"57 rue Cuvier"
```

#### <a name="schema:addressCountry_schema:addressLocality_schema:postalCode"></a>1.3.3. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:postalCode`

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

**Description:** The postal code of the address.

**Examples:**

```json
75005
```

```json
1201
```

#### <a name="schema:addressCountry_schema:addressLocality_schema:GeoCoordinates"></a>1.3.4. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:GeoCoordinates`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

**Description:** The geographical coordinates of the address.

| Property                                                                                      | Pattern | Type   | Deprecated | Definition | Title/Description             |
| --------------------------------------------------------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------------------- |
| - [latitude](#schema:addressCountry_schema:addressLocality_schema:GeoCoordinates_latitude )   | No      | number | No         | -          | The latitude of the address.  |
| - [longitude](#schema:addressCountry_schema:addressLocality_schema:GeoCoordinates_longitude ) | No      | number | No         | -          | The longitude of the address. |

##### <a name="schema:addressCountry_schema:addressLocality_schema:GeoCoordinates_latitude"></a>1.3.4.1. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:GeoCoordinates > latitude`

|              |          |
| ------------ | -------- |
| **Type**     | `number` |
| **Required** | No       |

**Description:** The latitude of the address.

**Examples:**

```json
46.2044
```

```json
51.5074
```

##### <a name="schema:addressCountry_schema:addressLocality_schema:GeoCoordinates_longitude"></a>1.3.4.2. Property `ELViS Latimer Core Schema (addresses definition) > schema:addressCountry > schema:addressLocality > schema:GeoCoordinates > longitude`

|              |          |
| ------------ | -------- |
| **Type**     | `number` |
| **Required** | No       |

**Description:** The longitude of the address.

**Examples:**

```json
6.1432
```

```json
-0.1278
```

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2025-04-22 at 09:22:43 +0200
