# Subdocument Schema

```txt
undefined#/items/properties/children/items
```

Object defining the subdocument

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                          |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [config.schema.json*](../config.schema.json "open original schema") |

## items Type

`object` ([Subdocument](config-json-document-properties-subdocuments-subdocument.md))

# items Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                       |
| :---------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [path](#path)           | `string` | Required | cannot be null | [JSON sub-document](config-json-document-properties-subdocuments-subdocument-properties-path.md "undefined#/items/properties/children/items/properties/path")                                    |
| [name](#name)           | `string` | Optional | cannot be null | [JSON sub-document](config-json-document-properties-subdocuments-subdocument-properties-name.md "undefined#/items/properties/children/items/properties/name")                                    |
| [structure](#structure) | `object` | Optional | cannot be null | [JSON sub-document](config-json-document-properties-subdocuments-subdocument-properties-subdocuments-structure-json-object.md "undefined#/items/properties/children/items/properties/structure") |

## path

Path to the destination JSON file

`path`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [JSON sub-document](config-json-document-properties-subdocuments-subdocument-properties-path.md "undefined#/items/properties/children/items/properties/path")

### path Type

`string`

## name

Destination file name

`name`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [JSON sub-document](config-json-document-properties-subdocuments-subdocument-properties-name.md "undefined#/items/properties/children/items/properties/name")

### name Type

`string`

## structure



`structure`

*   is optional

*   Type: `object` ([Subdocument's structure (JSON object)](config-json-document-properties-subdocuments-subdocument-properties-subdocuments-structure-json-object.md))

*   cannot be null

*   defined in: [JSON sub-document](config-json-document-properties-subdocuments-subdocument-properties-subdocuments-structure-json-object.md "undefined#/items/properties/children/items/properties/structure")

### structure Type

`object` ([Subdocument's structure (JSON object)](config-json-document-properties-subdocuments-subdocument-properties-subdocuments-structure-json-object.md))
