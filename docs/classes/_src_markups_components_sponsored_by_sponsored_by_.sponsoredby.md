[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/sponsored-by/sponsored-by"](../modules/_src_markups_components_sponsored_by_sponsored_by_.md) › [SponsoredBy](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md)

# Class: SponsoredBy

## Hierarchy

* PureComponent‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)›

  ↳ **SponsoredBy**

## Index

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-componentdidmount)
* [componentDidUpdate](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-componentdidupdate)
* [componentWillMount](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-componentwillunmount)
* [componentWillUpdate](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-componentwillupdate)
* [getSnapshotBeforeUpdate](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-getsnapshotbeforeupdate)
* [render](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#render)
* [renderLabel](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#renderlabel)
* [shouldComponentUpdate](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#optional-shouldcomponentupdate)

### Object literals

* [defaultProps](_src_markups_components_sponsored_by_sponsored_by_.sponsoredby.md#static-defaultprops)

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)› |
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

### `Optional` componentDidMount

▸ **componentDidMount**(): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidMount](_src_markups_components_tags_tags_.tags.md#optional-componentdidmount)*

Defined in node_modules/@types/react/index.d.ts:620

Called immediately after a component is mounted. Setting state here will trigger re-rendering.

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)›, `prevState`: Readonly‹object›, `snapshot?`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:683

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)› |
`prevState` | Readonly‹object› |
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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)› |
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

▸ **componentWillUpdate**(`nextProps`: Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)›, `prevState`: Readonly‹object›): *any | null*

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
`prevProps` | Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)› |
`prevState` | Readonly‹object› |

**Returns:** *any | null*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/sponsored-by/sponsored-by.tsx:35

**Returns:** *Element‹›*

___

###  renderLabel

▸ **renderLabel**(): *Element‹›*

Defined in src/markups/components/sponsored-by/sponsored-by.tsx:54

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[SponsoredByProps](../modules/_src_markups_components_sponsored_by_sponsored_by_.md#sponsoredbyprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/sponsored-by/sponsored-by.tsx:31

###  title

• **title**: *string* = "Sponsored by"

Defined in src/markups/components/sponsored-by/sponsored-by.tsx:32
