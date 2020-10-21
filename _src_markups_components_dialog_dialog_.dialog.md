[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/dialog/dialog"](../modules/_src_markups_components_dialog_dialog_.md) › [Dialog](_src_markups_components_dialog_dialog_.dialog.md)

# Class: Dialog

## Hierarchy

* PureComponent‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)›

  ↳ **Dialog**

## Index

### Properties

* [wrapperRef](_src_markups_components_dialog_dialog_.dialog.md#protected-wrapperref)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_dialog_dialog_.dialog.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_dialog_dialog_.dialog.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_dialog_dialog_.dialog.md#optional-unsafe_componentwillupdate)
* [close](_src_markups_components_dialog_dialog_.dialog.md#close)
* [componentDidCatch](_src_markups_components_dialog_dialog_.dialog.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_dialog_dialog_.dialog.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_dialog_dialog_.dialog.md#optional-componentdidupdate)
* [componentWillMount](_src_markups_components_dialog_dialog_.dialog.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_dialog_dialog_.dialog.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_dialog_dialog_.dialog.md#componentwillunmount)
* [componentWillUpdate](_src_markups_components_dialog_dialog_.dialog.md#optional-componentwillupdate)
* [disableScroll](_src_markups_components_dialog_dialog_.dialog.md#disablescroll)
* [getContent](_src_markups_components_dialog_dialog_.dialog.md#getcontent)
* [getSnapshotBeforeUpdate](_src_markups_components_dialog_dialog_.dialog.md#optional-getsnapshotbeforeupdate)
* [onButtonClick](_src_markups_components_dialog_dialog_.dialog.md#onbuttonclick)
* [onKeyup](_src_markups_components_dialog_dialog_.dialog.md#onkeyup)
* [render](_src_markups_components_dialog_dialog_.dialog.md#render)
* [renderCloseButton](_src_markups_components_dialog_dialog_.dialog.md#renderclosebutton)
* [renderDialogButtons](_src_markups_components_dialog_dialog_.dialog.md#renderdialogbuttons)
* [renderTitle](_src_markups_components_dialog_dialog_.dialog.md#rendertitle)
* [shouldComponentUpdate](_src_markups_components_dialog_dialog_.dialog.md#optional-shouldcomponentupdate)

### Object literals

* [defaultProps](_src_markups_components_dialog_dialog_.dialog.md#static-defaultprops)

## Properties

### `Protected` wrapperRef

• **wrapperRef**: *RefObject‹HTMLDivElement›*

Defined in src/markups/components/dialog/dialog.tsx:53

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

###  close

▸ **close**(): *void*

Defined in src/markups/components/dialog/dialog.tsx:161

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

Defined in src/markups/components/dialog/dialog.tsx:55

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)›, `prevState`: Readonly‹object›, `snapshot?`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:683

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)› |
`prevState` | Readonly‹object› |
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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)› |
`nextContext` | any |

**Returns:** *void*

___

###  componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillUnmount](_src_markups_components_tags_tags_.tags.md#optional-componentwillunmount)*

Defined in src/markups/components/dialog/dialog.tsx:73

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

###  disableScroll

▸ **disableScroll**(`modal`: boolean, `containerRef?`: RefObject‹HTMLDivElement›): *void*

Defined in src/markups/components/dialog/dialog.tsx:63

**Parameters:**

Name | Type |
------ | ------ |
`modal` | boolean |
`containerRef?` | RefObject‹HTMLDivElement› |

**Returns:** *void*

___

###  getContent

▸ **getContent**(): *any*

Defined in src/markups/components/dialog/dialog.tsx:136

**Returns:** *any*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)›, `prevState`: Readonly‹object›): *any | null*

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
`prevProps` | Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)› |
`prevState` | Readonly‹object› |

**Returns:** *any | null*

___

###  onButtonClick

▸ **onButtonClick**(`button`: [DialogButtonType](../modules/_src_markups_components_dialog_dialog_.md#dialogbuttontype)): *void*

Defined in src/markups/components/dialog/dialog.tsx:154

**Parameters:**

Name | Type |
------ | ------ |
`button` | [DialogButtonType](../modules/_src_markups_components_dialog_dialog_.md#dialogbuttontype) |

**Returns:** *void*

___

###  onKeyup

▸ **onKeyup**(`e`: KeyboardEvent): *void*

Defined in src/markups/components/dialog/dialog.tsx:148

**Parameters:**

Name | Type |
------ | ------ |
`e` | KeyboardEvent |

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/dialog/dialog.tsx:80

**Returns:** *Element‹›*

___

###  renderCloseButton

▸ **renderCloseButton**(): *Element‹›*

Defined in src/markups/components/dialog/dialog.tsx:112

**Returns:** *Element‹›*

___

###  renderDialogButtons

▸ **renderDialogButtons**(): *Element‹›[]*

Defined in src/markups/components/dialog/dialog.tsx:96

**Returns:** *Element‹›[]*

___

###  renderTitle

▸ **renderTitle**(): *Element‹›*

Defined in src/markups/components/dialog/dialog.tsx:128

**Returns:** *Element‹›*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[DialogProps](../modules/_src_markups_components_dialog_dialog_.md#dialogprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/dialog/dialog.tsx:44

###  buttons

• **buttons**: *undefined[]* = []

Defined in src/markups/components/dialog/dialog.tsx:48

###  className

• **className**: *string* = ""

Defined in src/markups/components/dialog/dialog.tsx:45

###  content

• **content**: *string* = ""

Defined in src/markups/components/dialog/dialog.tsx:47

###  modal

• **modal**: *true* = true

Defined in src/markups/components/dialog/dialog.tsx:49

###  target

• **target**: *string* = ""

Defined in src/markups/components/dialog/dialog.tsx:50

###  title

• **title**: *string* = ""

Defined in src/markups/components/dialog/dialog.tsx:46
