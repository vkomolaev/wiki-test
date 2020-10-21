[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/slider-slide/slider-slide"](../modules/_src_markups_components_slider_slide_slider_slide_.md) › [SliderSlide](_src_markups_components_slider_slide_slider_slide_.sliderslide.md)

# Class: SliderSlide

## Hierarchy

* PureComponent‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops), [SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)›

  ↳ **SliderSlide**

## Index

### Constructors

* [constructor](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#constructor)

### Properties

* [element](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#element)
* [video](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#video)
* [contextType](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#static-contexttype)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-unsafe_componentwillupdate)
* [callToAction](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#calltoaction)
* [closeButton](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#closebutton)
* [componentDidCatch](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-componentdidupdate)
* [componentWillMount](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#componentwillunmount)
* [componentWillUpdate](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-componentwillupdate)
* [descriptionButton](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#descriptionbutton)
* [getSnapshotBeforeUpdate](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-getsnapshotbeforeupdate)
* [isPlaying](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#isplaying)
* [onClose](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#onclose)
* [onFirstShow](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#onfirstshow)
* [onPause](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#onpause)
* [onPlay](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#onplay)
* [onStop](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#onstop)
* [pause](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#pause)
* [play](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#play)
* [render](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#render)
* [renderSlideDescription](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#renderslidedescription)
* [shouldComponentUpdate](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#optional-shouldcomponentupdate)
* [slideMedia](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#slidemedia)
* [stop](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#stop)

### Object literals

* [state](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#state)
* [defaultProps](_src_markups_components_slider_slide_slider_slide_.sliderslide.md#static-defaultprops)

## Constructors

###  constructor

\+ **new SliderSlide**(`props`: [SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)): *[SliderSlide](_src_markups_components_slider_slide_slider_slide_.sliderslide.md)*

Defined in src/markups/components/slider-slide/slider-slide.tsx:105

**Parameters:**

Name | Type |
------ | ------ |
`props` | [SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops) |

**Returns:** *[SliderSlide](_src_markups_components_slider_slide_slider_slide_.sliderslide.md)*

## Properties

###  element

• **element**: *HTMLDivElement*

Defined in src/markups/components/slider-slide/slider-slide.tsx:99

___

###  video

• **video**: *RefObject‹[VideoCorebine](_src_markups_components_video_corebine_video_corebine_.videocorebine.md)›* = React.createRef()

Defined in src/markups/components/slider-slide/slider-slide.tsx:97

___

### `Static` contextType

▪ **contextType**: *Context‹any[]›* = SliderVisibleMediaContext

Defined in src/markups/components/slider-slide/slider-slide.tsx:95

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)›, `nextState`: Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)› |
`nextState` | Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)› |
`nextContext` | any |

**Returns:** *void*

___

###  callToAction

▸ **callToAction**(`slide`: [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype)): *Element‹›*

Defined in src/markups/components/slider-slide/slider-slide.tsx:137

**Parameters:**

Name | Type |
------ | ------ |
`slide` | [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype) |

**Returns:** *Element‹›*

___

###  closeButton

▸ **closeButton**(`slide`: [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype)): *Element‹›*

Defined in src/markups/components/slider-slide/slider-slide.tsx:174

**Parameters:**

Name | Type |
------ | ------ |
`slide` | [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype) |

**Returns:** *Element‹›*

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

Defined in src/markups/components/slider-slide/slider-slide.tsx:112

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)›, `prevState`: Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)›, `snapshot?`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:683

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)› |
`prevState` | Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)› |
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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)› |
`nextContext` | any |

**Returns:** *void*

___

###  componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Overrides [AccessoLink](_src_markups_components_link_accesso_link_accesso_.accessolink.md).[componentWillUnmount](_src_markups_components_link_accesso_link_accesso_.accessolink.md#optional-componentwillunmount)*

Defined in src/markups/components/slider-slide/slider-slide.tsx:116

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)›, `nextState`: Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)› |
`nextState` | Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)› |
`nextContext` | any |

**Returns:** *void*

___

###  descriptionButton

▸ **descriptionButton**(`slide`: [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype)): *Element‹›*

Defined in src/markups/components/slider-slide/slider-slide.tsx:129

**Parameters:**

Name | Type |
------ | ------ |
`slide` | [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype) |

**Returns:** *Element‹›*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)›, `prevState`: Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)›): *any | null*

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
`prevProps` | Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)› |
`prevState` | Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)› |

**Returns:** *any | null*

___

###  isPlaying

▸ **isPlaying**(): *boolean*

Defined in src/markups/components/slider-slide/slider-slide.tsx:245

**Returns:** *boolean*

___

###  onClose

▸ **onClose**(): *void*

Defined in src/markups/components/slider-slide/slider-slide.tsx:170

**Returns:** *void*

___

###  onFirstShow

▸ **onFirstShow**(): *void*

Defined in src/markups/components/slider-slide/slider-slide.tsx:120

**Returns:** *void*

___

###  onPause

▸ **onPause**(): *void*

Defined in src/markups/components/slider-slide/slider-slide.tsx:265

**Returns:** *void*

___

###  onPlay

▸ **onPlay**(): *void*

Defined in src/markups/components/slider-slide/slider-slide.tsx:253

**Returns:** *void*

___

###  onStop

▸ **onStop**(): *void*

Defined in src/markups/components/slider-slide/slider-slide.tsx:280

**Returns:** *void*

___

###  pause

▸ **pause**(): *void*

Defined in src/markups/components/slider-slide/slider-slide.tsx:233

**Returns:** *void*

___

###  play

▸ **play**(`restart?`: boolean): *Promise‹void›*

Defined in src/markups/components/slider-slide/slider-slide.tsx:224

**Parameters:**

Name | Type |
------ | ------ |
`restart?` | boolean |

**Returns:** *Promise‹void›*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/slider-slide/slider-slide.tsx:292

**Returns:** *Element‹›*

___

###  renderSlideDescription

▸ **renderSlideDescription**(): *Element‹›*

Defined in src/markups/components/slider-slide/slider-slide.tsx:323

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)›, `nextState`: Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[SliderSlideProps](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)› |
`nextState` | Readonly‹[SliderSlideState](../modules/_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)› |
`nextContext` | any |

**Returns:** *boolean*

___

###  slideMedia

▸ **slideMedia**(`slide`: [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype)): *Element‹›*

Defined in src/markups/components/slider-slide/slider-slide.tsx:187

**Parameters:**

Name | Type |
------ | ------ |
`slide` | [SlideType](../modules/_src_markups_components_slider_slide_slider_slide_.md#slidetype) |

**Returns:** *Element‹›*

___

###  stop

▸ **stop**(): *void*

Defined in src/markups/components/slider-slide/slider-slide.tsx:239

**Returns:** *void*

## Object literals

###  state

### ▪ **state**: *object*

Defined in src/markups/components/slider-slide/slider-slide.tsx:101

###  isVideoPaused

• **isVideoPaused**: *boolean* = false

Defined in src/markups/components/slider-slide/slider-slide.tsx:103

###  isVideoPlaying

• **isVideoPlaying**: *boolean* = false

Defined in src/markups/components/slider-slide/slider-slide.tsx:102

###  isVideoStopped

• **isVideoStopped**: *boolean* = true

Defined in src/markups/components/slider-slide/slider-slide.tsx:104

___

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/slider-slide/slider-slide.tsx:86

###  className

• **className**: *string* = ""

Defined in src/markups/components/slider-slide/slider-slide.tsx:87

###  cloudinaryOptions

• **cloudinaryOptions**: *object*

Defined in src/markups/components/slider-slide/slider-slide.tsx:92

#### Type declaration:

###  isMediaControlled

• **isMediaControlled**: *false* = false

Defined in src/markups/components/slider-slide/slider-slide.tsx:91

###  mediaClassName

• **mediaClassName**: *string* = ""

Defined in src/markups/components/slider-slide/slider-slide.tsx:88

###  renderDescription

• **renderDescription**: *true* = true

Defined in src/markups/components/slider-slide/slider-slide.tsx:89

###  onClick

▸ **onClick**(): *void*

Defined in src/markups/components/slider-slide/slider-slide.tsx:90

**Returns:** *void*
