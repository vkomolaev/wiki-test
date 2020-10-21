[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/image-generic/image-generic"](../modules/_src_markups_components_image_generic_image_generic_.md) › [ImageGeneric](_src_markups_components_image_generic_image_generic_.imagegeneric.md)

# Class: ImageGeneric

## Hierarchy

* PureComponent‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops), [ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)›

  ↳ **ImageGeneric**

## Index

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_image_generic_image_generic_.imagegeneric.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_image_generic_image_generic_.imagegeneric.md#componentdidupdate)
* [componentWillMount](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_image_generic_image_generic_.imagegeneric.md#componentwillunmount)
* [componentWillUpdate](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-componentwillupdate)
* [disableDragging](_src_markups_components_image_generic_image_generic_.imagegeneric.md#disabledragging)
* [getImageSrc](_src_markups_components_image_generic_image_generic_.imagegeneric.md#getimagesrc)
* [getPropValue](_src_markups_components_image_generic_image_generic_.imagegeneric.md#getpropvalue)
* [getSnapshotBeforeUpdate](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-getsnapshotbeforeupdate)
* [getUrl](_src_markups_components_image_generic_image_generic_.imagegeneric.md#geturl)
* [onImageError](_src_markups_components_image_generic_image_generic_.imagegeneric.md#onimageerror)
* [onImageLoaded](_src_markups_components_image_generic_image_generic_.imagegeneric.md#onimageloaded)
* [onPreLoad](_src_markups_components_image_generic_image_generic_.imagegeneric.md#onpreload)
* [render](_src_markups_components_image_generic_image_generic_.imagegeneric.md#render)
* [shouldComponentUpdate](_src_markups_components_image_generic_image_generic_.imagegeneric.md#optional-shouldcomponentupdate)

### Object literals

* [state](_src_markups_components_image_generic_image_generic_.imagegeneric.md#state)
* [defaultProps](_src_markups_components_image_generic_image_generic_.imagegeneric.md#static-defaultprops)

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)›, `nextState`: Readonly‹[ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)› |
`nextState` | Readonly‹[ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)› |
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

Defined in src/markups/components/image-generic/image-generic.tsx:71

**Returns:** *void*

___

###  componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: [ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)): *void*

*Overrides [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidupdate)*

Defined in src/markups/components/image-generic/image-generic.tsx:75

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | [ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops) |

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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)› |
`nextContext` | any |

**Returns:** *void*

___

###  componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Overrides [AccessoLink](_src_markups_components_link_accesso_link_accesso_.accessolink.md).[componentWillUnmount](_src_markups_components_link_accesso_link_accesso_.accessolink.md#optional-componentwillunmount)*

Defined in src/markups/components/image-generic/image-generic.tsx:82

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)›, `nextState`: Readonly‹[ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)› |
`nextState` | Readonly‹[ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)› |
`nextContext` | any |

**Returns:** *void*

___

###  disableDragging

▸ **disableDragging**(): *[DraggableType](../modules/_src_markups_components_image_generic_image_generic_.md#draggabletype)*

Defined in src/markups/components/image-generic/image-generic.tsx:130

**Returns:** *[DraggableType](../modules/_src_markups_components_image_generic_image_generic_.md#draggabletype)*

___

###  getImageSrc

▸ **getImageSrc**(): *string*

Defined in src/markups/components/image-generic/image-generic.tsx:100

**Returns:** *string*

___

###  getPropValue

▸ **getPropValue**(`props`: [ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops), `propName`: string, `defaultVal`: string): *string*

Defined in src/markups/components/image-generic/image-generic.tsx:92

**Parameters:**

Name | Type |
------ | ------ |
`props` | [ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops) |
`propName` | string |
`defaultVal` | string |

**Returns:** *string*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)›, `prevState`: Readonly‹[ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)›): *any | null*

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
`prevProps` | Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)› |
`prevState` | Readonly‹[ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)› |

**Returns:** *any | null*

___

###  getUrl

▸ **getUrl**(`props`: [ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)): *string*

Defined in src/markups/components/image-generic/image-generic.tsx:96

**Parameters:**

Name | Type |
------ | ------ |
`props` | [ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops) |

**Returns:** *string*

___

###  onImageError

▸ **onImageError**(): *void*

Defined in src/markups/components/image-generic/image-generic.tsx:107

**Returns:** *void*

___

###  onImageLoaded

▸ **onImageLoaded**(): *void*

Defined in src/markups/components/image-generic/image-generic.tsx:119

**Returns:** *void*

___

###  onPreLoad

▸ **onPreLoad**(): *void*

Defined in src/markups/components/image-generic/image-generic.tsx:86

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/image-generic/image-generic.tsx:140

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)›, `nextState`: Readonly‹[ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[ImageGenericProps](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericprops)› |
`nextState` | Readonly‹[ImageGenericState](../modules/_src_markups_components_image_generic_image_generic_.md#imagegenericstate)› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

###  state

### ▪ **state**: *object*

Defined in src/markups/components/image-generic/image-generic.tsx:65

###  hasError

• **hasError**: *false* = false

Defined in src/markups/components/image-generic/image-generic.tsx:67

###  isLoaded

• **isLoaded**: *false* = false

Defined in src/markups/components/image-generic/image-generic.tsx:68

###  visible

• **visible**: *boolean* = this.props.visible

Defined in src/markups/components/image-generic/image-generic.tsx:66

___

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/image-generic/image-generic.tsx:56

###  className

• **className**: *string* = ""

Defined in src/markups/components/image-generic/image-generic.tsx:58

###  errorClassName

• **errorClassName**: *string* = "c-image-generic--error"

Defined in src/markups/components/image-generic/image-generic.tsx:60

###  image

• **image**: *object*

Defined in src/markups/components/image-generic/image-generic.tsx:57

#### Type declaration:

###  isExternalSource

• **isExternalSource**: *false* = false

Defined in src/markups/components/image-generic/image-generic.tsx:62

###  successClassName

• **successClassName**: *string* = "c-image-generic--success"

Defined in src/markups/components/image-generic/image-generic.tsx:61

###  visible

• **visible**: *false* = false

Defined in src/markups/components/image-generic/image-generic.tsx:59
