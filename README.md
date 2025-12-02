# Template Convention Metadata

- **UUID**: f010a634-3525-416e-9320-8f44b5bc352c
- **Name**: Template
- **Schema URL**: "https://raw.githubusercontent.com/zarr-conventions/template/refs/tags/v1/schema.json"
- **Spec URL**: "https://github.com/zarr-conventions/template/blob/v1/README.md"
- **Scope**: Array, Group
- **Extension Maturity Classification****: Proposal
- **Owner**: @your-github-handle, @another-github-handle

The document explains the Template convention, which is a Zarr convention metadata. This is the place to add a short introduction.

- Examples:
    - [Convention metadata example](examples/zarr_convention_metadata.json)

## Convention Attributes

This convention defines attributes that appear at the root level of the Zarr `attributes` object. The convention can be used in these parts of the Zarr hierarchy:

- [x] Group
- [x] Array

All convention-specific attribute names are prefixed with `template:` to avoid conflicts with other conventions.

| Field Name           | Type                      | Description                                  |
| -------------------- | ------------------------- | -------------------------------------------- |
| template:new_field   | string                    | **REQUIRED**. Describe the required field... |
| template:xyz         | [XYZ Object](#xyz-object) | Describe the field...                        |
| template:another_one | \[number]                 | Describe the field...                        |

### Additional Field Information

#### template:new_field

This is a much more detailed description of the field `template:new_field`...

### XYZ Object

This is the introduction for the purpose and the content of the XYZ Object...

| Field Name | Type   | Description                                  |
| ---------- | ------ | -------------------------------------------- |
| x          | number | **REQUIRED**. Describe the required field... |
| y          | number | **REQUIRED**. Describe the required field... |
| z          | number | **REQUIRED**. Describe the required field... |

## Acknowledgements

This template is based on the [STAC extensions template](https://github.com/stac-extensions/template/blob/main/README.md).
