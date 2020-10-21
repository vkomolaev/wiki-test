[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/control-events-manager"](../modules/_src_scripts_control_events_manager_.md) › [Subscriber](_src_scripts_control_events_manager_.subscriber.md)

# Class: Subscriber

## Hierarchy

* **Subscriber**

## Index

### Constructors

* [constructor](_src_scripts_control_events_manager_.subscriber.md#constructor)

### Properties

* [attachedEvents](_src_scripts_control_events_manager_.subscriber.md#protected-attachedevents)
* [instance](_src_scripts_control_events_manager_.subscriber.md#instance)

### Methods

* [destroy](_src_scripts_control_events_manager_.subscriber.md#destroy)
* [emitEvent](_src_scripts_control_events_manager_.subscriber.md#emitevent)
* [listenTo](_src_scripts_control_events_manager_.subscriber.md#listento)

## Constructors

###  constructor

\+ **new Subscriber**(`__namedParameters`: object): *[Subscriber](_src_scripts_control_events_manager_.subscriber.md)*

Defined in src/scripts/control-events-manager.ts:44

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type |
------ | ------ |
`instance` | [ViewInstance](../modules/_src_scripts_control_events_manager_.md#viewinstance) |

**Returns:** *[Subscriber](_src_scripts_control_events_manager_.subscriber.md)*

## Properties

### `Protected` attachedEvents

• **attachedEvents**: *string[]* = []

Defined in src/scripts/control-events-manager.ts:42

___

###  instance

• **instance**: *[ViewInstance](../modules/_src_scripts_control_events_manager_.md#viewinstance)* = null

Defined in src/scripts/control-events-manager.ts:44

## Methods

###  destroy

▸ **destroy**(): *this*

Defined in src/scripts/control-events-manager.ts:61

**Returns:** *this*

___

###  emitEvent

▸ **emitEvent**(`eventName`: string, `params`: any[]): *void*

Defined in src/scripts/control-events-manager.ts:55

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`eventName` | string | - |
`params` | any[] | [] |

**Returns:** *void*

___

###  listenTo

▸ **listenTo**(`eventName`: string): *this*

Defined in src/scripts/control-events-manager.ts:50

**Parameters:**

Name | Type |
------ | ------ |
`eventName` | string |

**Returns:** *this*
