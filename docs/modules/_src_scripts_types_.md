[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/types"](_src_scripts_types_.md)

# Module: "src/scripts/types"

## Index

### Type aliases

* [ActionItem](_src_scripts_types_.md#actionitem)
* [ActionType](_src_scripts_types_.md#actiontype)
* [AnyDate](_src_scripts_types_.md#anydate)
* [BootstrapLocale](_src_scripts_types_.md#bootstraplocale)
* [CorebinePageData](_src_scripts_types_.md#corebinepagedata)
* [CorebinePageOptions](_src_scripts_types_.md#corebinepageoptions)
* [CorebinePageResponse](_src_scripts_types_.md#corebinepageresponse)
* [FeedSourceBase](_src_scripts_types_.md#feedsourcebase)
* [Size](_src_scripts_types_.md#size)
* [TrackingAttributes](_src_scripts_types_.md#trackingattributes)

## Type aliases

###  ActionItem

Ƭ **ActionItem**: *object*

Defined in src/scripts/types.ts:23

#### Type declaration:

* **action**: *[ActionType](_src_scripts_types_.md#actiontype)*

* **items**: *[ActionItem](_src_scripts_types_.md#actionitem)[]*

___

###  ActionType

Ƭ **ActionType**: *object*

Defined in src/scripts/types.ts:17

#### Type declaration:

* **actionType**? : *string*

* **caption**: *string*

* **link**? : *[LinkData](_src_markups_components_link_link_.md#linkdata)*

___

###  AnyDate

Ƭ **AnyDate**: *string | Moment | Date*

Defined in src/scripts/types.ts:15

___

###  BootstrapLocale

Ƭ **BootstrapLocale**: *object*

Defined in src/scripts/types.ts:43

#### Type declaration:

* **code**: *string*

* **key**: *string*

* **name**: *string*

___

###  CorebinePageData

Ƭ **CorebinePageData**: *object*

Defined in src/scripts/types.ts:53

#### Type declaration:

* **_disabled**? : *boolean*

* **_entityId**? : *string*

* **_ref**? : *boolean*

* **_type**? : *string*

* **content**? : *[CorebinePageData](_src_scripts_types_.md#corebinepagedata)[]*

* **contentId**? : *string*

* **interstitials**? : *[CorebinePageData](_src_scripts_types_.md#corebinepagedata)[]*

* **link**? : *string*

* **meta**(): *object*

  * **ampReady**: *boolean*

* **pageType**? : *string*

* **title**? : *string*

* **trackingId**? : *string*

___

###  CorebinePageOptions

Ƭ **CorebinePageOptions**: *object*

Defined in src/scripts/types.ts:71

#### Type declaration:

* **bootstrap**(): *object*

  * **web**(): *object*

    * **baseUrl**: *string*

* **config**(): *object*

* **page**(): *object*

  * **devMode**: *boolean*

  * **lang**: *string*

  * **locale**: *string*

  * **native**: *boolean*

* **templateTypes**(): *object*

___

###  CorebinePageResponse

Ƭ **CorebinePageResponse**: *object*

Defined in src/scripts/types.ts:49

#### Type declaration:

* **data**: *[CorebinePageData](_src_scripts_types_.md#corebinepagedata)*

___

###  FeedSourceBase

Ƭ **FeedSourceBase**: *object*

Defined in src/scripts/types.ts:38

#### Type declaration:

* **_type**: *string*

* **query**? : *string*

___

###  Size

Ƭ **Size**: *object*

Defined in src/scripts/types.ts:28

#### Type declaration:

* **height**: *number*

* **width**: *number*

___

###  TrackingAttributes

Ƭ **TrackingAttributes**: *object*

Defined in src/scripts/types.ts:33

#### Type declaration:

* **data-track-module**? : *string*

* **data-track-module-id**? : *string*
