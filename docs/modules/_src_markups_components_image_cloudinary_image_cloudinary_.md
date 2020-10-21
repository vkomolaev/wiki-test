[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/image-cloudinary/image-cloudinary"](_src_markups_components_image_cloudinary_image_cloudinary_.md)

# Module: "src/markups/components/image-cloudinary/image-cloudinary"

## Index

### Classes

* [ImageCloudinary](../classes/_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md)

### Type aliases

* [CloudinaryOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#cloudinaryoptions)
* [ImageAspectRatio](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageaspectratio)
* [ImageCloudinaryProps](_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)
* [ImageCloudinaryState](_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)
* [ImageCloudinaryType](_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarytype)
* [ImageFormat](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageformat)
* [ImageOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptions)
* [ImageOptionsScreen](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptionsscreen)
* [ImageOptionsScreens](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptionsscreens)

### Variables

* [ANIMATED_SET](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-animated_set)
* [EMPTY_SRC](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-empty_src)
* [REGULAR_SET](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-regular_set)
* [TRANSPARENT_SET](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-transparent_set)
* [getImageSrc](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-getimagesrc)

### Functions

* [getResolutions](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-getresolutions)
* [getScreenSize](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-getscreensize)
* [getSupportedFormats](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-getsupportedformats)
* [hydrate](_src_markups_components_image_cloudinary_image_cloudinary_.md#hydrate)
* [render](_src_markups_components_image_cloudinary_image_cloudinary_.md#render)

### Object literals

* [MAP_TYPES](_src_markups_components_image_cloudinary_image_cloudinary_.md#const-map_types)

## Type aliases

###  CloudinaryOptions

Ƭ **CloudinaryOptions**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:32

#### Type declaration:

* **background**? : *string*

* **crop**? : *string*

* **dpr**? : *number*

* **fetch_format**? : *string*

* **flags**? : *string*

* **focus**? : *string*

___

###  ImageAspectRatio

Ƭ **ImageAspectRatio**: *"square" | "rectangle" | "flex"*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:20

___

###  ImageCloudinaryProps

Ƭ **ImageCloudinaryProps**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:54

#### Type declaration:

* **alt**? : *string*

* **className**? : *string*

* **cloudinaryOptions**? : *[CloudinaryOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#cloudinaryoptions)*

* **disableLazyLoading**? : *boolean*

* **errorClassName**? : *string*

* **image**? : *[ImageCloudinaryType](_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarytype)*

* **onLoaded**(): *function*

  * (): *void*

* **options**? : *[ImageOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptions)*

* **source**? : *string*

* **successClassName**? : *string*

* **visible**? : *boolean*

___

###  ImageCloudinaryState

Ƭ **ImageCloudinaryState**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:81

#### Type declaration:

* **error**: *boolean*

* **format**: *[ImageFormat](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageformat)*

* **loaded**: *boolean*

* **screenSize**: *[ScreenShortName](_src_scripts_window_size_manager_.md#screenshortname)*

* **visible**: *boolean*

___

###  ImageCloudinaryType

Ƭ **ImageCloudinaryType**: *object & [ImageType](_src_markups_components_image_image_.md#imagetype)*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:47

___

###  ImageFormat

Ƭ **ImageFormat**: *"wdp" | "apng" | "jpg" | "png" | "jp2"*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:79

___

###  ImageOptions

Ƭ **ImageOptions**: *object & [ImageOptionsScreens](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptionsscreens)*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:27

___

###  ImageOptionsScreen

Ƭ **ImageOptionsScreen**: *"screen-all" | "screen-s" | "screen-m" | "screen-l" | "screen-xl" | "screen-max"*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:21

___

###  ImageOptionsScreens

Ƭ **ImageOptionsScreens**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:23

#### Type declaration:

## Variables

### `Const` ANIMATED_SET

• **ANIMATED_SET**: *string[]* = ['webp', 'apng']

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:93

___

### `Const` EMPTY_SRC

• **EMPTY_SRC**: *string* = 'data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABAQMAAAAl21bKAAAAA1BMVEUAAACnej3aAAAAAXRSTl' +
    'MAQObYZgAAAApJREFUCNdjYAAAAAIAAeIhvDMAAAAASUVORK5CYII='

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:105

___

### `Const` REGULAR_SET

• **REGULAR_SET**: *string[]* = ['jp2', 'webp', 'wdp', 'jpg']

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:89

___

### `Const` TRANSPARENT_SET

• **TRANSPARENT_SET**: *string[]* = ['jp2', 'webp', 'wdp', 'png']

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:91

___

### `Const` getImageSrc

• **getImageSrc**: *(Anonymous function) & MemoizedFunction* = _.memoize(
    (id, params, {layout, aspectRatio}) => cloudinaryUtils.getCloudinaryImagePath(id, params, {layout, aspectRatio}),
    (id, params, {layout, aspectRatio}) => [id, layout, aspectRatio, ...Object.values(params)].join('_')
)

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:350

## Functions

### `Const` getResolutions

▸ **getResolutions**(`options`: [ImageOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptions)): *any*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:333

**Parameters:**

Name | Type |
------ | ------ |
`options` | [ImageOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptions) |

**Returns:** *any*

___

### `Const` getScreenSize

▸ **getScreenSize**(`source`: [ImageOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptions), `sizeKey`: [ScreenShortName](_src_scripts_window_size_manager_.md#screenshortname)): *[ScreenShortName](_src_scripts_window_size_manager_.md#screenshortname)*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:346

**Parameters:**

Name | Type |
------ | ------ |
`source` | [ImageOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#imageoptions) |
`sizeKey` | [ScreenShortName](_src_scripts_window_size_manager_.md#screenshortname) |

**Returns:** *[ScreenShortName](_src_scripts_window_size_manager_.md#screenshortname)*

___

### `Const` getSupportedFormats

▸ **getSupportedFormats**(`__namedParameters`: object): *string[]*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:321

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type |
------ | ------ |
`animated` | boolean |
`transparent` | boolean |

**Returns:** *string[]*

___

###  hydrate

▸ **hydrate**(`props`: [ImageCloudinaryProps](_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops), `targetElement`: HTMLElement, `callback`: function): *void*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:313

**Parameters:**

▪ **props**: *[ImageCloudinaryProps](_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)*

▪ **targetElement**: *HTMLElement*

▪ **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

###  render

▸ **render**(`props`: [ImageCloudinaryProps](_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops), `targetElement`: HTMLElement): *void*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:306

**Parameters:**

Name | Type |
------ | ------ |
`props` | [ImageCloudinaryProps](_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops) |
`targetElement` | HTMLElement |

**Returns:** *void*

## Object literals

### `Const` MAP_TYPES

### ▪ **MAP_TYPES**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:95

###  apng

• **apng**: *string* = "png"

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:99

###  jp2

• **jp2**: *string* = "jp2"

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:102

###  jpg

• **jpg**: *string* = "jpeg"

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:101

###  png

• **png**: *string* = "png"

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:100

###  wdp

• **wdp**: *string* = "vnd.ms-photo"

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:98
