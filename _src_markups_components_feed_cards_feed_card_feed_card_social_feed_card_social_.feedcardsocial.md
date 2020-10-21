[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social"](../modules/_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.md) › [FeedCardSocial](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md)

# Class: FeedCardSocial

## Hierarchy

* PureComponent

  ↳ **FeedCardSocial**

## Index

### Constructors

* [constructor](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#constructor)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-unsafe_componentwillupdate)
* [adjustFontSize](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#adjustfontsize)
* [componentDidCatch](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#componentdidupdate)
* [componentWillMount](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#componentwillunmount)
* [componentWillUpdate](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-componentwillupdate)
* [getFontSizeIncrement](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#getfontsizeincrement)
* [getSnapshotBeforeUpdate](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-getsnapshotbeforeupdate)
* [onFirstShow](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#onfirstshow)
* [onWindowResize](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#onwindowresize)
* [render](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#render)
* [shouldComponentUpdate](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#optional-shouldcomponentupdate)

### Object literals

* [state](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md#state)

## Constructors

###  constructor

\+ **new FeedCardSocial**(`props`: any): *[FeedCardSocial](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md)*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:22

**Parameters:**

Name | Type |
------ | ------ |
`props` | any |

**Returns:** *[FeedCardSocial](_src_markups_components_feed_cards_feed_card_feed_card_social_feed_card_social_.feedcardsocial.md)*

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹object›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹object› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

###  adjustFontSize

▸ **adjustFontSize**(): *void*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:62

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

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:29

**Returns:** *void*

___

###  componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: any, `prevState`: any): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentdidupdate)*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:33

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | any |
`prevState` | any |

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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

###  componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillUnmount](_src_markups_components_tags_tags_.tags.md#optional-componentwillunmount)*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:42

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹object›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹object› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

###  getFontSizeIncrement

▸ **getFontSizeIncrement**(`$textContainer`: any, `$content`: any, `overflow`: any): *1 | 0 | -1*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:81

**Parameters:**

Name | Type |
------ | ------ |
`$textContainer` | any |
`$content` | any |
`overflow` | any |

**Returns:** *1 | 0 | -1*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹object›, `prevState`: Readonly‹object›): *any | null*

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
`prevProps` | Readonly‹object› |
`prevState` | Readonly‹object› |

**Returns:** *any | null*

___

###  onFirstShow

▸ **onFirstShow**(): *void*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:54

**Returns:** *void*

___

###  onWindowResize

▸ **onWindowResize**(): *void*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:46

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:102

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹object›, `nextState`: Readonly‹object›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹object› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

###  state

### ▪ **state**: *object*

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:20

###  imageError

• **imageError**: *boolean* = false

Defined in src/markups/components/feed-cards/feed-card/feed-card-social/feed-card-social.js:21
