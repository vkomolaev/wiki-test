[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/dom-events-manager"](../modules/_src_scripts_dom_events_manager_.md) › [DomEventsManager](_src_scripts_dom_events_manager_.domeventsmanager.md)

# Class: DomEventsManager

## Hierarchy

* any

  ↳ **DomEventsManager**

## Index

### Constructors

* [constructor](_src_scripts_dom_events_manager_.domeventsmanager.md#constructor)

### Properties

* [_onDocumentResize](_src_scripts_dom_events_manager_.domeventsmanager.md#_ondocumentresize)
* [_onWindowResizeThrottled](_src_scripts_dom_events_manager_.domeventsmanager.md#_onwindowresizethrottled)
* [_onWindowScrollThrottled](_src_scripts_dom_events_manager_.domeventsmanager.md#_onwindowscrollthrottled)
* [_screenSize](_src_scripts_dom_events_manager_.domeventsmanager.md#protected-_screensize)
* [onPreloadObserver](_src_scripts_dom_events_manager_.domeventsmanager.md#protected-onpreloadobserver)
* [onScreenObserver](_src_scripts_dom_events_manager_.domeventsmanager.md#protected-onscreenobserver)
* [subscribers](_src_scripts_dom_events_manager_.domeventsmanager.md#protected-subscribers)
* [visibilitySubscribers](_src_scripts_dom_events_manager_.domeventsmanager.md#protected-visibilitysubscribers)

### Methods

* [_addSubscriber](_src_scripts_dom_events_manager_.domeventsmanager.md#_addsubscriber)
* [_checkVisibilitySubscribers](_src_scripts_dom_events_manager_.domeventsmanager.md#_checkvisibilitysubscribers)
* [_emitSubscribers](_src_scripts_dom_events_manager_.domeventsmanager.md#_emitsubscribers)
* [_onDOMLoaded](_src_scripts_dom_events_manager_.domeventsmanager.md#_ondomloaded)
* [_onDocumentInteract](_src_scripts_dom_events_manager_.domeventsmanager.md#_ondocumentinteract)
* [_onElementIntersection](_src_scripts_dom_events_manager_.domeventsmanager.md#_onelementintersection)
* [_onElementPreload](_src_scripts_dom_events_manager_.domeventsmanager.md#_onelementpreload)
* [_onWindowResize](_src_scripts_dom_events_manager_.domeventsmanager.md#_onwindowresize)
* [_onWindowScroll](_src_scripts_dom_events_manager_.domeventsmanager.md#_onwindowscroll)
* [onElementVisible](_src_scripts_dom_events_manager_.domeventsmanager.md#onelementvisible)
* [onFirstShow](_src_scripts_dom_events_manager_.domeventsmanager.md#onfirstshow)
* [onPreLoad](_src_scripts_dom_events_manager_.domeventsmanager.md#onpreload)
* [registerScrollable](_src_scripts_dom_events_manager_.domeventsmanager.md#registerscrollable)
* [subscribe](_src_scripts_dom_events_manager_.domeventsmanager.md#subscribe)
* [unregisterScrollable](_src_scripts_dom_events_manager_.domeventsmanager.md#unregisterscrollable)
* [unsubscribe](_src_scripts_dom_events_manager_.domeventsmanager.md#unsubscribe)

## Constructors

###  constructor

\+ **new DomEventsManager**(): *[DomEventsManager](_src_scripts_dom_events_manager_.domeventsmanager.md)*

Defined in src/scripts/dom-events-manager.ts:47

**Returns:** *[DomEventsManager](_src_scripts_dom_events_manager_.domeventsmanager.md)*

## Properties

###  _onDocumentResize

• **_onDocumentResize**: *DebouncedFunc‹(Anonymous function)›* = throttle((width, height) => {
        this.emitEvent(EVENTS.documentResize, [width, height]);
    })

Defined in src/scripts/dom-events-manager.ts:193

___

###  _onWindowResizeThrottled

• **_onWindowResizeThrottled**: *DebouncedFunc‹(Anonymous function)›* = throttle((args) => {
        this.emitEvent(EVENTS.windowResize, args);
    }, THROTTLE_DELAY)

Defined in src/scripts/dom-events-manager.ts:189

___

###  _onWindowScrollThrottled

• **_onWindowScrollThrottled**: *DebouncedFunc‹(Anonymous function)›* = throttle((args) => {
        this.emitEvent(EVENTS.windowScroll, args);
        this._checkVisibilitySubscribers();
    }, THROTTLE_DELAY)

Defined in src/scripts/dom-events-manager.ts:170

___

### `Protected` _screenSize

• **_screenSize**: *any*

Defined in src/scripts/dom-events-manager.ts:47

___

### `Protected` onPreloadObserver

• **onPreloadObserver**: *any*

Defined in src/scripts/dom-events-manager.ts:45

___

### `Protected` onScreenObserver

• **onScreenObserver**: *any*

Defined in src/scripts/dom-events-manager.ts:43

___

### `Protected` subscribers

• **subscribers**: *[Subscriber](_src_scripts_dom_events_manager_.subscriber.md)[]* = []

Defined in src/scripts/dom-events-manager.ts:39

___

### `Protected` visibilitySubscribers

• **visibilitySubscribers**: *any[]* = []

Defined in src/scripts/dom-events-manager.ts:41

## Methods

###  _addSubscriber

▸ **_addSubscriber**(`params`: any): *[Subscriber](_src_scripts_dom_events_manager_.subscriber.md)‹›*

Defined in src/scripts/dom-events-manager.ts:100

**Parameters:**

Name | Type |
------ | ------ |
`params` | any |

**Returns:** *[Subscriber](_src_scripts_dom_events_manager_.subscriber.md)‹›*

___

###  _checkVisibilitySubscribers

▸ **_checkVisibilitySubscribers**(): *void*

Defined in src/scripts/dom-events-manager.ts:197

**Returns:** *void*

___

###  _emitSubscribers

▸ **_emitSubscribers**(`eventName`: any, ...`params`: any[]): *void*

Defined in src/scripts/dom-events-manager.ts:117

**Parameters:**

Name | Type |
------ | ------ |
`eventName` | any |
`...params` | any[] |

**Returns:** *void*

___

###  _onDOMLoaded

▸ **_onDOMLoaded**(): *void*

Defined in src/scripts/dom-events-manager.ts:121

**Returns:** *void*

___

###  _onDocumentInteract

▸ **_onDocumentInteract**(`event`: any): *void*

Defined in src/scripts/dom-events-manager.ts:165

**Parameters:**

Name | Type |
------ | ------ |
`event` | any |

**Returns:** *void*

___

###  _onElementIntersection

▸ **_onElementIntersection**(`entries`: any): *void*

Defined in src/scripts/dom-events-manager.ts:131

**Parameters:**

Name | Type |
------ | ------ |
`entries` | any |

**Returns:** *void*

___

###  _onElementPreload

▸ **_onElementPreload**(`entries`: any): *void*

Defined in src/scripts/dom-events-manager.ts:147

**Parameters:**

Name | Type |
------ | ------ |
`entries` | any |

**Returns:** *void*

___

###  _onWindowResize

▸ **_onWindowResize**(): *void*

Defined in src/scripts/dom-events-manager.ts:175

**Returns:** *void*

___

###  _onWindowScroll

▸ **_onWindowScroll**(): *void*

Defined in src/scripts/dom-events-manager.ts:159

**Returns:** *void*

___

###  onElementVisible

▸ **onElementVisible**(`elementSelector`: any, `callback`: any): *void*

Defined in src/scripts/dom-events-manager.ts:80

**Parameters:**

Name | Type |
------ | ------ |
`elementSelector` | any |
`callback` | any |

**Returns:** *void*

___

###  onFirstShow

▸ **onFirstShow**(`element`: any, `callback`: any): *void*

Defined in src/scripts/dom-events-manager.ts:84

**Parameters:**

Name | Type |
------ | ------ |
`element` | any |
`callback` | any |

**Returns:** *void*

___

###  onPreLoad

▸ **onPreLoad**(`element`: any, `callback`: any): *void*

Defined in src/scripts/dom-events-manager.ts:88

**Parameters:**

Name | Type |
------ | ------ |
`element` | any |
`callback` | any |

**Returns:** *void*

___

###  registerScrollable

▸ **registerScrollable**(`element`: any): *void*

Defined in src/scripts/dom-events-manager.ts:92

**Parameters:**

Name | Type |
------ | ------ |
`element` | any |

**Returns:** *void*

___

###  subscribe

▸ **subscribe**(`instance`: any): *this*

Defined in src/scripts/dom-events-manager.ts:66

**Parameters:**

Name | Type |
------ | ------ |
`instance` | any |

**Returns:** *this*

___

###  unregisterScrollable

▸ **unregisterScrollable**(`element`: any): *void*

Defined in src/scripts/dom-events-manager.ts:96

**Parameters:**

Name | Type |
------ | ------ |
`element` | any |

**Returns:** *void*

___

###  unsubscribe

▸ **unsubscribe**(`instance`: any): *void*

Defined in src/scripts/dom-events-manager.ts:71

**Parameters:**

Name | Type |
------ | ------ |
`instance` | any |

**Returns:** *void*
