[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/gallery/gallery"](../modules/_src_markups_components_gallery_gallery_.md) › [Gallery](_src_markups_components_gallery_gallery_.gallery.md)

# Class: Gallery

## Hierarchy

* PureComponent‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops), [GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)›

  ↳ **Gallery**

## Index

### Properties

* [galleryRef](_src_markups_components_gallery_gallery_.gallery.md#galleryref)
* [headCarouselRef](_src_markups_components_gallery_gallery_.gallery.md#headcarouselref)
* [thumbsCarouselRef](_src_markups_components_gallery_gallery_.gallery.md#thumbscarouselref)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_gallery_gallery_.gallery.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_gallery_gallery_.gallery.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_gallery_gallery_.gallery.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_gallery_gallery_.gallery.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_gallery_gallery_.gallery.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_gallery_gallery_.gallery.md#optional-componentdidupdate)
* [componentWillMount](_src_markups_components_gallery_gallery_.gallery.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_gallery_gallery_.gallery.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_gallery_gallery_.gallery.md#componentwillunmount)
* [componentWillUpdate](_src_markups_components_gallery_gallery_.gallery.md#optional-componentwillupdate)
* [getSnapshotBeforeUpdate](_src_markups_components_gallery_gallery_.gallery.md#optional-getsnapshotbeforeupdate)
* [onFirstShow](_src_markups_components_gallery_gallery_.gallery.md#onfirstshow)
* [onLayout](_src_markups_components_gallery_gallery_.gallery.md#onlayout)
* [openModal](_src_markups_components_gallery_gallery_.gallery.md#openmodal)
* [render](_src_markups_components_gallery_gallery_.gallery.md#render)
* [renderGalleryActiveSlide](_src_markups_components_gallery_gallery_.gallery.md#rendergalleryactiveslide)
* [renderGalleryHead](_src_markups_components_gallery_gallery_.gallery.md#rendergalleryhead)
* [renderGalleryThumbs](_src_markups_components_gallery_gallery_.gallery.md#rendergallerythumbs)
* [shouldComponentUpdate](_src_markups_components_gallery_gallery_.gallery.md#optional-shouldcomponentupdate)

### Object literals

* [THUMBS_PER_SCREEN](_src_markups_components_gallery_gallery_.gallery.md#thumbs_per_screen)
* [state](_src_markups_components_gallery_gallery_.gallery.md#state)

## Properties

###  galleryRef

• **galleryRef**: *RefObject‹HTMLDivElement›* = React.createRef()

Defined in src/markups/components/gallery/gallery.tsx:42

___

###  headCarouselRef

• **headCarouselRef**: *RefObject‹[NukaApi](../modules/_src_markups_components_slider_slider_.md#const-nukaapi)›* = React.createRef()

Defined in src/markups/components/gallery/gallery.tsx:46

___

###  thumbsCarouselRef

• **thumbsCarouselRef**: *RefObject‹[NukaApi](../modules/_src_markups_components_slider_slider_.md#const-nukaapi)›* = React.createRef()

Defined in src/markups/components/gallery/gallery.tsx:44

## Methods

### `Optional` UNSAFE_componentWillMount

▸ **UNSAFE_componentWillMount**(): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[UNSAFE_componentWillMount](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-unsafe_componentwillmount)*

Defined in node_modules/@types/react/index.d.ts:712

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillReceiveProps

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)›, `nextContext`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[UNSAFE_componentWillReceiveProps](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-unsafe_componentwillreceiveprops)*

Defined in node_modules/@types/react/index.d.ts:744

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)›, `nextState`: Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)›, `nextContext`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[UNSAFE_componentWillUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-unsafe_componentwillupdate)*

Defined in node_modules/@types/react/index.d.ts:772

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)› |
`nextState` | Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` componentDidCatch

▸ **componentDidCatch**(`error`: Error, `errorInfo`: ErrorInfo): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidCatch](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidcatch)*

Defined in node_modules/@types/react/index.d.ts:641

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

**Parameters:**

Name | Type |
------ | ------ |
`error` | Error |
`errorInfo` | ErrorInfo |

**Returns:** *void*

___

###  componentDidMount

▸ **componentDidMount**(): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidMount](_src_markups_components_tags_tags_.tags.md#optional-componentdidmount)*

Defined in src/markups/components/gallery/gallery.tsx:48

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)›, `prevState`: Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)›, `snapshot?`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:683

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)› |
`prevState` | Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)› |
`snapshot?` | any |

**Returns:** *void*

___

### `Optional` componentWillMount

▸ **componentWillMount**(): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentWillMount](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentwillmount)*

Defined in node_modules/@types/react/index.d.ts:698

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Returns:** *void*

___

### `Optional` componentWillReceiveProps

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)›, `nextContext`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentWillReceiveProps](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentwillreceiveprops)*

Defined in node_modules/@types/react/index.d.ts:727

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)› |
`nextContext` | any |

**Returns:** *void*

___

###  componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Overrides [AccessoLink](_src_markups_components_link_accesso_link_accesso_.accessolink.md).[componentWillUnmount](_src_markups_components_link_accesso_link_accesso_.accessolink.md#optional-componentwillunmount)*

Defined in src/markups/components/gallery/gallery.tsx:52

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)›, `nextState`: Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)›, `nextContext`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentWillUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentwillupdate)*

Defined in node_modules/@types/react/index.d.ts:757

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)› |
`nextState` | Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)›, `prevState`: Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)›): *any | null*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[getSnapshotBeforeUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-getsnapshotbeforeupdate)*

Defined in node_modules/@types/react/index.d.ts:677

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)› |
`prevState` | Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)› |

**Returns:** *any | null*

___

###  onFirstShow

▸ **onFirstShow**(): *void*

Defined in src/markups/components/gallery/gallery.tsx:56

**Returns:** *void*

___

###  onLayout

▸ **onLayout**(`layout`: string): *void*

Defined in src/markups/components/gallery/gallery.tsx:62

**Parameters:**

Name | Type |
------ | ------ |
`layout` | string |

**Returns:** *void*

___

###  openModal

▸ **openModal**(): *void*

Defined in src/markups/components/gallery/gallery.tsx:68

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/gallery/gallery.tsx:85

**Returns:** *Element‹›*

___

###  renderGalleryActiveSlide

▸ **renderGalleryActiveSlide**(): *Element‹›*

Defined in src/markups/components/gallery/gallery.tsx:143

**Returns:** *Element‹›*

___

###  renderGalleryHead

▸ **renderGalleryHead**(): *Element‹›*

Defined in src/markups/components/gallery/gallery.tsx:97

**Returns:** *Element‹›*

___

###  renderGalleryThumbs

▸ **renderGalleryThumbs**(): *Element‹›*

Defined in src/markups/components/gallery/gallery.tsx:112

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)›, `nextState`: Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)›, `nextContext`: any): *boolean*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[shouldComponentUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-shouldcomponentupdate)*

Defined in node_modules/@types/react/index.d.ts:631

Called to determine whether the change in props and state should trigger a re-render.

`Component` always returns true.
`PureComponent` implements a shallow comparison on props and state and returns true if any
props or states have changed.

If false is returned, `Component#render`, `componentWillUpdate`
and `componentDidUpdate` will not be called.

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[GalleryProps](../modules/_src_markups_components_gallery_gallery_.md#galleryprops)› |
`nextState` | Readonly‹[GalleryState](../modules/_src_markups_components_gallery_gallery_.md#gallerystate)› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

###  THUMBS_PER_SCREEN

### ▪ **THUMBS_PER_SCREEN**: *object*

Defined in src/markups/components/gallery/gallery.tsx:29

###  extra-large

• **extra-large**: *number* = 6

Defined in src/markups/components/gallery/gallery.tsx:33

###  large

• **large**: *number* = 6

Defined in src/markups/components/gallery/gallery.tsx:32

###  max

• **max**: *number* = 6

Defined in src/markups/components/gallery/gallery.tsx:34

###  medium

• **medium**: *number* = 5

Defined in src/markups/components/gallery/gallery.tsx:31

###  small

• **small**: *number* = 4

Defined in src/markups/components/gallery/gallery.tsx:30

___

###  state

### ▪ **state**: *object*

Defined in src/markups/components/gallery/gallery.tsx:37

###  slideIndex

• **slideIndex**: *number* = 0

Defined in src/markups/components/gallery/gallery.tsx:38

###  thumbsCount

• **thumbsCount**: *number* = 1

Defined in src/markups/components/gallery/gallery.tsx:39
