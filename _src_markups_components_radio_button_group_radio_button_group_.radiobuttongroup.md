[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/radio-button-group/radio-button-group"](../modules/_src_markups_components_radio_button_group_radio_button_group_.md) › [RadioButtonGroup](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md)

# Class: RadioButtonGroup

## Hierarchy

* Component‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)›

  ↳ **RadioButtonGroup**

## Index

### Constructors

* [constructor](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#constructor)

### Properties

* [context](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#context)
* [props](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#readonly-props)
* [refs](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#refs)
* [contextType](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#static-optional-contexttype)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-componentdidmount)
* [componentDidUpdate](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#componentdidupdate)
* [componentWillMount](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-componentwillunmount)
* [componentWillUpdate](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-componentwillupdate)
* [forceUpdate](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#forceupdate)
* [getSnapshotBeforeUpdate](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-getsnapshotbeforeupdate)
* [handleChange](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#handlechange)
* [render](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#render)
* [renderItem](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#renderitem)
* [reset](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#reset)
* [setState](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#setstate)
* [shouldComponentUpdate](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#optional-shouldcomponentupdate)

### Object literals

* [state](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#state)
* [defaultProps](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md#static-defaultprops)

## Constructors

###  constructor

\+ **new RadioButtonGroup**(`props`: Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› | [RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)): *[RadioButtonGroup](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md)*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[constructor](_src_markups_components_tags_tags_.tags.md#constructor)*

Defined in node_modules/@types/react/index.d.ts:476

**`deprecated`** 

**`see`** https://reactjs.org/docs/legacy-context.html

**Parameters:**

Name | Type |
------ | ------ |
`props` | Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› &#124; [RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops) |

**Returns:** *[RadioButtonGroup](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md)*

\+ **new RadioButtonGroup**(`props`: [RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops), `context`: any): *[RadioButtonGroup](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md)*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[constructor](_src_markups_components_tags_tags_.tags.md#constructor)*

Defined in node_modules/@types/react/index.d.ts:478

**`deprecated`** 

**`see`** https://reactjs.org/docs/legacy-context.html

**Parameters:**

Name | Type |
------ | ------ |
`props` | [RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops) |
`context` | any |

**Returns:** *[RadioButtonGroup](_src_markups_components_radio_button_group_radio_button_group_.radiobuttongroup.md)*

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

### `Readonly` props

• **props**: *Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› & Readonly‹object›*

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› |
`nextState` | Readonly‹object› |
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

### `Optional` componentDidMount

▸ **componentDidMount**(): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidMount](_src_markups_components_tags_tags_.tags.md#optional-componentdidmount)*

Defined in node_modules/@types/react/index.d.ts:620

Called immediately after a component is mounted. Setting state here will trigger re-rendering.

**Returns:** *void*

___

###  componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: [RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentdidupdate)*

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:71

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | [RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops) |

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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› |
`nextContext` | any |

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

▸ **componentWillUpdate**(`nextProps`: Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› |
`nextState` | Readonly‹object› |
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

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)›, `prevState`: Readonly‹object›): *any | null*

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
`prevProps` | Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› |
`prevState` | Readonly‹object› |

**Returns:** *any | null*

___

###  handleChange

▸ **handleChange**(`value`: RadioButtonGroupItemProps["value"]): *void*

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:49

**Parameters:**

Name | Type |
------ | ------ |
`value` | RadioButtonGroupItemProps["value"] |

**Returns:** *void*

___

###  render

▸ **render**(): *Element‹›*

*Overrides void*

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:83

**Returns:** *Element‹›*

___

###  renderItem

▸ **renderItem**(`__namedParameters`: object, `index`: number): *Element‹›*

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:57

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type |
------ | ------ |
`label` | string |
`value` | string |

▪ **index**: *number*

**Returns:** *Element‹›*

___

###  reset

▸ **reset**(): *void*

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:79

**Returns:** *void*

___

###  setState

▸ **setState**‹**K**›(`state`: function | Pick‹object, K› | object | null, `callback?`: function): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[setState](_src_markups_components_tags_tags_.tags.md#setstate)*

Defined in node_modules/@types/react/index.d.ts:488

**Type parameters:**

▪ **K**: *keyof object*

**Parameters:**

▪ **state**: *function | Pick‹object, K› | object | null*

▪`Optional`  **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)›, `nextState`: Readonly‹object›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[RadioButtonGroupProps](../modules/_src_markups_components_radio_button_group_radio_button_group_.md#radiobuttongroupprops)› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

###  state

### ▪ **state**: *object*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[state](_src_markups_components_tags_tags_.tags.md#state)*

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:45

###  value

• **value**: *string* = ""

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:46

___

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:39

###  disabled

• **disabled**: *false* = false

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:42

###  items

• **items**: *undefined[]* = []

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:40

###  statusClass

• **statusClass**: *string* = ""

Defined in src/markups/components/radio-button-group/radio-button-group.tsx:41
