[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/image-cloudinary/image-cloudinary"](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md) › [ImageCloudinary](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md)

# Class: ImageCloudinary

## Hierarchy

* Component‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops), [ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›

  ↳ **ImageCloudinary**

## Index

### Constructors

* [constructor](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#constructor)

### Properties

* [context](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#context)
* [isUnmounted](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#protected-isunmounted)
* [props](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#readonly-props)
* [refs](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#refs)
* [state](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#state)
* [contextType](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#static-optional-contexttype)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-componentdidupdate)
* [componentWillMount](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#componentwillunmount)
* [componentWillUpdate](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-componentwillupdate)
* [forceUpdate](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#forceupdate)
* [getImageSrc](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#getimagesrc)
* [getSnapshotBeforeUpdate](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-getsnapshotbeforeupdate)
* [isAnimated](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#isanimated)
* [onImageError](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#onimageerror)
* [onImageLoaded](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#onimageloaded)
* [onLayout](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#onlayout)
* [onPreLoad](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#onpreload)
* [render](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#render)
* [renderCloudinaryImage](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#rendercloudinaryimage)
* [renderCloudinarySource](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#rendercloudinarysource)
* [setState](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#setstate)
* [shouldComponentUpdate](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#optional-shouldcomponentupdate)
* [shouldLoadImage](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#shouldloadimage)
* [getDerivedStateFromProps](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#static-getderivedstatefromprops)

### Object literals

* [default](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md#static-default)

## Constructors

###  constructor

\+ **new ImageCloudinary**(`props`: [ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)): *[ImageCloudinary](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md)*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[constructor](_src_markups_components_tags_tags_.tags.md#constructor)*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:119

**Parameters:**

Name | Type |
------ | ------ |
`props` | [ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops) |

**Returns:** *[ImageCloudinary](_src_markups_components_image_cloudinary_image_cloudinary_.imagecloudinary.md)*

## Properties

###  context

• **context**: *any*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[context](_src_markups_components_tags_tags_.tags.md#context)*

Defined in node_modules/@types/react/index.d.ts:476

If using the new style context, re-declare this in your class to be the
`React.ContextType` of your `static contextType`.
Should be used with type annotation or static contextType.

```ts
static contextType = MyContext
// For TS pre-3.7:
context!: React.ContextType<typeof MyContext>
// For TS 3.7 and above:
declare context: React.ContextType<typeof MyContext>
```

**`see`** https://reactjs.org/docs/context.html

___

### `Protected` isUnmounted

• **isUnmounted**: *boolean*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:133

___

### `Readonly` props

• **props**: *Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)› & Readonly‹object›*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[props](_src_markups_components_tags_tags_.tags.md#readonly-props)*

Defined in node_modules/@types/react/index.d.ts:501

___

###  refs

• **refs**: *object*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[refs](_src_markups_components_tags_tags_.tags.md#refs)*

Defined in node_modules/@types/react/index.d.ts:507

**`deprecated`** 
https://reactjs.org/docs/refs-and-the-dom.html#legacy-api-string-refs

#### Type declaration:

* \[ **key**: *string*\]: ReactInstance

___

###  state

• **state**: *Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[state](_src_markups_components_tags_tags_.tags.md#state)*

Defined in node_modules/@types/react/index.d.ts:502

___

### `Static` `Optional` contextType

▪ **contextType**? : *Context‹any›*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[contextType](_src_markups_components_tags_tags_.tags.md#static-optional-contexttype)*

Defined in node_modules/@types/react/index.d.ts:458

If set, `this.context` will be set at runtime to the current value of the given Context.

Usage:

```ts
type MyContext = number
const Ctx = React.createContext<MyContext>(0)

class Foo extends React.Component {
  static contextType = Ctx
  context!: React.ContextType<typeof Ctx>
  render () {
    return <>My context's value: {this.context}</>;
  }
}
```

**`see`** https://reactjs.org/docs/context.html#classcontexttype

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)›, `nextState`: Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)› |
`nextState` | Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)› |
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

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:145

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)›, `prevState`: Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›, `snapshot?`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:683

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)› |
`prevState` | Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)› |
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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)› |
`nextContext` | any |

**Returns:** *void*

___

###  componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Overrides [AccessoLink](_src_markups_components_link_accesso_link_accesso_.accessolink.md).[componentWillUnmount](_src_markups_components_link_accesso_link_accesso_.accessolink.md#optional-componentwillunmount)*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:163

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)›, `nextState`: Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)› |
`nextState` | Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)› |
`nextContext` | any |

**Returns:** *void*

___

###  forceUpdate

▸ **forceUpdate**(`callback?`: function): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[forceUpdate](_src_markups_components_tags_tags_.tags.md#forceupdate)*

Defined in node_modules/@types/react/index.d.ts:493

**Parameters:**

▪`Optional`  **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

###  getImageSrc

▸ **getImageSrc**(`layout`: [ScreenShortName](../modules/_src_scripts_window_size_manager_.md#screenshortname), `format`: [ImageFormat](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imageformat)): *string*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:240

**Parameters:**

Name | Type |
------ | ------ |
`layout` | [ScreenShortName](../modules/_src_scripts_window_size_manager_.md#screenshortname) |
`format` | [ImageFormat](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imageformat) |

**Returns:** *string*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)›, `prevState`: Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›): *any | null*

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
`prevProps` | Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)› |
`prevState` | Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)› |

**Returns:** *any | null*

___

###  isAnimated

▸ **isAnimated**(): *string*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:141

**Returns:** *string*

___

###  onImageError

▸ **onImageError**(): *void*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:290

**Returns:** *void*

___

###  onImageLoaded

▸ **onImageLoaded**(): *void*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:296

**Returns:** *void*

___

###  onLayout

▸ **onLayout**(): *void*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:176

**Returns:** *void*

___

###  onPreLoad

▸ **onPreLoad**(): *void*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:168

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

*Overrides void*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:182

**Returns:** *Element‹›*

___

###  renderCloudinaryImage

▸ **renderCloudinaryImage**(): *Element‹›*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:227

**Returns:** *Element‹›*

___

###  renderCloudinarySource

▸ **renderCloudinarySource**(`__namedParameters`: object): *Element‹›*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:208

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type |
------ | ------ |
`breakpoint` | number |
`format` | [ImageFormat](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imageformat) |
`index` | number |
`screenSize` | [ScreenShortName](../modules/_src_scripts_window_size_manager_.md#screenshortname) |

**Returns:** *Element‹›*

___

###  setState

▸ **setState**‹**K**›(`state`: function | Pick‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate), K› | [ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate) | null, `callback?`: function): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[setState](_src_markups_components_tags_tags_.tags.md#setstate)*

Defined in node_modules/@types/react/index.d.ts:488

**Type parameters:**

▪ **K**: *keyof ImageCloudinaryState*

**Parameters:**

▪ **state**: *function | Pick‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate), K› | [ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate) | null*

▪`Optional`  **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)›, `nextState`: Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops)› |
`nextState` | Readonly‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)› |
`nextContext` | any |

**Returns:** *boolean*

___

###  shouldLoadImage

▸ **shouldLoadImage**(): *boolean*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:286

**Returns:** *boolean*

___

### `Static` getDerivedStateFromProps

▸ **getDerivedStateFromProps**(`nextProps`: [ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops), `prevState`: [ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)): *Partial‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:135

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | [ImageCloudinaryProps](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinaryprops) |
`prevState` | [ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate) |

**Returns:** *Partial‹[ImageCloudinaryState](../modules/_src_markups_components_image_cloudinary_image_cloudinary_.md#imagecloudinarystate)›*

## Object literals

### `Static` default

### ▪ **default**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:109

###  alt

• **alt**: *string* = ""

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:115

###  className

• **className**: *string* = ""

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:116

###  cloudinaryOptions

• **cloudinaryOptions**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:112

#### Type declaration:

###  disableLazyLoading

• **disableLazyLoading**: *false* = false

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:114

###  errorClassName

• **errorClassName**: *string* = "c-image-cloudinary--placeholder"

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:118

###  image

• **image**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:110

#### Type declaration:

###  options

• **options**: *object*

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:111

#### Type declaration:

###  successClassName

• **successClassName**: *string* = ""

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:117

###  visible

• **visible**: *false* = false

Defined in src/markups/components/image-cloudinary/image-cloudinary.tsx:113
