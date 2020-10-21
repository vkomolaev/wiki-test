[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/dom"](_src_scripts_utils_dom_.md)

# Module: "src/scripts/utils/dom"

## Index

### Functions

* [getWindow](_src_scripts_utils_dom_.md#getwindow)
* [startDocumentWritesBunch](_src_scripts_utils_dom_.md#startdocumentwritesbunch)
* [stopDocumentWritesBunch](_src_scripts_utils_dom_.md#stopdocumentwritesbunch)

### Object literals

* [domUtils](_src_scripts_utils_dom_.md#const-domutils)

## Functions

###  getWindow

▸ **getWindow**(`prop`: any, `defaultValue`: any): *any*

Defined in src/scripts/utils/dom.js:16

**Parameters:**

Name | Type |
------ | ------ |
`prop` | any |
`defaultValue` | any |

**Returns:** *any*

___

###  startDocumentWritesBunch

▸ **startDocumentWritesBunch**(): *void*

Defined in src/scripts/utils/dom.js:306

**Returns:** *void*

___

###  stopDocumentWritesBunch

▸ **stopDocumentWritesBunch**(`targetElement`: any): *void*

Defined in src/scripts/utils/dom.js:317

**Parameters:**

Name | Type |
------ | ------ |
`targetElement` | any |

**Returns:** *void*

## Object literals

### `Const` domUtils

### ▪ **domUtils**: *object*

Defined in src/scripts/utils/dom.js:20

###  visibilityCheckingOffset

• **visibilityCheckingOffset**: *number* = 5

Defined in src/scripts/utils/dom.js:22

###  forceToggleScroll

▸ **forceToggleScroll**(`shouldDisable`: any): *void*

Defined in src/scripts/utils/dom.js:289

**Parameters:**

Name | Type |
------ | ------ |
`shouldDisable` | any |

**Returns:** *void*

###  getChildrenWidth

▸ **getChildrenWidth**(`containerEl`: any, `includeMargin`: boolean): *number*

Defined in src/scripts/utils/dom.js:166

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`containerEl` | any | - |
`includeMargin` | boolean | false |

**Returns:** *number*

###  getMeta

▸ **getMeta**(): *meta*

Defined in src/scripts/utils/dom.js:69

**Returns:** *meta*

###  getSupportedImgFormat

▸ **getSupportedImgFormat**(): *Promise‹any›*

Defined in src/scripts/utils/dom.js:220

**Returns:** *Promise‹any›*

###  getViewportSize

▸ **getViewportSize**(): *object*

Defined in src/scripts/utils/dom.js:24

**Returns:** *object*

* **height**: *any* = bs.height ? parseInt(bs.height, 10) : e[`${a}Height`]

* **width**: *any* = bs.width ? parseInt(bs.width, 10) : e[`${a}Width`]

###  isOnScreen

▸ **isOnScreen**(`element`: any, `options`: object): *boolean*

Defined in src/scripts/utils/dom.js:41

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`element` | any | - |
`options` | object | {} |

**Returns:** *boolean*

###  loadScript

▸ **loadScript**(`src`: any, `body`: any, `container`: HTMLElement): *Promise‹void›*

Defined in src/scripts/utils/dom.js:174

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`src` | any | - |
`body` | any | - |
`container` | HTMLElement | document.body |

**Returns:** *Promise‹void›*

###  parseSocialMeta

▸ **parseSocialMeta**(): *object*

Defined in src/scripts/utils/dom.js:82

**Returns:** *object*

* **description**: *string* = ""

* **title**: *string* = ""

* **url**: *string* = ""

* ### **network**: *object*

  * **twitter**(): *object*

###  promisifyImg

▸ **promisifyImg**(`imgNode`: any): *Promise‹any›*

Defined in src/scripts/utils/dom.js:213

**Parameters:**

Name | Type |
------ | ------ |
`imgNode` | any |

**Returns:** *Promise‹any›*

###  pushState

▸ **pushState**(`url`: any): *void*

Defined in src/scripts/utils/dom.js:61

**Parameters:**

Name | Type |
------ | ------ |
`url` | any |

**Returns:** *void*

###  replaceState

▸ **replaceState**(`url`: any): *void*

Defined in src/scripts/utils/dom.js:65

**Parameters:**

Name | Type |
------ | ------ |
`url` | any |

**Returns:** *void*

###  reverseChildItems

▸ **reverseChildItems**(`container`: any): *void*

Defined in src/scripts/utils/dom.js:113

**Parameters:**

Name | Type |
------ | ------ |
`container` | any |

**Returns:** *void*

###  runScripts

▸ **runScripts**(`container`: any): *any*

Defined in src/scripts/utils/dom.js:195

**Parameters:**

Name | Type |
------ | ------ |
`container` | any |

**Returns:** *any*

###  scrollTo

▸ **scrollTo**(`to`: any, `speed`: any, `delta`: number): *void*

Defined in src/scripts/utils/dom.js:148

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`to` | any | - |
`speed` | any | - |
`delta` | number | 0 |

**Returns:** *void*

###  scrollToElementTop

▸ **scrollToElementTop**(`selector`: any, `speed`: any): *void*

Defined in src/scripts/utils/dom.js:157

**Parameters:**

Name | Type |
------ | ------ |
`selector` | any |
`speed` | any |

**Returns:** *void*

###  watchElementSize

▸ **watchElementSize**(`element`: any, `callback`: any, `interval`: any): *(Anonymous function)*

Defined in src/scripts/utils/dom.js:129

**Parameters:**

Name | Type |
------ | ------ |
`element` | any |
`callback` | any |
`interval` | any |

**Returns:** *(Anonymous function)*

###  IntersectionObserver

• **IntersectionObserver**:

Defined in src/scripts/utils/dom.js:246

###  scrollElement

• **scrollElement**:

Defined in src/scripts/utils/dom.js:277

###  scrollTop

• **scrollTop**:

Defined in src/scripts/utils/dom.js:281

Defined in src/scripts/utils/dom.js:285
