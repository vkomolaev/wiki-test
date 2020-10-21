[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/fetch"](_src_scripts_utils_fetch_.md)

# Module: "src/scripts/utils/fetch"

## Index

### Object literals

* [fetchUtils](_src_scripts_utils_fetch_.md#const-fetchutils)

## Object literals

### `Const` fetchUtils

### ▪ **fetchUtils**: *object*

Defined in src/scripts/utils/fetch.js:17

###  fetch

▸ **fetch**(`url`: any, `requestParams`: object, `options`: any): *Promise‹any›*

Defined in src/scripts/utils/fetch.js:18

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`url` | any | - |
`requestParams` | object | {} |
`options` | any | - |

**Returns:** *Promise‹any›*

###  fetchHtml

▸ **fetchHtml**(`url`: any, `requestParams`: object, `options`: object): *Promise‹any›*

Defined in src/scripts/utils/fetch.js:30

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`url` | any | - |
`requestParams` | object | {} |
`options` | object | {} |

**Returns:** *Promise‹any›*

###  fetchJson

▸ **fetchJson**(`url`: any, `requestParams`: object, `options`: object): *Promise‹any›*

Defined in src/scripts/utils/fetch.js:48

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`url` | any | - |
`requestParams` | object | {} |
`options` | object | {} |

**Returns:** *Promise‹any›*

###  startFeedStream

▸ **startFeedStream**(`feedUrl`: any, `callback`: any, `intervalCheck`: any, `__namedParameters`: object): *any*

Defined in src/scripts/utils/fetch.js:77

**Parameters:**

▪ **feedUrl**: *any*

▪ **callback**: *any*

▪ **intervalCheck**: *any*

▪ **__namedParameters**: *object*

Name | Type | Default |
------ | ------ | ------ |
`queryFailsLimit` | number | 0 |
`queryMaxInterval` | number | 60000 |
`queryMinInterval` | number | 5000 |

**Returns:** *any*
