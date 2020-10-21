[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/social/twitter"](../modules/_src_scripts_social_twitter_.md) › [Twitter](_src_scripts_social_twitter_.twitter.md)

# Class: Twitter

## Hierarchy

  ↳ [BaseModule](_src_scripts_base_module_.basemodule.md)

  ↳ **Twitter**

## Index

### Constructors

* [constructor](_src_scripts_social_twitter_.twitter.md#constructor)

### Properties

* [apiLoaded](_src_scripts_social_twitter_.twitter.md#apiloaded)
* [apiLoading](_src_scripts_social_twitter_.twitter.md#apiloading)
* [apiUrl](_src_scripts_social_twitter_.twitter.md#apiurl)
* [appConfig](_src_scripts_social_twitter_.twitter.md#appconfig)
* [attempts](_src_scripts_social_twitter_.twitter.md#attempts)
* [autoResolve](_src_scripts_social_twitter_.twitter.md#autoresolve)
* [checkApiDelay](_src_scripts_social_twitter_.twitter.md#checkapidelay)
* [maxAttempts](_src_scripts_social_twitter_.twitter.md#maxattempts)
* [moduleAwaiting](_src_scripts_social_twitter_.twitter.md#moduleawaiting)
* [options](_src_scripts_social_twitter_.twitter.md#options)

### Methods

* [_onApiLoaded](_src_scripts_social_twitter_.twitter.md#_onapiloaded)
* [checkApi](_src_scripts_social_twitter_.twitter.md#checkapi)
* [getApiUrl](_src_scripts_social_twitter_.twitter.md#getapiurl)
* [initialize](_src_scripts_social_twitter_.twitter.md#initialize)
* [isApiAvailable](_src_scripts_social_twitter_.twitter.md#isapiavailable)
* [loadApi](_src_scripts_social_twitter_.twitter.md#loadapi)
* [onApiLoaded](_src_scripts_social_twitter_.twitter.md#onapiloaded)

## Constructors

###  constructor

\+ **new Twitter**(): *[Twitter](_src_scripts_social_twitter_.twitter.md)*

Defined in src/scripts/social/twitter.js:16

**Returns:** *[Twitter](_src_scripts_social_twitter_.twitter.md)*

## Properties

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

###  checkApi

▸ **checkApi**(): *void*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[checkApi](_src_scripts_base_module_.basemodule.md#checkapi)*

Defined in src/scripts/base-module.ts:52

**Returns:** *void*

___

###  getApiUrl

▸ **getApiUrl**(): *string*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[getApiUrl](_src_scripts_base_module_.basemodule.md#getapiurl)*

Defined in src/scripts/base-module.ts:71

**Returns:** *string*

___

###  initialize

▸ **initialize**(`options?`: object): *Promise‹any›*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[initialize](_src_scripts_base_module_.basemodule.md#initialize)*

Defined in src/scripts/base-module.ts:39

**Parameters:**

Name | Type |
------ | ------ |
`options?` | object |

**Returns:** *Promise‹any›*

___

###  isApiAvailable

▸ **isApiAvailable**(): *boolean*

*Overrides [BaseModule](_src_scripts_base_module_.basemodule.md).[isApiAvailable](_src_scripts_base_module_.basemodule.md#isapiavailable)*

Defined in src/scripts/social/twitter.js:23

**Returns:** *boolean*

___

###  loadApi

▸ **loadApi**(): *void*

*Inherited from [BaseModule](_src_scripts_base_module_.basemodule.md).[loadApi](_src_scripts_base_module_.basemodule.md#loadapi)*

Defined in src/scripts/base-module.ts:75

**Returns:** *void*

___

###  onApiLoaded

▸ **onApiLoaded**(): *void*

*Overrides [BaseModule](_src_scripts_base_module_.basemodule.md).[onApiLoaded](_src_scripts_base_module_.basemodule.md#onapiloaded)*

Defined in src/scripts/social/twitter.js:27

**Returns:** *void*
