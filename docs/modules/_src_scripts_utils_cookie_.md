[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/cookie"](_src_scripts_utils_cookie_.md)

# Module: "src/scripts/utils/cookie"

## Index

### Object literals

* [cookieUtils](_src_scripts_utils_cookie_.md#const-cookieutils)

## Object literals

### `Const` cookieUtils

### ▪ **cookieUtils**: *object*

Defined in src/scripts/utils/cookie.ts:12

###  createCookie

▸ **createCookie**(`name`: string, `value`: string, `date`: number, `domain`: string): *void*

Defined in src/scripts/utils/cookie.ts:13

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`name` | string | - |
`value` | string | - |
`date` | number | Date.now() + 3600 * 1000 * 24 * 365 |
`domain` | string | - |

**Returns:** *void*

###  deleteCookie

▸ **deleteCookie**(`name`: string, `domain`: string): *void*

Defined in src/scripts/utils/cookie.ts:17

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |
`domain` | string |

**Returns:** *void*

###  getCookie

▸ **getCookie**(`name`: string): *string*

Defined in src/scripts/utils/cookie.ts:22

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |

**Returns:** *string*
