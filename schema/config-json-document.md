# JSON document Schema

```txt
undefined#/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                          |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [config.schema.json*](../config.schema.json "open original schema") |

## items Type

`object` ([JSON document](config-json-document.md))

# items Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                  |
| :-------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------- |
| [path](#path)         | `string` | Required | cannot be null | [JSON sub-document](config-json-document-properties-path.md "undefined#/items/properties/path")             |
| [children](#children) | `array`  | Required | cannot be null | [JSON sub-document](config-json-document-properties-subdocuments.md "undefined#/items/properties/children") |

## path

Path to the JSON file

`path`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JSON sub-document](config-json-document-properties-path.md "undefined#/items/properties/path")

### path Type

`string`

## children



`children`

*   is required

*   Type: `object[]` ([Subdocument](config-json-document-properties-subdocuments-subdocument.md))

*   cannot be null

*   defined in: [JSON sub-document](config-json-document-properties-subdocuments.md "undefined#/items/properties/children")

### children Type

`object[]` ([Subdocument](config-json-document-properties-subdocuments-subdocument.md))
