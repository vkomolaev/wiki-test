[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/data-context/data-context"](_src_markups_components_data_context_data_context_.md)

# Module: "src/markups/components/data-context/data-context"

## Index

### Type aliases

* [PageDataOptions](_src_markups_components_data_context_data_context_.md#pagedataoptions)

### Variables

* [DataContext](_src_markups_components_data_context_data_context_.md#const-datacontext)
* [PAGE_DATA](_src_markups_components_data_context_data_context_.md#let-page_data)

### Functions

* [getPageData](_src_markups_components_data_context_data_context_.md#getpagedata)
* [setPageData](_src_markups_components_data_context_data_context_.md#setpagedata)

## Type aliases

###  PageDataOptions

Ƭ **PageDataOptions**: *object & object*

Defined in src/markups/components/data-context/data-context.tsx:16

## Variables

### `Const` DataContext

• **DataContext**: *Context‹object›* = React.createContext({})

Defined in src/markups/components/data-context/data-context.tsx:24

___

### `Let` PAGE_DATA

• **PAGE_DATA**: *[PageDataOptions](_src_markups_components_data_context_data_context_.md#pagedataoptions)*

Defined in src/markups/components/data-context/data-context.tsx:22

## Functions

###  getPageData

▸ **getPageData**(`path?`: string, `defaultValue?`: any): *any*

Defined in src/markups/components/data-context/data-context.tsx:33

**Parameters:**

Name | Type |
------ | ------ |
`path?` | string |
`defaultValue?` | any |

**Returns:** *any*

___

###  setPageData

▸ **setPageData**(`pageData`: [PageDataOptions](_src_markups_components_data_context_data_context_.md#pagedataoptions)): *void*

Defined in src/markups/components/data-context/data-context.tsx:29

**Parameters:**

Name | Type |
------ | ------ |
`pageData` | [PageDataOptions](_src_markups_components_data_context_data_context_.md#pagedataoptions) |

**Returns:** *void*
