[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/embed-code/embed-code"](../modules/_src_markups_components_embed_code_embed_code_.md) › [EmbedCode](_src_markups_components_embed_code_embed_code_.embedcode.md)

# Class: EmbedCode

## Hierarchy

* PureComponent‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)›

  ↳ **EmbedCode**

## Index

### Properties

* [element](_src_markups_components_embed_code_embed_code_.embedcode.md#element)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_embed_code_embed_code_.embedcode.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_embed_code_embed_code_.embedcode.md#componentdidupdate)
* [componentWillMount](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-componentwillunmount)
* [componentWillUpdate](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-componentwillupdate)
* [getSnapshotBeforeUpdate](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-getsnapshotbeforeupdate)
* [injectEmbedCode](_src_markups_components_embed_code_embed_code_.embedcode.md#injectembedcode)
* [render](_src_markups_components_embed_code_embed_code_.embedcode.md#render)
* [shouldComponentUpdate](_src_markups_components_embed_code_embed_code_.embedcode.md#optional-shouldcomponentupdate)

### Object literals

* [defaultProps](_src_markups_components_embed_code_embed_code_.embedcode.md#static-defaultprops)

## Properties

###  element

• **element**: *RefObject‹HTMLDivElement›* = React.createRef()

Defined in src/markups/components/embed-code/embed-code.tsx:28

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)› |
`nextState` | Readonly‹object› |
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

Defined in src/markups/components/embed-code/embed-code.tsx:30

**Returns:** *void*

___

###  componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: [EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)): *void*

*Overrides [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidupdate)*

Defined in src/markups/components/embed-code/embed-code.tsx:34

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | [EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops) |

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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Inherited from [AccessoLink](_src_markups_components_link_accesso_link_accesso_.accessolink.md).[componentWillUnmount](_src_markups_components_link_accesso_link_accesso_.accessolink.md#optional-componentwillunmount)*

Defined in node_modules/@types/react/index.d.ts:636

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)›, `prevState`: Readonly‹object›): *any | null*

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
`prevProps` | Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)› |
`prevState` | Readonly‹object› |

**Returns:** *any | null*

___

###  injectEmbedCode

▸ **injectEmbedCode**(): *void*

Defined in src/markups/components/embed-code/embed-code.tsx:40

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/embed-code/embed-code.tsx:45

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[EmbedCodeProps](../modules/_src_markups_components_embed_code_embed_code_.md#embedcodeprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/embed-code/embed-code.tsx:24

###  className

• **className**: *string* = ""

Defined in src/markups/components/embed-code/embed-code.tsx:25
