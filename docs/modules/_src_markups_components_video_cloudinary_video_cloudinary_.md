[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/video-cloudinary/video-cloudinary"](_src_markups_components_video_cloudinary_video_cloudinary_.md)

# Module: "src/markups/components/video-cloudinary/video-cloudinary"

## Index

### Classes

* [VideoCloudinary](../classes/_src_markups_components_video_cloudinary_video_cloudinary_.videocloudinary.md)

### Type aliases

* [VideoCloudinaryProps](_src_markups_components_video_cloudinary_video_cloudinary_.md#videocloudinaryprops)
* [VideoCloudinaryState](_src_markups_components_video_cloudinary_video_cloudinary_.md#videocloudinarystate)

### Variables

* [getVideoSrc](_src_markups_components_video_cloudinary_video_cloudinary_.md#const-getvideosrc)

### Functions

* [hydrate](_src_markups_components_video_cloudinary_video_cloudinary_.md#hydrate)
* [render](_src_markups_components_video_cloudinary_video_cloudinary_.md#render)

## Type aliases

###  VideoCloudinaryProps

Ƭ **VideoCloudinaryProps**: *object & [VideoProps](_src_markups_components_video_corebine_video_corebine_.md#videoprops)*

Defined in src/markups/components/video-cloudinary/video-cloudinary.tsx:22

___

###  VideoCloudinaryState

Ƭ **VideoCloudinaryState**: *object*

Defined in src/markups/components/video-cloudinary/video-cloudinary.tsx:53

#### Type declaration:

* **autoPlay**? : *boolean*

* **hasLoadingError**? : *boolean*

* **isOnScreen**? : *boolean*

* **loaded**? : *boolean*

* **screenSize**? : *[ScreenShortName](_src_scripts_window_size_manager_.md#screenshortname)*

* **src**? : *string*

* **volume**? : *number*

## Variables

### `Const` getVideoSrc

• **getVideoSrc**: *(Anonymous function) & MemoizedFunction* = _.memoize(
    (id, options, {layout, aspectRatio}) => cloudinaryUtils.getCloudinaryVideoPath(
        id, options, {layout, aspectRatio}
    ),
    (id, options, {layout, aspectRatio}) => [id, layout, options.gravity, aspectRatio].join('_')
)

Defined in src/markups/components/video-cloudinary/video-cloudinary.tsx:386

## Functions

###  hydrate

▸ **hydrate**(`props`: [VideoCloudinaryProps](_src_markups_components_video_cloudinary_video_cloudinary_.md#videocloudinaryprops), `targetElement`: HTMLElement, `callback`: function): *void*

Defined in src/markups/components/video-cloudinary/video-cloudinary.tsx:378

**Parameters:**

▪ **props**: *[VideoCloudinaryProps](_src_markups_components_video_cloudinary_video_cloudinary_.md#videocloudinaryprops)*

▪ **targetElement**: *HTMLElement*

▪ **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

###  render

▸ **render**(`props`: [VideoCloudinaryProps](_src_markups_components_video_cloudinary_video_cloudinary_.md#videocloudinaryprops), `targetElement`: HTMLElement): *void*

Defined in src/markups/components/video-cloudinary/video-cloudinary.tsx:371

**Parameters:**

Name | Type |
------ | ------ |
`props` | [VideoCloudinaryProps](_src_markups_components_video_cloudinary_video_cloudinary_.md#videocloudinaryprops) |
`targetElement` | HTMLElement |

**Returns:** *void*
