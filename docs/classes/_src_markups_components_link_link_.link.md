[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/link/link"](../modules/_src_markups_components_link_link_.md) › [Link](_src_markups_components_link_link_.link.md)

# Class: Link

## Hierarchy

* PureComponent‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)›

  ↳ **Link**

## Index

### Properties

* [anchorContentEl](_src_markups_components_link_link_.link.md#anchorcontentel)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_link_link_.link.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_link_link_.link.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_link_link_.link.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_link_link_.link.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_link_link_.link.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_link_link_.link.md#componentdidupdate)
* [componentWillMount](_src_markups_components_link_link_.link.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_link_link_.link.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_link_link_.link.md#optional-componentwillunmount)
* [componentWillUpdate](_src_markups_components_link_link_.link.md#optional-componentwillupdate)
* [getSnapshotBeforeUpdate](_src_markups_components_link_link_.link.md#optional-getsnapshotbeforeupdate)
* [handleDisabledLink](_src_markups_components_link_link_.link.md#handledisabledlink)
* [injectEmbedCode](_src_markups_components_link_link_.link.md#injectembedcode)
* [render](_src_markups_components_link_link_.link.md#render)
* [renderCommonLink](_src_markups_components_link_link_.link.md#rendercommonlink)
* [shouldComponentUpdate](_src_markups_components_link_link_.link.md#optional-shouldcomponentupdate)

### Object literals

* [defaultProps](_src_markups_components_link_link_.link.md#static-defaultprops)

## Properties

###  anchorContentEl

• **anchorContentEl**: *RefObject‹HTMLAnchorElement›* = React.createRef()

Defined in src/markups/components/link/link.tsx:53

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)› |
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

Defined in src/markups/components/link/link.tsx:55

**Returns:** *void*

___

###  componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: [LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)): *void*

*Overrides [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidupdate)*

Defined in src/markups/components/link/link.tsx:59

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | [LinkProps](../modules/_src_markups_components_link_link_.md#linkprops) |

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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)› |
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

▸ **componentWillUpdate**(`nextProps`: Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)›, `prevState`: Readonly‹object›): *any | null*

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
`prevProps` | Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)› |
`prevState` | Readonly‹object› |

**Returns:** *any | null*

___

###  handleDisabledLink

▸ **handleDisabledLink**(`e`: MouseEvent): *void*

Defined in src/markups/components/link/link.tsx:111

**Parameters:**

Name | Type |
------ | ------ |
`e` | MouseEvent |

**Returns:** *void*

___

###  injectEmbedCode

▸ **injectEmbedCode**(): *void*

Defined in src/markups/components/link/link.tsx:65

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/link/link.tsx:102

**Returns:** *Element‹›*

___

###  renderCommonLink

▸ **renderCommonLink**(): *Element‹›*

Defined in src/markups/components/link/link.tsx:74

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[LinkProps](../modules/_src_markups_components_link_link_.md#linkprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/link/link.tsx:45

###  className

• **className**: *string* = ""

Defined in src/markups/components/link/link.tsx:47

###  content

• **content**: *string* = ""

Defined in src/markups/components/link/link.tsx:48

###  disabled

• **disabled**: *false* = false

Defined in src/markups/components/link/link.tsx:49

###  keepHref

• **keepHref**: *false* = false

Defined in src/markups/components/link/link.tsx:50

###  link

• **link**: *object*

Defined in src/markups/components/link/link.tsx:46

#### Type declaration:
