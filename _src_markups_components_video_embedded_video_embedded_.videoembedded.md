[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/video-embedded/video-embedded"](../modules/_src_markups_components_video_embedded_video_embedded_.md) › [VideoEmbedded](_src_markups_components_video_embedded_video_embedded_.videoembedded.md)

# Class: VideoEmbedded

## Hierarchy

* Component‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops), [VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›

  ↳ **VideoEmbedded**

## Index

### Constructors

* [constructor](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#constructor)

### Properties

* [context](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#context)
* [element](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#element)
* [props](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#readonly-props)
* [refs](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#refs)
* [state](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#state)
* [contextType](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#static-optional-contexttype)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#componentdidupdate)
* [componentWillMount](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-componentwillunmount)
* [componentWillUpdate](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-componentwillupdate)
* [forceUpdate](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#forceupdate)
* [getSnapshotBeforeUpdate](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-getsnapshotbeforeupdate)
* [getStateFromProps](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#getstatefromprops)
* [hasApiSupport](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#hasapisupport)
* [isPlaying](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#isplaying)
* [pause](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#pause)
* [play](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#play)
* [render](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#render)
* [renderEmbeddedVideo](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#renderembeddedvideo)
* [renderYoutubeVideo](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#renderyoutubevideo)
* [setState](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#setstate)
* [shouldComponentUpdate](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#optional-shouldcomponentupdate)
* [stop](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#stop)

### Object literals

* [defaultProps](_src_markups_components_video_embedded_video_embedded_.videoembedded.md#static-defaultprops)

## Constructors

###  constructor

\+ **new VideoEmbedded**(`props`: [VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)): *[VideoEmbedded](_src_markups_components_video_embedded_video_embedded_.videoembedded.md)*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[constructor](_src_markups_components_tags_tags_.tags.md#constructor)*

Defined in src/markups/components/video-embedded/video-embedded.tsx:72

**Parameters:**

Name | Type |
------ | ------ |
`props` | [VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops) |

**Returns:** *[VideoEmbedded](_src_markups_components_video_embedded_video_embedded_.videoembedded.md)*

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

###  element

• **element**: *[VideoYoutube](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md)*

Defined in src/markups/components/video-embedded/video-embedded.tsx:72

___

### `Readonly` props

• **props**: *Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› & Readonly‹object›*

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

• **state**: *Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›*

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)›, `nextState`: Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› |
`nextState` | Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)› |
`nextContext` | any |

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

Defined in src/markups/components/video-embedded/video-embedded.tsx:99

**Returns:** *void*

___

###  componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Partial‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)›): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentdidupdate)*

Defined in src/markups/components/video-embedded/video-embedded.tsx:105

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Partial‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› |

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

###  componentWillReceiveProps

▸ **componentWillReceiveProps**(`nextProps`: Partial‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)›): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillReceiveProps](_src_markups_components_tags_tags_.tags.md#optional-componentwillreceiveprops)*

Defined in src/markups/components/video-embedded/video-embedded.tsx:93

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Partial‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› |

**Returns:** *void*

___

### `Optional` componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillUnmount](_src_markups_components_tags_tags_.tags.md#optional-componentwillunmount)*

Defined in node_modules/@types/react/index.d.ts:636

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)›, `nextState`: Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› |
`nextState` | Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)› |
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

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)›, `prevState`: Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›): *any | null*

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
`prevProps` | Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› |
`prevState` | Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)› |

**Returns:** *any | null*

___

###  getStateFromProps

▸ **getStateFromProps**(`props`: Partial‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)›, `state?`: Partial‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›): *Partial‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›*

Defined in src/markups/components/video-embedded/video-embedded.tsx:87

**Parameters:**

Name | Type |
------ | ------ |
`props` | Partial‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› |
`state?` | Partial‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)› |

**Returns:** *Partial‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›*

___

###  hasApiSupport

▸ **hasApiSupport**(): *boolean*

Defined in src/markups/components/video-embedded/video-embedded.tsx:79

**Returns:** *boolean*

___

###  isPlaying

▸ **isPlaying**(): *boolean*

Defined in src/markups/components/video-embedded/video-embedded.tsx:146

**Returns:** *boolean*

___

###  pause

▸ **pause**(): *void*

Defined in src/markups/components/video-embedded/video-embedded.tsx:126

**Returns:** *void*

___

###  play

▸ **play**(): *Promise‹void›*

Defined in src/markups/components/video-embedded/video-embedded.tsx:114

**Returns:** *Promise‹void›*

___

###  render

▸ **render**(): *Element‹›*

*Overrides void*

Defined in src/markups/components/video-embedded/video-embedded.tsx:154

**Returns:** *Element‹›*

___

###  renderEmbeddedVideo

▸ **renderEmbeddedVideo**(): *Element‹›*

Defined in src/markups/components/video-embedded/video-embedded.tsx:181

**Returns:** *Element‹›*

___

###  renderYoutubeVideo

▸ **renderYoutubeVideo**(): *Element‹›*

Defined in src/markups/components/video-embedded/video-embedded.tsx:164

**Returns:** *Element‹›*

___

###  setState

▸ **setState**‹**K**›(`state`: function | Pick‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate), K› | [VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate) | null, `callback?`: function): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[setState](_src_markups_components_tags_tags_.tags.md#setstate)*

Defined in node_modules/@types/react/index.d.ts:488

**Type parameters:**

▪ **K**: *keyof VideoEmbeddedState*

**Parameters:**

▪ **state**: *function | Pick‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate), K› | [VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate) | null*

▪`Optional`  **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)›, `nextState`: Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[VideoEmbeddedProps](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedprops)› |
`nextState` | Readonly‹[VideoEmbeddedState](../modules/_src_markups_components_video_embedded_video_embedded_.md#videoembeddedstate)› |
`nextContext` | any |

**Returns:** *boolean*

___

###  stop

▸ **stop**(): *void*

Defined in src/markups/components/video-embedded/video-embedded.tsx:136

**Returns:** *void*

## Object literals

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/video-embedded/video-embedded.tsx:66

###  className

• **className**: *string* = ""

Defined in src/markups/components/video-embedded/video-embedded.tsx:67

###  errorClassName

• **errorClassName**: *string* = ""

Defined in src/markups/components/video-embedded/video-embedded.tsx:68

###  successClassName

• **successClassName**: *string* = ""

Defined in src/markups/components/video-embedded/video-embedded.tsx:69
