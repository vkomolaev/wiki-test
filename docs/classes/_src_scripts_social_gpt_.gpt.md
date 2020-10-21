[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/social/gpt"](../modules/_src_scripts_social_gpt_.md) › [GPT](_src_scripts_social_gpt_.gpt.md)

# Class: GPT

## Hierarchy

  ↳ [BaseModule](_src_scripts_base_module_.basemodule.md)

  ↳ **GPT**

## Index

### Constructors

* [constructor](_src_scripts_social_gpt_.gpt.md#constructor)

### Properties

* [_config](_src_scripts_social_gpt_.gpt.md#_config)
* [_disabled](_src_scripts_social_gpt_.gpt.md#_disabled)
* [_flushQueue](_src_scripts_social_gpt_.gpt.md#_flushqueue)
* [_flushReady](_src_scripts_social_gpt_.gpt.md#_flushready)
* [_flushSlotsComplete](_src_scripts_social_gpt_.gpt.md#_flushslotscomplete)
* [_flushSlotsDelay](_src_scripts_social_gpt_.gpt.md#_flushslotsdelay)
* [_flushSlotsTotal](_src_scripts_social_gpt_.gpt.md#_flushslotstotal)
* [_flushingSlots](_src_scripts_social_gpt_.gpt.md#_flushingslots)
* [apiLoaded](_src_scripts_social_gpt_.gpt.md#apiloaded)
* [apiLoading](_src_scripts_social_gpt_.gpt.md#apiloading)
* [apiUrl](_src_scripts_social_gpt_.gpt.md#apiurl)
* [appConfig](_src_scripts_social_gpt_.gpt.md#appconfig)
* [attempts](_src_scripts_social_gpt_.gpt.md#attempts)
* [autoResolve](_src_scripts_social_gpt_.gpt.md#autoresolve)
* [checkApiDelay](_src_scripts_social_gpt_.gpt.md#checkapidelay)
* [enableSingleRequest](_src_scripts_social_gpt_.gpt.md#enablesinglerequest)
* [maxAttempts](_src_scripts_social_gpt_.gpt.md#maxattempts)
* [moduleAwaiting](_src_scripts_social_gpt_.gpt.md#moduleawaiting)
* [options](_src_scripts_social_gpt_.gpt.md#options)

### Methods

* [_createSlot](_src_scripts_social_gpt_.gpt.md#_createslot)
* [_flushSlots](_src_scripts_social_gpt_.gpt.md#_flushslots)
* [_getSizeMapping](_src_scripts_social_gpt_.gpt.md#_getsizemapping)
* [_onApiLoaded](_src_scripts_social_gpt_.gpt.md#_onapiloaded)
* [_onSlotRendered](_src_scripts_social_gpt_.gpt.md#_onslotrendered)
* [_scheduleFlushSlots](_src_scripts_social_gpt_.gpt.md#_scheduleflushslots)
* [_updateSlot](_src_scripts_social_gpt_.gpt.md#_updateslot)
* [checkApi](_src_scripts_social_gpt_.gpt.md#checkapi)
* [create](_src_scripts_social_gpt_.gpt.md#create)
* [getApiUrl](_src_scripts_social_gpt_.gpt.md#getapiurl)
* [initialize](_src_scripts_social_gpt_.gpt.md#initialize)
* [isApiAvailable](_src_scripts_social_gpt_.gpt.md#isapiavailable)
* [loadApi](_src_scripts_social_gpt_.gpt.md#loadapi)
* [makeResponsiveSizesArray](_src_scripts_social_gpt_.gpt.md#makeresponsivesizesarray)
* [makeSizesArray](_src_scripts_social_gpt_.gpt.md#makesizesarray)
* [onApiLoaded](_src_scripts_social_gpt_.gpt.md#onapiloaded)
* [stackCommand](_src_scripts_social_gpt_.gpt.md#stackcommand)

## Constructors

###  constructor

\+ **new GPT**(): *[GPT](_src_scripts_social_gpt_.gpt.md)*

Defined in src/scripts/social/gpt.ts:78

**Returns:** *[GPT](_src_scripts_social_gpt_.gpt.md)*

## Properties

###  _config

• **_config**: *object*

Defined in src/scripts/social/gpt.ts:78

___

###  _disabled

• **_disabled**: *boolean* = false

Defined in src/scripts/social/gpt.ts:76

___

###  _flushQueue

• **_flushQueue**: *([SlotType](../modules/_src_scripts_social_gpt_.md#slottype) | function)[]* = []

Defined in src/scripts/social/gpt.ts:66

___

###  _flushReady

• **_flushReady**: *boolean* = false

Defined in src/scripts/social/gpt.ts:64

___

###  _flushSlotsComplete

• **_flushSlotsComplete**: *number* = 0

Defined in src/scripts/social/gpt.ts:72

___

###  _flushSlotsDelay

• **_flushSlotsDelay**: *number* = 1000

Defined in src/scripts/social/gpt.ts:70

___

###  _flushSlotsTotal

• **_flushSlotsTotal**: *number* = 0

Defined in src/scripts/social/gpt.ts:74

___

###  _flushingSlots

• **_flushingSlots**: *boolean* = false

Defined in src/scripts/social/gpt.ts:68

___

###  apiLoaded

• **apiLoaded**: *boolean* = false

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[apiLoaded](_src_scripts_base_module_.basemodule.md#apiloaded)*

Defined in src/scripts/base-module.ts:27

___

###  apiLoading

• **apiLoading**: *boolean* = false

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[apiLoading](_src_scripts_base_module_.basemodule.md#apiloading)*

Defined in src/scripts/base-module.ts:25

___

###  apiUrl

• **apiUrl**: *string* = ""

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[apiUrl](_src_scripts_base_module_.basemodule.md#apiurl)*

Defined in src/scripts/base-module.ts:23

___

###  appConfig

• **appConfig**: *object* = appConfig

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[appConfig](_src_scripts_base_module_.basemodule.md#appconfig)*

Defined in src/scripts/base-module.ts:21

#### Type declaration:

* **momentLocales**: *string[]* = ["en", "ar", "cs", "de", "fr", "id", "it", "zh"]

* ### **api**: *object*

  * **paths**: *object*

    * **cards**: *string* = "/api/cards"

    * **chromes**: *string* = "/api/chromes"

    * **chromesTabBar**: *string* = "/api/chromes/tab-bar"

    * **localization**: *string* = "/api/localization"

    * **page**: *string* = "/api/page"

    * **pageContent**: *string* = "/api/page/content"

    * **pages**: *string* = "/api/pages"

* ### **cdn**: *object*

  * **baseUrl**: *string* = "https://cdn.corebine.com/"

  * **geo**: *object*

    * **baseUrl**: *string* = "https://cdn.corebine.com/geo"

    * **countries**: *string* = "/countries.json"

    * **countryCities**: *string* = "/countries/{countryId}/cities.json"

    * **countryRegions**: *string* = "/countries/{countryId}/regions.json"

    * **countryRegionsCities**: *string* = "/countries/{countryId}/regions/{regionId}/cities.json"

  * **paths**: *object*

    * **flags**: *string* = "/flags"

* ### **cookieDisclaimer**: *object*

  * **declineLink**: *string* = "https://www.google.com"

* ### **dateTime**: *object*

  * **en**: *object*

    * **relativeTime**: *object*

      * **M**: *string* = "1 month"

      * **MM**: *string* = "%d months"

      * **d**: *string* = "1 day"

      * **dd**: *string* = "%d days"

      * **future**: *string* = "in %s"

      * **h**: *string* = "1 hour"

      * **hh**: *string* = "%d hours"

      * **m**: *string* = "1 minute"

      * **mm**: *string* = "%d minutes"

      * **past**: *string* = "%s ago"

      * **s**: *string* = "seconds"

      * **y**: *string* = "1 year"

      * **yy**: *string* = "%d years"

* ### **formats**: *object*

  * **date**: *string* = "DD MMM YYYY"

  * **decimal**: *number* = 2

  * **liveTickerDate**: *string* = "DD MMM YYYY"

  * **longScheduleDate**: *string* = "DD MMM YYYY"

  * **scheduleDate**: *string* = "DD MMM YYYY"

  * **time**: *string* = "HH:mm"

* ### **screenSizes**: *object*

  * **extra-large**: *object*

    * **max**: *number* = 3839

    * **min**: *number* = 1550

  * **large**: *object*

    * **max**: *number* = 1549

    * **min**: *number* = 1280

  * **max**: *object*

    * **max**: *number* = 99999

    * **min**: *number* = 3840

  * **medium**: *object*

    * **max**: *number* = 1279

    * **min**: *number* = 768

  * **small**: *object*

    * **max**: *number* = 767

    * **min**: *number* = 0

* ### **urls**: *object*

  * **countriesList**: *string* = "/data/countries.json"

  * **api**: *object*

    * **accesso**: *object*

      * **apiUrl**: *string* = "https://{clientId}.secure-cdn.accesso.com/embed/accesso.js"

    * **adobeLaunch**: *object*

      * **apiUrl**: *string* = "//assets.adobedtm.com/launch-{id}.min.js"

    * **auth0**: *object*

      * **apiUrl**: *string* = "https://cdn.auth0.com/js/lock/11.0.0/lock.min.js"

    * **facebook**: *object*

      * **apiUrl**: *string* = "//connect.facebook.net/en_US/sdk.js#xfbml=1"

    * **ga**: *object*

      * **apiUrl**: *string* = "//www.google-analytics.com/analytics.js"

    * **gigya**: *object*

      * **apiUrl**: *string* = "//cdn.gigya.com/JS/gigya.js?apikey="

    * **gpt**: *object*

      * **apiUrl**: *string* = "//www.googletagservices.com/tag/js/gpt.js"

    * **instagram**: *object*

      * **apiUrl**: *string* = "//platform.instagram.com/en_US/embeds.js"

      * **data**: *string* = "http://instagr.am/p/{socialId}/"

      * **oembed**: *string* = "http://api.instagram.com/oembed"

    * **opta**: *object*

      * **apiUrl**: *string* = "//asroma-optaproxy-prod.corebine.com/"

    * **recaptcha**: *object*

      * **apiUrl**: *string* = "//www.google.com/recaptcha/api.js"

    * **search**: *object*

      * **apiUrl**: *string* = "//www.google.com/jsapi"

    * **twitter**: *object*

      * **apiUrl**: *string* = "//platform.twitter.com/widgets.js"

    * **youtube**: *object*

      * **apiUrl**: *string* = "https://www.youtube.com/iframe_api"

    * **zendesk**: *object*

      * **apiUrl**: *string* = "https://assets.zendesk.com/embeddable_framework/main.js"

  * **device**: *object*

    * **corebineVideo**: *string* = "corebine://video/{videoId}/{videoType}"

  * **share**: *object*

    * **facebook**: *string* = "https://www.facebook.com/sharer/sharer.php?u={url}"

    * **mailto**: *string* = "mailto:{address}?subject={subject}&body={body}"

    * **pinterest**: *string* = "http://www.pinterest.com/pin/create/button/?url={url}&media={image_url}&description={text}"

    * **twitter**: *string* = "https://twitter.com/intent/tweet?url={url}&text={text}"

* ### **web**: *object*

  * **paths**: *object*

    * **login**: *string* = "/login"

    * **search**: *string* = "/search"

    * **tag**: *string* = "/tag"

___

###  attempts

• **attempts**: *number* = 0

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[attempts](_src_scripts_base_module_.basemodule.md#attempts)*

Defined in src/scripts/base-module.ts:31

___

###  autoResolve

• **autoResolve**: *boolean* = true

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[autoResolve](_src_scripts_base_module_.basemodule.md#autoresolve)*

Defined in src/scripts/base-module.ts:29

___

###  checkApiDelay

• **checkApiDelay**: *number* = 500

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[checkApiDelay](_src_scripts_base_module_.basemodule.md#checkapidelay)*

Defined in src/scripts/base-module.ts:35

___

###  enableSingleRequest

• **enableSingleRequest**: *boolean* = true

Defined in src/scripts/social/gpt.ts:62

___

###  maxAttempts

• **maxAttempts**: *number* = 10

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[maxAttempts](_src_scripts_base_module_.basemodule.md#maxattempts)*

Defined in src/scripts/base-module.ts:33

___

###  moduleAwaiting

• **moduleAwaiting**: *[DeferredType](../modules/_src_scripts_utils_deferred_.md#deferredtype)* = Deferred()

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[moduleAwaiting](_src_scripts_base_module_.basemodule.md#moduleawaiting)*

Defined in src/scripts/base-module.ts:37

___

###  options

• **options**: *any*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[options](_src_scripts_base_module_.basemodule.md#options)*

Defined in src/scripts/base-module.ts:19

## Methods

###  _createSlot

▸ **_createSlot**(`elementId`: string, `unitId`: string, `defaultSize`: [SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple)[], `responsiveSize`: [ResponsiveSizes](../modules/_src_scripts_social_gpt_.md#responsivesizes), `callback`: function): *function*

Defined in src/scripts/social/gpt.ts:113

**Parameters:**

▪ **elementId**: *string*

▪ **unitId**: *string*

▪ **defaultSize**: *[SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple)[]*

▪ **responsiveSize**: *[ResponsiveSizes](../modules/_src_scripts_social_gpt_.md#responsivesizes)*

▪ **callback**: *function*

▸ (`slot`: [SlotType](../modules/_src_scripts_social_gpt_.md#slottype)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`slot` | [SlotType](../modules/_src_scripts_social_gpt_.md#slottype) |

**Returns:** *function*

▸ (): *[SlotType](../modules/_src_scripts_social_gpt_.md#slottype)*

___

###  _flushSlots

▸ **_flushSlots**(): *void*

Defined in src/scripts/social/gpt.ts:180

**Returns:** *void*

___

###  _getSizeMapping

▸ **_getSizeMapping**(`responsiveSize`: [ResponsiveSizes](../modules/_src_scripts_social_gpt_.md#responsivesizes)): *([SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple) | [SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple)[])[][]*

Defined in src/scripts/social/gpt.ts:151

**Parameters:**

Name | Type |
------ | ------ |
`responsiveSize` | [ResponsiveSizes](../modules/_src_scripts_social_gpt_.md#responsivesizes) |

**Returns:** *([SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple) | [SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple)[])[][]*

___

###  _onApiLoaded

▸ **_onApiLoaded**(...`args`: any): *void*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[_onApiLoaded](_src_scripts_base_module_.basemodule.md#_onapiloaded)*

Defined in src/scripts/base-module.ts:93

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any |

**Returns:** *void*

___

###  _onSlotRendered

▸ **_onSlotRendered**(): *void*

Defined in src/scripts/social/gpt.ts:228

**Returns:** *void*

___

###  _scheduleFlushSlots

▸ **_scheduleFlushSlots**(): *void*

Defined in src/scripts/social/gpt.ts:170

**Returns:** *void*

___

###  _updateSlot

▸ **_updateSlot**(`slot`: [SlotType](../modules/_src_scripts_social_gpt_.md#slottype) | function): *void*

Defined in src/scripts/social/gpt.ts:144

**Parameters:**

Name | Type |
------ | ------ |
`slot` | [SlotType](../modules/_src_scripts_social_gpt_.md#slottype) &#124; function |

**Returns:** *void*

___

###  checkApi

▸ **checkApi**(): *void*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[checkApi](_src_scripts_base_module_.basemodule.md#checkapi)*

Defined in src/scripts/base-module.ts:52

**Returns:** *void*

___

###  create

▸ **create**(`elementId`: string, `unitId`: string, `defaultSize`: [SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple)[], `responsiveSize`: [ResponsiveSizes](../modules/_src_scripts_social_gpt_.md#responsivesizes)): *[CreatedGPTSlot](../modules/_src_scripts_social_gpt_.md#createdgptslot) | boolean*

Defined in src/scripts/social/gpt.ts:94

**Parameters:**

Name | Type |
------ | ------ |
`elementId` | string |
`unitId` | string |
`defaultSize` | [SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple)[] |
`responsiveSize` | [ResponsiveSizes](../modules/_src_scripts_social_gpt_.md#responsivesizes) |

**Returns:** *[CreatedGPTSlot](../modules/_src_scripts_social_gpt_.md#createdgptslot) | boolean*

___

###  getApiUrl

▸ **getApiUrl**(): *string*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[getApiUrl](_src_scripts_base_module_.basemodule.md#getapiurl)*

Defined in src/scripts/base-module.ts:71

**Returns:** *string*

___

###  initialize

▸ **initialize**(`config`: object, `disabled`: boolean): *void*

*Overrides [BaseModule](_src_scripts_base_module_.basemodule.md).[initialize](_src_scripts_base_module_.basemodule.md#initialize)*

Defined in src/scripts/social/gpt.ts:85

**Parameters:**

Name | Type |
------ | ------ |
`config` | object |
`disabled` | boolean |

**Returns:** *void*

___

###  isApiAvailable

▸ **isApiAvailable**(): *boolean*

*Overrides [BaseModule](_src_scripts_base_module_.basemodule.md).[isApiAvailable](_src_scripts_base_module_.basemodule.md#isapiavailable)*

Defined in src/scripts/social/gpt.ts:90

**Returns:** *boolean*

___

###  loadApi

▸ **loadApi**(): *void*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[loadApi](_src_scripts_base_module_.basemodule.md#loadapi)*

Defined in src/scripts/base-module.ts:75

**Returns:** *void*

___

###  makeResponsiveSizesArray

▸ **makeResponsiveSizesArray**(`data`: ResponsiveAd): *[ResponsiveSizes](../modules/_src_scripts_social_gpt_.md#responsivesizes)*

Defined in src/scripts/social/gpt.ts:248

**Parameters:**

Name | Type |
------ | ------ |
`data` | ResponsiveAd |

**Returns:** *[ResponsiveSizes](../modules/_src_scripts_social_gpt_.md#responsivesizes)*

___

###  makeSizesArray

▸ **makeSizesArray**(`data`: [Size](../modules/_src_scripts_types_.md#size)[]): *[SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple)[]*

Defined in src/scripts/social/gpt.ts:240

**Parameters:**

Name | Type |
------ | ------ |
`data` | [Size](../modules/_src_scripts_types_.md#size)[] |

**Returns:** *[SizeTuple](../modules/_src_scripts_social_gpt_.md#sizetuple)[]*

___

###  onApiLoaded

▸ **onApiLoaded**(...`args`: any): *void*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[onApiLoaded](_src_scripts_base_module_.basemodule.md#onapiloaded)*

Defined in src/scripts/base-module.ts:102

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any |

**Returns:** *void*

___

###  stackCommand

▸ **stackCommand**(`command`: function): *void*

Defined in src/scripts/social/gpt.ts:236

**Parameters:**

▪ **command**: *function*

▸ (): *void*

**Returns:** *void*
