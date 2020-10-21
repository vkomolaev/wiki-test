[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/cloudinary"](_src_scripts_utils_cloudinary_.md)

# Module: "src/scripts/utils/cloudinary"

## Index

### Variables

* [CLOUDINARY_DOMAIN](_src_scripts_utils_cloudinary_.md#const-cloudinary_domain)
* [CloudinaryCore](_src_scripts_utils_cloudinary_.md#const-cloudinarycore)
* [cloudinary](_src_scripts_utils_cloudinary_.md#const-cloudinary)

### Functions

* [extendCloudinaryUrl](_src_scripts_utils_cloudinary_.md#extendcloudinaryurl)
* [getCloudinaryUrl](_src_scripts_utils_cloudinary_.md#const-getcloudinaryurl)
* [getDpr](_src_scripts_utils_cloudinary_.md#const-getdpr)
* [getPathFixer](_src_scripts_utils_cloudinary_.md#getpathfixer)
* [isFullPath](_src_scripts_utils_cloudinary_.md#const-isfullpath)

### Object literals

* [HEIGHTS_PROPORTIONS](_src_scripts_utils_cloudinary_.md#const-heights_proportions)
* [LAYOUT_WIDTHS](_src_scripts_utils_cloudinary_.md#const-layout_widths)
* [cloudinaryUtils](_src_scripts_utils_cloudinary_.md#const-cloudinaryutils)

## Variables

### `Const` CLOUDINARY_DOMAIN

• **CLOUDINARY_DOMAIN**: *"res.cloudinary.com"* = "res.cloudinary.com"

Defined in src/scripts/utils/cloudinary.js:40

___

### `Const` CloudinaryCore

• **CloudinaryCore**: *"/Users/vitaly/work/corebine-web-templates-core/node_modules/cloudinary-core/cloudinary-core"* = require('cloudinary-core')

Defined in src/scripts/utils/cloudinary.js:18

___

### `Const` cloudinary

• **cloudinary**: *Cloudinary‹›* = CloudinaryCore.Cloudinary.new({})

Defined in src/scripts/utils/cloudinary.js:39

## Functions

###  extendCloudinaryUrl

▸ **extendCloudinaryUrl**(`path`: any, `config`: any, `fixPath`: any): *any*

Defined in src/scripts/utils/cloudinary.js:75

**Parameters:**

Name | Type |
------ | ------ |
`path` | any |
`config` | any |
`fixPath` | any |

**Returns:** *any*

___

### `Const` getCloudinaryUrl

▸ **getCloudinaryUrl**(`path`: any, `config`: any, `fixPath`: any): *any*

Defined in src/scripts/utils/cloudinary.js:66

**Parameters:**

Name | Type |
------ | ------ |
`path` | any |
`config` | any |
`fixPath` | any |

**Returns:** *any*

___

### `Const` getDpr

▸ **getDpr**(): *number*

Defined in src/scripts/utils/cloudinary.js:34

**Returns:** *number*

___

###  getPathFixer

▸ **getPathFixer**(`oldDir`: any, `newDir`: any): *(Anonymous function)*

Defined in src/scripts/utils/cloudinary.js:46

**Parameters:**

Name | Type |
------ | ------ |
`oldDir` | any |
`newDir` | any |

**Returns:** *(Anonymous function)*

___

### `Const` isFullPath

▸ **isFullPath**(`path`: any): *boolean*

Defined in src/scripts/utils/cloudinary.js:42

**Parameters:**

Name | Type |
------ | ------ |
`path` | any |

**Returns:** *boolean*

## Object literals

### `Const` HEIGHTS_PROPORTIONS

### ▪ **HEIGHTS_PROPORTIONS**: *object*

Defined in src/scripts/utils/cloudinary.js:28

###  flex

• **flex**: *null* = null

Defined in src/scripts/utils/cloudinary.js:31

###  rectangle

• **rectangle**: *number* = 9 / 16

Defined in src/scripts/utils/cloudinary.js:30

###  square

• **square**: *number* = 1

Defined in src/scripts/utils/cloudinary.js:29

___

### `Const` LAYOUT_WIDTHS

### ▪ **LAYOUT_WIDTHS**: *object*

Defined in src/scripts/utils/cloudinary.js:20

###  l

• **l**: *number* = 1280

Defined in src/scripts/utils/cloudinary.js:23

###  m

• **m**: *number* = 768

Defined in src/scripts/utils/cloudinary.js:22

###  max

• **max**: *number* = 1920

Defined in src/scripts/utils/cloudinary.js:25

###  s

• **s**: *number* = 480

Defined in src/scripts/utils/cloudinary.js:21

###  xl

• **xl**: *number* = 1550

Defined in src/scripts/utils/cloudinary.js:24

___

### `Const` cloudinaryUtils

### ▪ **cloudinaryUtils**: *object*

Defined in src/scripts/utils/cloudinary.js:96

###  cloudinaryUrl

▸ **cloudinaryUrl**(`path`: any, `config`: any): *any*

Defined in src/scripts/utils/cloudinary.js:97

**Parameters:**

Name | Type |
------ | ------ |
`path` | any |
`config` | any |

**Returns:** *any*

###  getCloudinaryImagePath

▸ **getCloudinaryImagePath**(`id`: any, `options`: any, `sizeSource`: any): *any*

Defined in src/scripts/utils/cloudinary.js:221

**Parameters:**

Name | Type |
------ | ------ |
`id` | any |
`options` | any |
`sizeSource` | any |

**Returns:** *any*

###  getCloudinaryVideoPath

▸ **getCloudinaryVideoPath**(`id`: any, `options`: any, `sizeSource`: any): *any*

Defined in src/scripts/utils/cloudinary.js:243

**Parameters:**

Name | Type |
------ | ------ |
`id` | any |
`options` | any |
`sizeSource` | any |

**Returns:** *any*

###  getElementSize

▸ **getElementSize**(`$element`: any, `propName`: any): *object*

Defined in src/scripts/utils/cloudinary.js:187

**Parameters:**

Name | Type |
------ | ------ |
`$element` | any |
`propName` | any |

**Returns:** *object*

* **units**: *any* = matches[2]

* **value**: *number* = parseInt(matches[1], 10)

###  getGravityAndCrop

▸ **getGravityAndCrop**(`options`: any): *object*

Defined in src/scripts/utils/cloudinary.js:199

**Parameters:**

Name | Type |
------ | ------ |
`options` | any |

**Returns:** *object*

* **crop**: *any*

* **gravity**: *any*

###  getMaxHeight

▸ **getMaxHeight**(`$element`: any, `id`: any): *number*

Defined in src/scripts/utils/cloudinary.js:170

**Parameters:**

Name | Type |
------ | ------ |
`$element` | any |
`id` | any |

**Returns:** *number*

###  getMaxWidth

▸ **getMaxWidth**(`$element`: any, `id`: any): *number*

Defined in src/scripts/utils/cloudinary.js:147

**Parameters:**

Name | Type |
------ | ------ |
`$element` | any |
`id` | any |

**Returns:** *number*

###  getResponsiveSize

▸ **getResponsiveSize**(`element`: any, `options`: any, `id`: any): *object*

Defined in src/scripts/utils/cloudinary.js:138

**Parameters:**

Name | Type |
------ | ------ |
`element` | any |
`options` | any |
`id` | any |

**Returns:** *object*

* **height**: *any*

* **width**: *any*

###  getSizeByLayout

▸ **getSizeByLayout**(`layout`: any, `aspectRatio`: any): *object*

Defined in src/scripts/utils/cloudinary.js:266

**Parameters:**

Name | Type |
------ | ------ |
`layout` | any |
`aspectRatio` | any |

**Returns:** *object*

* **height**: *number*

* **width**: *any*

###  isCloudinaryUrl

▸ **isCloudinaryUrl**(`url`: any): *boolean*

Defined in src/scripts/utils/cloudinary.js:116

**Parameters:**

Name | Type |
------ | ------ |
`url` | any |

**Returns:** *boolean*

###  pretifyCloudinaryUrl

▸ **pretifyCloudinaryUrl**(`url`: any): *any*

Defined in src/scripts/utils/cloudinary.js:123

**Parameters:**

Name | Type |
------ | ------ |
`url` | any |

**Returns:** *any*
