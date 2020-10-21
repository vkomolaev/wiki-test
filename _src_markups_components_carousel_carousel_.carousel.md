[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/carousel/carousel"](../modules/_src_markups_components_carousel_carousel_.md) › [Carousel](_src_markups_components_carousel_carousel_.carousel.md)

# Class: Carousel

## Hierarchy

* PureComponent‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops), [CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)›

  ↳ **Carousel**

## Index

### Constructors

* [constructor](_src_markups_components_carousel_carousel_.carousel.md#constructor)

### Properties

* [_autoPlayTimeout](_src_markups_components_carousel_carousel_.carousel.md#_autoplaytimeout)
* [_blockAutoRotate](_src_markups_components_carousel_carousel_.carousel.md#_blockautorotate)
* [carousel](_src_markups_components_carousel_carousel_.carousel.md#protected-carousel)
* [carouselSlide0](_src_markups_components_carousel_carousel_.carousel.md#protected-carouselslide0)
* [isFirstModule](_src_markups_components_carousel_carousel_.carousel.md#protected-isfirstmodule)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_carousel_carousel_.carousel.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_carousel_carousel_.carousel.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_carousel_carousel_.carousel.md#optional-unsafe_componentwillupdate)
* [beforeSlideHandler](_src_markups_components_carousel_carousel_.carousel.md#beforeslidehandler)
* [blockAutoRotate](_src_markups_components_carousel_carousel_.carousel.md#blockautorotate)
* [componentDidCatch](_src_markups_components_carousel_carousel_.carousel.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_carousel_carousel_.carousel.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_carousel_carousel_.carousel.md#optional-componentdidupdate)
* [componentWillMount](_src_markups_components_carousel_carousel_.carousel.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_carousel_carousel_.carousel.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_carousel_carousel_.carousel.md#componentwillunmount)
* [componentWillUpdate](_src_markups_components_carousel_carousel_.carousel.md#optional-componentwillupdate)
* [getChildrenWithProps](_src_markups_components_carousel_carousel_.carousel.md#getchildrenwithprops)
* [getExtraClasses](_src_markups_components_carousel_carousel_.carousel.md#getextraclasses)
* [getSnapshotBeforeUpdate](_src_markups_components_carousel_carousel_.carousel.md#optional-getsnapshotbeforeupdate)
* [onPreLoad](_src_markups_components_carousel_carousel_.carousel.md#onpreload)
* [onVideoPause](_src_markups_components_carousel_carousel_.carousel.md#onvideopause)
* [onVideoPlay](_src_markups_components_carousel_carousel_.carousel.md#onvideoplay)
* [onVideoStop](_src_markups_components_carousel_carousel_.carousel.md#onvideostop)
* [render](_src_markups_components_carousel_carousel_.carousel.md#render)
* [shouldComponentUpdate](_src_markups_components_carousel_carousel_.carousel.md#optional-shouldcomponentupdate)
* [startAutoRotate](_src_markups_components_carousel_carousel_.carousel.md#startautorotate)
* [stopAutoRotate](_src_markups_components_carousel_carousel_.carousel.md#stopautorotate)
* [unblockAutoRotate](_src_markups_components_carousel_carousel_.carousel.md#unblockautorotate)

### Object literals

* [state](_src_markups_components_carousel_carousel_.carousel.md#state)
* [defaultProps](_src_markups_components_carousel_carousel_.carousel.md#static-defaultprops)

## Constructors

###  constructor

\+ **new Carousel**(`props`: [CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)): *[Carousel](_src_markups_components_carousel_carousel_.carousel.md)*

Defined in src/markups/components/carousel/carousel.tsx:75

**Parameters:**

Name | Type |
------ | ------ |
`props` | [CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops) |

**Returns:** *[Carousel](_src_markups_components_carousel_carousel_.carousel.md)*

## Properties

###  _autoPlayTimeout

• **_autoPlayTimeout**: *number* = null

Defined in src/markups/components/carousel/carousel.tsx:58

___

###  _blockAutoRotate

• **_blockAutoRotate**: *boolean* = false

Defined in src/markups/components/carousel/carousel.tsx:60

___

### `Protected` carousel

• **carousel**: *RefObject‹[NukaApi](../modules/_src_markups_components_slider_slider_.md#const-nukaapi)›* = React.createRef()

Defined in src/markups/components/carousel/carousel.tsx:73

___

### `Protected` carouselSlide0

• **carouselSlide0**: *[SliderSlide](_src_markups_components_slider_slide_slider_slide_.sliderslide.md)*

Defined in src/markups/components/carousel/carousel.tsx:75

___

### `Protected` isFirstModule

• **isFirstModule**: *boolean* = false

Defined in src/markups/components/carousel/carousel.tsx:71

Flag that allows to determine whether the module will be visible

## Methods

### `Optional` UNSAFE_componentWillMount

▸ **UNSAFE_componentWillMount**(): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[UNSAFE_componentWillMount](_src_markups_components_tags_tags_.tags.md#optional-unsafe_componentwillmount)*

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)›, `nextContext`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[UNSAFE_componentWillReceiveProps](_src_markups_components_tags_tags_.tags.md#optional-unsafe_componentwillreceiveprops)*

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
`nextProps` | Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)›, `nextState`: Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)›, `nextContext`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[UNSAFE_componentWillUpdate](_src_markups_components_tags_tags_.tags.md#optional-unsafe_componentwillupdate)*

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
`nextProps` | Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)› |
`nextState` | Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)› |
`nextContext` | any |

**Returns:** *void*

___

###  beforeSlideHandler

▸ **beforeSlideHandler**(`prevSlide`: number, `nextSlide`: number): *void*

Defined in src/markups/components/carousel/carousel.tsx:164

**Parameters:**

Name | Type |
------ | ------ |
`prevSlide` | number |
`nextSlide` | number |

**Returns:** *void*

___

###  blockAutoRotate

▸ **blockAutoRotate**(): *void*

Defined in src/markups/components/carousel/carousel.tsx:241

**Returns:** *void*

___

### `Optional` componentDidCatch

▸ **componentDidCatch**(`error`: [Error](_src_markups_modules_error_error_.error.md), `errorInfo`: ErrorInfo): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidCatch](_src_markups_components_tags_tags_.tags.md#optional-componentdidcatch)*

Defined in node_modules/@types/react/index.d.ts:641

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

**Parameters:**

Name | Type |
------ | ------ |
`error` | [Error](_src_markups_modules_error_error_.error.md) |
`errorInfo` | ErrorInfo |

**Returns:** *void*

___

###  componentDidMount

▸ **componentDidMount**(): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidMount](_src_markups_components_tags_tags_.tags.md#optional-componentdidmount)*

Defined in src/markups/components/carousel/carousel.tsx:82

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)›, `prevState`: Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)›, `snapshot?`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:683

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)› |
`prevState` | Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)› |
`snapshot?` | any |

**Returns:** *void*

___

### `Optional` componentWillMount

▸ **componentWillMount**(): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillMount](_src_markups_components_tags_tags_.tags.md#optional-componentwillmount)*

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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)›, `nextContext`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillReceiveProps](_src_markups_components_tags_tags_.tags.md#optional-componentwillreceiveprops)*

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
`nextProps` | Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)› |
`nextContext` | any |

**Returns:** *void*

___

###  componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillUnmount](_src_markups_components_tags_tags_.tags.md#optional-componentwillunmount)*

Defined in src/markups/components/carousel/carousel.tsx:94

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)›, `nextState`: Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)›, `nextContext`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentwillupdate)*

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
`nextProps` | Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)› |
`nextState` | Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)› |
`nextContext` | any |

**Returns:** *void*

___

###  getChildrenWithProps

▸ **getChildrenWithProps**(`isArray`: boolean, `styleClass`: string): *ReactNode*

Defined in src/markups/components/carousel/carousel.tsx:113

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`isArray` | boolean | false |
`styleClass` | string | "" |

**Returns:** *ReactNode*

___

###  getExtraClasses

▸ **getExtraClasses**(`slides`: [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype)[]): *string[]*

Defined in src/markups/components/carousel/carousel.tsx:102

**Parameters:**

Name | Type |
------ | ------ |
`slides` | [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype)[] |

**Returns:** *string[]*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)›, `prevState`: Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)›): *any | null*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[getSnapshotBeforeUpdate](_src_markups_components_tags_tags_.tags.md#optional-getsnapshotbeforeupdate)*

Defined in node_modules/@types/react/index.d.ts:677

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)› |
`prevState` | Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)› |

**Returns:** *any | null*

___

###  onPreLoad

▸ **onPreLoad**(): *void*

Defined in src/markups/components/carousel/carousel.tsx:98

**Returns:** *void*

___

###  onVideoPause

▸ **onVideoPause**(): *void*

Defined in src/markups/components/carousel/carousel.tsx:148

**Returns:** *void*

___

###  onVideoPlay

▸ **onVideoPlay**(): *void*

Defined in src/markups/components/carousel/carousel.tsx:140

**Returns:** *void*

___

###  onVideoStop

▸ **onVideoStop**(`autoPlayFinished`: boolean): *void*

Defined in src/markups/components/carousel/carousel.tsx:156

**Parameters:**

Name | Type |
------ | ------ |
`autoPlayFinished` | boolean |

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/carousel/carousel.tsx:179

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)›, `nextState`: Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)›, `nextContext`: any): *boolean*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[shouldComponentUpdate](_src_markups_components_tags_tags_.tags.md#optional-shouldcomponentupdate)*

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
`nextProps` | Readonly‹[CarouselProps](../modules/_src_markups_components_carousel_carousel_.md#carouselprops)› |
`nextState` | Readonly‹[CarouselState](../modules/_src_markups_components_carousel_carousel_.md#carouselstate)› |
`nextContext` | any |

**Returns:** *boolean*

___

###  startAutoRotate

▸ **startAutoRotate**(`instant?`: boolean): *void*

Defined in src/markups/components/carousel/carousel.tsx:224

**Parameters:**

Name | Type |
------ | ------ |
`instant?` | boolean |

**Returns:** *void*

___

###  stopAutoRotate

▸ **stopAutoRotate**(): *this*

Defined in src/markups/components/carousel/carousel.tsx:235

**Returns:** *this*

___

###  unblockAutoRotate

▸ **unblockAutoRotate**(): *void*

Defined in src/markups/components/carousel/carousel.tsx:246

**Returns:** *void*

## Object literals

###  state

### ▪ **state**: *object*

Defined in src/markups/components/carousel/carousel.tsx:62

###  dragging

• **dragging**: *true* = true

Defined in src/markups/components/carousel/carousel.tsx:67

###  isVideoPaused

• **isVideoPaused**: *false* = false

Defined in src/markups/components/carousel/carousel.tsx:65

###  isVideoPlaying

• **isVideoPlaying**: *false* = false

Defined in src/markups/components/carousel/carousel.tsx:64

###  slideIndex

• **slideIndex**: *number* = 0

Defined in src/markups/components/carousel/carousel.tsx:63

###  visible

• **visible**: *false* = false

Defined in src/markups/components/carousel/carousel.tsx:66

___

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/carousel/carousel.tsx:52

###  autoRotate

• **autoRotate**: *true* = true

Defined in src/markups/components/carousel/carousel.tsx:54

###  content

• **content**: *undefined[]* = []

Defined in src/markups/components/carousel/carousel.tsx:53

###  rotateInterval

• **rotateInterval**: *number* = 5000

Defined in src/markups/components/carousel/carousel.tsx:55
