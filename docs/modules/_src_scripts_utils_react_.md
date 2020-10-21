[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/react"](_src_scripts_utils_react_.md)

# Module: "src/scripts/utils/react"

## Index

### Variables

* [DATA_ATTR_REGEXP](_src_scripts_utils_react_.md#const-data_attr_regexp)

### Object literals

* [reactUtils](_src_scripts_utils_react_.md#const-reactutils)

## Variables

### `Const` DATA_ATTR_REGEXP

• **DATA_ATTR_REGEXP**: *RegExp‹›* = /data-/

Defined in src/scripts/utils/react.ts:14

## Object literals

### `Const` reactUtils

### ▪ **reactUtils**: *object*

Defined in src/scripts/utils/react.ts:16

###  attachRefs

▸ **attachRefs**(`mainRef`: any, ...`otherRefs`: any[]): *(Anonymous function)*

Defined in src/scripts/utils/react.ts:33

**Parameters:**

Name | Type |
------ | ------ |
`mainRef` | any |
`...otherRefs` | any[] |

**Returns:** *(Anonymous function)*

###  getChildrenData

▸ **getChildrenData**(`children`: React.ReactNode): *object[]*

Defined in src/scripts/utils/react.ts:18

**Parameters:**

Name | Type |
------ | ------ |
`children` | React.ReactNode |

**Returns:** *object[]*

###  injectChildrenProps

▸ **injectChildrenProps**(`children`: React.ReactNode, `isArray`: boolean, `getNodeProps`: function): *React.ReactNode*

Defined in src/scripts/utils/react.ts:46

**Parameters:**

▪ **children**: *React.ReactNode*

▪ **isArray**: *boolean*

▪ **getNodeProps**: *function*

▸ (`child`: ReactElement, `index`: number): *object*

**Parameters:**

Name | Type |
------ | ------ |
`child` | ReactElement |
`index` | number |

**Returns:** *React.ReactNode*

###  renderDataAttributes

▸ **renderDataAttributes**(`props`: React.ReactNode): *object*

Defined in src/scripts/utils/react.ts:23

**Parameters:**

Name | Type |
------ | ------ |
`props` | React.ReactNode |

**Returns:** *object*
