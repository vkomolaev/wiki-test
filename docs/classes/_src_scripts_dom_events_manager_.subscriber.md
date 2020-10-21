[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/dom-events-manager"](../modules/_src_scripts_dom_events_manager_.md) › [Subscriber](_src_scripts_dom_events_manager_.subscriber.md)

# Class: Subscriber

## Hierarchy

* **Subscriber**

## Index

### Constructors

* [constructor](_src_scripts_dom_events_manager_.subscriber.md#constructor)

### Properties

* [element](_src_scripts_dom_events_manager_.subscriber.md#element)
* [initialLayouted](_src_scripts_dom_events_manager_.subscriber.md#initiallayouted)
* [instance](_src_scripts_dom_events_manager_.subscriber.md#instance)
* [onFirstShow](_src_scripts_dom_events_manager_.subscriber.md#onfirstshow)
* [onPreLoad](_src_scripts_dom_events_manager_.subscriber.md#onpreload)
* [pleLoaded](_src_scripts_dom_events_manager_.subscriber.md#pleloaded)
* [shown](_src_scripts_dom_events_manager_.subscriber.md#shown)

### Methods

* [_getInstanceMethod](_src_scripts_dom_events_manager_.subscriber.md#_getinstancemethod)
* [callMethod](_src_scripts_dom_events_manager_.subscriber.md#callmethod)
* [destroy](_src_scripts_dom_events_manager_.subscriber.md#destroy)
* [initialLayout](_src_scripts_dom_events_manager_.subscriber.md#initiallayout)
* [outOfScreen](_src_scripts_dom_events_manager_.subscriber.md#outofscreen)
* [preLoad](_src_scripts_dom_events_manager_.subscriber.md#preload)
* [shouldBePreloadTracked](_src_scripts_dom_events_manager_.subscriber.md#shouldbepreloadtracked)
* [shouldBeTracked](_src_scripts_dom_events_manager_.subscriber.md#shouldbetracked)
* [shownOnScreen](_src_scripts_dom_events_manager_.subscriber.md#shownonscreen)

## Constructors

###  constructor

\+ **new Subscriber**(`__namedParameters`: object): *[Subscriber](_src_scripts_dom_events_manager_.subscriber.md)*

Defined in src/scripts/dom-events-manager.ts:224

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type | Default |
------ | ------ | ------ |
`element` | any | instance.element |
`instance` | any | - |
`onFirstShow` | any | - |
`onPreLoad` | any | - |

**Returns:** *[Subscriber](_src_scripts_dom_events_manager_.subscriber.md)*

## Properties

###  element

• **element**: *Element | Text* = null

Defined in src/scripts/dom-events-manager.ts:224

___

###  initialLayouted

• **initialLayouted**: *boolean* = false

Defined in src/scripts/dom-events-manager.ts:218

___

###  instance

• **instance**: *any* = null

Defined in src/scripts/dom-events-manager.ts:212

___

###  onFirstShow

• **onFirstShow**: *any* = null

Defined in src/scripts/dom-events-manager.ts:220

___

###  onPreLoad

• **onPreLoad**: *any* = null

Defined in src/scripts/dom-events-manager.ts:222

___

###  pleLoaded

• **pleLoaded**: *boolean* = false

Defined in src/scripts/dom-events-manager.ts:216

___

###  shown

• **shown**: *boolean* = false

Defined in src/scripts/dom-events-manager.ts:214

## Methods

###  _getInstanceMethod

▸ **_getInstanceMethod**(`methodName`: any): *any*

Defined in src/scripts/dom-events-manager.ts:294

**Parameters:**

Name | Type |
------ | ------ |
`methodName` | any |

**Returns:** *any*

___

###  callMethod

▸ **callMethod**(`methodName`: any, `params`: any[]): *void*

Defined in src/scripts/dom-events-manager.ts:237

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`methodName` | any | - |
`params` | any[] | [] |

**Returns:** *void*

___

###  destroy

▸ **destroy**(): *this*

Defined in src/scripts/dom-events-manager.ts:286

**Returns:** *this*

___

###  initialLayout

▸ **initialLayout**(): *void*

Defined in src/scripts/dom-events-manager.ts:261

**Returns:** *void*

___

###  outOfScreen

▸ **outOfScreen**(): *void*

Defined in src/scripts/dom-events-manager.ts:268

**Returns:** *void*

___

###  preLoad

▸ **preLoad**(): *void*

Defined in src/scripts/dom-events-manager.ts:253

**Returns:** *void*

___

###  shouldBePreloadTracked

▸ **shouldBePreloadTracked**(): *boolean*

Defined in src/scripts/dom-events-manager.ts:279

**Returns:** *boolean*

___

###  shouldBeTracked

▸ **shouldBeTracked**(): *boolean*

Defined in src/scripts/dom-events-manager.ts:272

**Returns:** *boolean*

___

###  shownOnScreen

▸ **shownOnScreen**(): *void*

Defined in src/scripts/dom-events-manager.ts:243

**Returns:** *void*
