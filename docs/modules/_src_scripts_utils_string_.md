[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/string"](_src_scripts_utils_string_.md)

# Module: "src/scripts/utils/string"

## Index

### Variables

* [ALL_BRACKETS_REGEXP](_src_scripts_utils_string_.md#const-all_brackets_regexp)

### Object literals

* [stringUtils](_src_scripts_utils_string_.md#const-stringutils)

## Variables

### `Const` ALL_BRACKETS_REGEXP

• **ALL_BRACKETS_REGEXP**: *RegExp‹›* = /{.*?}/g

Defined in src/scripts/utils/string.ts:15

## Object literals

### `Const` stringUtils

### ▪ **stringUtils**: *object*

Defined in src/scripts/utils/string.ts:17

###  decodeHtml

▸ **decodeHtml**(`html`: string): *string*

Defined in src/scripts/utils/string.ts:51

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`html` | string | "" |

**Returns:** *string*

###  getMatchedString

▸ **getMatchedString**(`str`: string, `pattern`: string): *string*

Defined in src/scripts/utils/string.ts:19

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`str` | string | "" |
`pattern` | string | - |

**Returns:** *string*

###  guid

▸ **guid**(): *string*

Defined in src/scripts/utils/string.ts:40

**Returns:** *string*

###  removeBreaklines

▸ **removeBreaklines**(`str`: string): *string*

Defined in src/scripts/utils/string.ts:55

**Parameters:**

Name | Type |
------ | ------ |
`str` | string |

**Returns:** *string*

###  replaceStrByKey

▸ **replaceStrByKey**(`str`: string, `obj`: Record‹string, any›): *string*

Defined in src/scripts/utils/string.ts:44

**Parameters:**

Name | Type |
------ | ------ |
`str` | string |
`obj` | Record‹string, any› |

**Returns:** *string*

###  replaceTemplateVariables

▸ **replaceTemplateVariables**(`template`: string, `data`: any): *string*

Defined in src/scripts/utils/string.ts:59

**Parameters:**

Name | Type |
------ | ------ |
`template` | string |
`data` | any |

**Returns:** *string*

###  s4

▸ **s4**(): *string*

Defined in src/scripts/utils/string.ts:28

**Returns:** *string*

###  substitute

▸ **substitute**(`str`: string, `root`: any): *string*

Defined in src/scripts/utils/string.ts:34

**Parameters:**

Name | Type |
------ | ------ |
`str` | string |
`root` | any |

**Returns:** *string*
