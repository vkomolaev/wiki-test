[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/analytics/data-layer/data-layer"](../modules/_src_scripts_analytics_data_layer_data_layer_.md) › [DataLayer](_src_scripts_analytics_data_layer_data_layer_.datalayer.md)

# Class: DataLayer

## Hierarchy

* **DataLayer**

## Index

### Constructors

* [constructor](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#constructor)

### Properties

* [onWindowScroll](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#onwindowscroll)
* [trackingElementAttribute](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#trackingelementattribute)
* [trackingElementHoverAttribute](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#trackingelementhoverattribute)
* [trackingLinkLevel](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#trackinglinklevel)
* [trackingModuleAttribute](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#trackingmoduleattribute)
* [trackingModuleIdAttribute](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#trackingmoduleidattribute)

### Methods

* [findModule](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#findmodule)
* [setupTrackers](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#setuptrackers)
* [track](_src_scripts_analytics_data_layer_data_layer_.datalayer.md#track)

## Constructors

###  constructor

\+ **new DataLayer**(): *[DataLayer](_src_scripts_analytics_data_layer_data_layer_.datalayer.md)*

Defined in src/scripts/analytics/data-layer/data-layer.js:27

**Returns:** *[DataLayer](_src_scripts_analytics_data_layer_data_layer_.datalayer.md)*

## Properties

###  onWindowScroll

• **onWindowScroll**: *DebouncedFunc‹(Anonymous function)›* = _.throttle(() => {
        const {scrollTop, scrollHeight} = document.documentElement;
        const percentage = (scrollTop / scrollHeight) * 100;
        this.track('body', document.body, 'scroll', {trackPercentage: percentage}, {module: 'page'});
    }, 1000)

Defined in src/scripts/analytics/data-layer/data-layer.js:34

___

###  trackingElementAttribute

• **trackingElementAttribute**: *string* = "trackElement"

Defined in src/scripts/analytics/data-layer/data-layer.js:19

___

###  trackingElementHoverAttribute

• **trackingElementHoverAttribute**: *string* = "trackElementHover"

Defined in src/scripts/analytics/data-layer/data-layer.js:21

___

###  trackingLinkLevel

• **trackingLinkLevel**: *number* = 5

Defined in src/scripts/analytics/data-layer/data-layer.js:27

___

###  trackingModuleAttribute

• **trackingModuleAttribute**: *string* = "trackModule"

Defined in src/scripts/analytics/data-layer/data-layer.js:23

___

###  trackingModuleIdAttribute

• **trackingModuleIdAttribute**: *string* = "trackModuleId"

Defined in src/scripts/analytics/data-layer/data-layer.js:25

## Methods

###  findModule

▸ **findModule**(`element`: any): *object | object*

Defined in src/scripts/analytics/data-layer/data-layer.js:76

**Parameters:**

Name | Type |
------ | ------ |
`element` | any |

**Returns:** *object | object*

___

###  setupTrackers

▸ **setupTrackers**(): *void*

Defined in src/scripts/analytics/data-layer/data-layer.js:40

**Returns:** *void*

___

###  track

▸ **track**(`element`: any, `target`: any, `action`: any, `dataset`: any, `moduleData`: any): *void*

Defined in src/scripts/analytics/data-layer/data-layer.js:90

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`element` | any | - |
`target` | any | - |
`action` | any | - |
`dataset` | any | null |
`moduleData` | any | null |

**Returns:** *void*
