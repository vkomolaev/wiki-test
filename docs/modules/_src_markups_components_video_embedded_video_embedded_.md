[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/video-embedded/video-embedded"](_src_markups_components_video_embedded_video_embedded_.md)

# Module: "src/markups/components/video-embedded/video-embedded"

## Index

### Classes

* [VideoEmbedded](../classes/_src_markups_components_video_embedded_video_embedded_.videoembedded.md)

### Type aliases

* [VideoEmbeddedProps](_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)
* [VideoEmbeddedState](_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)

### Functions

* [getYoutubeCode](_src_markups_components_video_embedded_video_embedded_.md#getyoutubecode)
* [hydrate](_src_markups_components_video_embedded_video_embedded_.md#hydrate)
* [render](_src_markups_components_video_embedded_video_embedded_.md#render)

## Type aliases

###  VideoEmbeddedProps

Ƭ **VideoEmbeddedProps**: *object*

Defined in src/markups/components/video-embedded/video-embedded.tsx:21

#### Type declaration:

* **className**? : *string*

* **errorClassName**? : *string*

* **hidden**? : *boolean*

* **onPause**(): *function*

  * (): *void*

* **onPlay**(): *function*

  * (): *void*

* **onStop**(): *function*

  * (): *void*

* **successClassName**? : *string*

* **video**? : *[VideoProps](_src_markups_components_video_corebine_video_corebine_.md#videoprops)*

___

###  VideoEmbeddedState

Ƭ **VideoEmbeddedState**: *object*

Defined in src/markups/components/video-embedded/video-embedded.tsx:40

#### Type declaration:

* **escapedSource**? : *string*

* **isYoutubeVideo**? : *boolean*

* **source**? : *string*

* **supportsApi**? : *boolean*

* **videoUrl**? : *string*

## Functions

###  getYoutubeCode

▸ **getYoutubeCode**(`code`: string): *object*

Defined in src/markups/components/video-embedded/video-embedded.tsx:48

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`code` | string | "" |

**Returns:** *object*

* **isYoutubeVideo**: *boolean*

* **source**: *string*

* **videoUrl**: *string*

___

###  hydrate

▸ **hydrate**(`props`: [VideoEmbeddedProps](_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops), `targetElement`: HTMLElement, `callback`: function): *void*

Defined in src/markups/components/video-embedded/video-embedded.tsx:207

**Parameters:**

▪ **props**: *[VideoEmbeddedProps](_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)*

▪ **targetElement**: *HTMLElement*

▪ **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

###  render

▸ **render**(`props`: [VideoEmbeddedProps](_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops), `targetElement`: HTMLElement): *void*

Defined in src/markups/components/video-embedded/video-embedded.tsx:200

**Parameters:**

Name | Type |
------ | ------ |
`props` | [VideoEmbeddedProps](_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops) |
`targetElement` | HTMLElement |

**Returns:** *void*
