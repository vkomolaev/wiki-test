[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/date-picker/date-picker"](../modules/_src_markups_components_date_picker_date_picker_.md) › [DatePicker](_src_markups_components_date_picker_date_picker_.datepicker.md)

# Class: DatePicker

## Hierarchy

* PureComponent‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops), [DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)›

  ↳ **DatePicker**

## Index

### Constructors

* [constructor](_src_markups_components_date_picker_date_picker_.datepicker.md#constructor)

### Properties

* [$datePickerElement](_src_markups_components_date_picker_date_picker_.datepicker.md#protected-datepickerelement)
* [element](_src_markups_components_date_picker_date_picker_.datepicker.md#protected-element)
* [id](_src_markups_components_date_picker_date_picker_.datepicker.md#protected-id)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-unsafe_componentwillupdate)
* [componentDidCatch](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_date_picker_date_picker_.datepicker.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_date_picker_date_picker_.datepicker.md#componentdidupdate)
* [componentWillMount](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-componentwillunmount)
* [componentWillUpdate](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-componentwillupdate)
* [getOptions](_src_markups_components_date_picker_date_picker_.datepicker.md#getoptions)
* [getSnapshotBeforeUpdate](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-getsnapshotbeforeupdate)
* [getTextValue](_src_markups_components_date_picker_date_picker_.datepicker.md#gettextvalue)
* [render](_src_markups_components_date_picker_date_picker_.datepicker.md#render)
* [renderPickerField](_src_markups_components_date_picker_date_picker_.datepicker.md#renderpickerfield)
* [reset](_src_markups_components_date_picker_date_picker_.datepicker.md#reset)
* [setValues](_src_markups_components_date_picker_date_picker_.datepicker.md#setvalues)
* [shouldComponentUpdate](_src_markups_components_date_picker_date_picker_.datepicker.md#optional-shouldcomponentupdate)

### Object literals

* [state](_src_markups_components_date_picker_date_picker_.datepicker.md#state)
* [defaultProps](_src_markups_components_date_picker_date_picker_.datepicker.md#static-defaultprops)

## Constructors

###  constructor

\+ **new DatePicker**(`props`: [DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)): *[DatePicker](_src_markups_components_date_picker_date_picker_.datepicker.md)*

Defined in src/markups/components/date-picker/date-picker.tsx:99

**Parameters:**

Name | Type |
------ | ------ |
`props` | [DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops) |

**Returns:** *[DatePicker](_src_markups_components_date_picker_date_picker_.datepicker.md)*

## Properties

### `Protected` $datePickerElement

• **$datePickerElement**: *Element*

Defined in src/markups/components/date-picker/date-picker.tsx:99

___

### `Protected` element

• **element**: *Element*

Defined in src/markups/components/date-picker/date-picker.tsx:97

___

### `Protected` id

• **id**: *string*

Defined in src/markups/components/date-picker/date-picker.tsx:95

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)›, `nextState`: Readonly‹[DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)› |
`nextState` | Readonly‹[DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)› |
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

Defined in src/markups/components/date-picker/date-picker.tsx:112

**Returns:** *void*

___

###  componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: [DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentdidupdate)*

Defined in src/markups/components/date-picker/date-picker.tsx:127

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | [DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops) |

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

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)› |
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

▸ **componentWillUpdate**(`nextProps`: Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)›, `nextState`: Readonly‹[DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)›, `nextContext`: any): *void*

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
`nextProps` | Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)› |
`nextState` | Readonly‹[DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)› |
`nextContext` | any |

**Returns:** *void*

___

###  getOptions

▸ **getOptions**(): *object*

Defined in src/markups/components/date-picker/date-picker.tsx:151

**Returns:** *object*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)›, `prevState`: Readonly‹[DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)›): *any | null*

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
`prevProps` | Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)› |
`prevState` | Readonly‹[DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)› |

**Returns:** *any | null*

___

###  getTextValue

▸ **getTextValue**(`startDate?`: [AnyDate](../modules/_src_scripts_types_.md#anydate), `endDate?`: [AnyDate](../modules/_src_scripts_types_.md#anydate)): *string*

Defined in src/markups/components/date-picker/date-picker.tsx:139

**Parameters:**

Name | Type |
------ | ------ |
`startDate?` | [AnyDate](../modules/_src_scripts_types_.md#anydate) |
`endDate?` | [AnyDate](../modules/_src_scripts_types_.md#anydate) |

**Returns:** *string*

___

###  render

▸ **render**(): *Element‹›*

Defined in src/markups/components/date-picker/date-picker.tsx:192

**Returns:** *Element‹›*

___

###  renderPickerField

▸ **renderPickerField**(): *Element‹›*

Defined in src/markups/components/date-picker/date-picker.tsx:201

**Returns:** *Element‹›*

___

###  reset

▸ **reset**(): *void*

Defined in src/markups/components/date-picker/date-picker.tsx:135

**Returns:** *void*

___

###  setValues

▸ **setValues**(`startDate?`: Moment, `endDate?`: Moment): *void*

Defined in src/markups/components/date-picker/date-picker.tsx:185

**Parameters:**

Name | Type |
------ | ------ |
`startDate?` | Moment |
`endDate?` | Moment |

**Returns:** *void*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)›, `nextState`: Readonly‹[DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)›, `nextContext`: any): *boolean*

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
`nextProps` | Readonly‹[DatePickerProps](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerprops)› |
`nextState` | Readonly‹[DatePickerState](../modules/_src_markups_components_date_picker_date_picker_.md#datepickerstate)› |
`nextContext` | any |

**Returns:** *boolean*

## Object literals

###  state

### ▪ **state**: *object*

Defined in src/markups/components/date-picker/date-picker.tsx:107

###  endDate

• **endDate**: *string* = this.props.endDate

Defined in src/markups/components/date-picker/date-picker.tsx:109

###  startDate

• **startDate**: *string* = this.props.startDate

Defined in src/markups/components/date-picker/date-picker.tsx:108

___

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/date-picker/date-picker.tsx:82

###  className

• **className**: *string* = ""

Defined in src/markups/components/date-picker/date-picker.tsx:86

###  disabled

• **disabled**: *false* = false

Defined in src/markups/components/date-picker/date-picker.tsx:92

###  firstDay

• **firstDay**: *number* = 1

Defined in src/markups/components/date-picker/date-picker.tsx:85

###  format

• **format**: *string* = "DD MM YYYY"

Defined in src/markups/components/date-picker/date-picker.tsx:84

###  linkedCalendars

• **linkedCalendars**: *false* = false

Defined in src/markups/components/date-picker/date-picker.tsx:90

###  name

• **name**: *string* = "datepicker"

Defined in src/markups/components/date-picker/date-picker.tsx:91

###  opens

• **opens**: *string* = "left"

Defined in src/markups/components/date-picker/date-picker.tsx:89

###  parentEl

• **parentEl**: *string* = "body"

Defined in src/markups/components/date-picker/date-picker.tsx:88

###  placeholder

• **placeholder**: *string* = ""

Defined in src/markups/components/date-picker/date-picker.tsx:87

###  showDropdowns

• **showDropdowns**: *false* = false

Defined in src/markups/components/date-picker/date-picker.tsx:83
