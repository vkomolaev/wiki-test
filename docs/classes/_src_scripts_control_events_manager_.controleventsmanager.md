[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/control-events-manager"](../modules/_src_scripts_control_events_manager_.md) › [ControlEventsManager](_src_scripts_control_events_manager_.controleventsmanager.md)

# Class: ControlEventsManager

## Hierarchy

* **ControlEventsManager**

## Index

### Properties

* [subscribers](_src_scripts_control_events_manager_.controleventsmanager.md#protected-subscribers)

### Methods

* [dispatch](_src_scripts_control_events_manager_.controleventsmanager.md#dispatch)
* [subscribe](_src_scripts_control_events_manager_.controleventsmanager.md#subscribe)
* [unsubscribe](_src_scripts_control_events_manager_.controleventsmanager.md#unsubscribe)

## Properties

### `Protected` subscribers

• **subscribers**: *[Subscriber](_src_scripts_dom_events_manager_.subscriber.md)[]* = []

Defined in src/scripts/control-events-manager.ts:16

## Methods

###  dispatch

▸ **dispatch**(`eventName`: string, ...`params`: any[]): *void*

Defined in src/scripts/control-events-manager.ts:34

**Parameters:**

Name | Type |
------ | ------ |
`eventName` | string |
`...params` | any[] |

**Returns:** *void*

___

###  subscribe

▸ **subscribe**(`instance`: [ViewInstance](../modules/_src_scripts_control_events_manager_.md#viewinstance)): *[Subscriber](_src_scripts_dom_events_manager_.subscriber.md)*

Defined in src/scripts/control-events-manager.ts:18

**Parameters:**

Name | Type |
------ | ------ |
`instance` | [ViewInstance](../modules/_src_scripts_control_events_manager_.md#viewinstance) |

**Returns:** *[Subscriber](_src_scripts_dom_events_manager_.subscriber.md)*

___

###  unsubscribe

▸ **unsubscribe**(`instance`: [ViewInstance](../modules/_src_scripts_control_events_manager_.md#viewinstance)): *void*

Defined in src/scripts/control-events-manager.ts:27

**Parameters:**

Name | Type |
------ | ------ |
`instance` | [ViewInstance](../modules/_src_scripts_control_events_manager_.md#viewinstance) |

**Returns:** *void*
