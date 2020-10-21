[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/stats"](_src_scripts_utils_stats_.md)

# Module: "src/scripts/utils/stats"

## Index

### Functions

* [resolvePair](_src_scripts_utils_stats_.md#resolvepair)

### Object literals

* [TYPES](_src_scripts_utils_stats_.md#const-types)
* [statsUtils](_src_scripts_utils_stats_.md#const-statsutils)

## Functions

###  resolvePair

▸ **resolvePair**(`stat1`: any, `stat2`: any): *number*

Defined in src/scripts/utils/stats.js:52

**Parameters:**

Name | Type |
------ | ------ |
`stat1` | any |
`stat2` | any |

**Returns:** *number*

## Object literals

### `Const` TYPES

### ▪ **TYPES**: *object*

Defined in src/scripts/utils/stats.js:16

###  DATE

• **DATE**: *string* = "Corebine.Core.Type.Property.Date"

Defined in src/scripts/utils/stats.js:17

###  INTEGER_PAIR

• **INTEGER_PAIR**: *string* = "Corebine.Core.Type.Property.Integer.Pair"

Defined in src/scripts/utils/stats.js:20

###  NUMBER

• **NUMBER**: *string* = "Corebine.Core.Type.Property.Number"

Defined in src/scripts/utils/stats.js:18

###  NUMBER_PAIR

• **NUMBER_PAIR**: *string* = "Corebine.Core.Type.Property.Number.Pair"

Defined in src/scripts/utils/stats.js:19

___

### `Const` statsUtils

### ▪ **statsUtils**: *object*

Defined in src/scripts/utils/stats.js:23

###  resolveValue

▸ **resolveValue**(`stat`: object, `options`: object): *string | number*

Defined in src/scripts/utils/stats.js:34

**Parameters:**

▪`Default value`  **stat**: *object*= {value: 0}

Name | Type | Default |
------ | ------ | ------ |
`value` | number | 0 |

▪`Default value`  **options**: *object*= {}

**Returns:** *string | number*

▪ **units**: *object*

Defined in src/scripts/utils/stats.js:24

* **cm**: *string* = "cm"

* **kg**: *string* = "kg"

* **km**: *string* = "km"

* **min**: *string* = "m"

* **percents**: *string* = "%"

* **plus-minus**: *string* = "+/-"

* **sec**: *string* = "s"
