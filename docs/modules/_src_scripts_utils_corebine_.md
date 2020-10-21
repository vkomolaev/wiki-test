[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/corebine"](_src_scripts_utils_corebine_.md)

# Module: "src/scripts/utils/corebine"

## Index

### Type aliases

* [ModulesDataTree](_src_scripts_utils_corebine_.md#modulesdatatree)

### Variables

* [ACCESSO_LINK](_src_scripts_utils_corebine_.md#const-accesso_link)
* [CAROUSEL_MODULE](_src_scripts_utils_corebine_.md#const-carousel_module)

### Object literals

* [corebineUtils](_src_scripts_utils_corebine_.md#const-corebineutils)

## Type aliases

###  ModulesDataTree

Ƭ **ModulesDataTree**: *T & object*

Defined in src/scripts/utils/corebine.ts:24

## Variables

### `Const` ACCESSO_LINK

• **ACCESSO_LINK**: *"Corebine.Core.Type.Link.Tickets.Accesso"* = "Corebine.Core.Type.Link.Tickets.Accesso"

Defined in src/scripts/utils/corebine.ts:22

___

### `Const` CAROUSEL_MODULE

• **CAROUSEL_MODULE**: *"Corebine.Core.Page.Content.Module.Carousel"* = "Corebine.Core.Page.Content.Module.Carousel"

Defined in src/scripts/utils/corebine.ts:21

## Object literals

### `Const` corebineUtils

### ▪ **corebineUtils**: *object*

Defined in src/scripts/utils/corebine.ts:28

###  getBreadcrumbs

▸ **getBreadcrumbs**(`props`: any): *any[]*

Defined in src/scripts/utils/corebine.ts:285

**Parameters:**

Name | Type |
------ | ------ |
`props` | any |

**Returns:** *any[]*

###  getFeedUrl

▸ **getFeedUrl**(`url`: string, `page`: number, `source`: [FeedSourceBase](_src_scripts_types_.md#feedsourcebase)): *string*

Defined in src/scripts/utils/corebine.ts:214

**Parameters:**

Name | Type |
------ | ------ |
`url` | string |
`page` | number |
`source` | [FeedSourceBase](_src_scripts_types_.md#feedsourcebase) |

**Returns:** *string*

###  getGenericPageType

▸ **getGenericPageType**(`pageType`: string): *string*

Defined in src/scripts/utils/corebine.ts:40

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`pageType` | string | "" |

**Returns:** *string*

###  getImageUrl

▸ **getImageUrl**(`image`: any): *string*

Defined in src/scripts/utils/corebine.ts:48

**Parameters:**

Name | Type |
------ | ------ |
`image` | any |

**Returns:** *string*

###  getInterstitialObj

▸ **getInterstitialObj**(`interstitials?`: [CorebinePageData](_src_scripts_types_.md#corebinepagedata)[]): *[CorebinePageData](_src_scripts_types_.md#corebinepagedata)*

Defined in src/scripts/utils/corebine.ts:30

**Parameters:**

Name | Type |
------ | ------ |
`interstitials?` | [CorebinePageData](_src_scripts_types_.md#corebinepagedata)[] |

**Returns:** *[CorebinePageData](_src_scripts_types_.md#corebinepagedata)*

###  getLinkTarget

▸ **getLinkTarget**(`link?`: [LinkData](_src_markups_components_link_link_.md#linkdata)): *string*

Defined in src/scripts/utils/corebine.ts:124

**Parameters:**

Name | Type |
------ | ------ |
`link?` | [LinkData](_src_markups_components_link_link_.md#linkdata) |

**Returns:** *string*

###  getLinkUrl

▸ **getLinkUrl**(`link?`: [LinkData](_src_markups_components_link_link_.md#linkdata)): *string*

Defined in src/scripts/utils/corebine.ts:87

**Parameters:**

Name | Type |
------ | ------ |
`link?` | [LinkData](_src_markups_components_link_link_.md#linkdata) |

**Returns:** *string*

###  getPageContentUrl

▸ **getPageContentUrl**(`url`: string, `source`: [FeedSourceBase](_src_scripts_types_.md#feedsourcebase)): *string*

Defined in src/scripts/utils/corebine.ts:227

**Parameters:**

Name | Type |
------ | ------ |
`url` | string |
`source` | [FeedSourceBase](_src_scripts_types_.md#feedsourcebase) |

**Returns:** *string*

###  getSiteSetting

▸ **getSiteSetting**(`category`: string, `predicate`: any, `property?`: string): *any*

Defined in src/scripts/utils/corebine.ts:61

**Parameters:**

Name | Type |
------ | ------ |
`category` | string |
`predicate` | any |
`property?` | string |

**Returns:** *any*

###  getSiteSettingProvider

▸ **getSiteSettingProvider**(`category`: string, `type`: string, `property?`: string): *any*

Defined in src/scripts/utils/corebine.ts:74

**Parameters:**

Name | Type |
------ | ------ |
`category` | string |
`type` | string |
`property?` | string |

**Returns:** *any*

###  getStickyHeight

▸ **getStickyHeight**(): *number*

Defined in src/scripts/utils/corebine.ts:240

**Returns:** *number*

###  getStickyOffset

▸ **getStickyOffset**(): *number*

Defined in src/scripts/utils/corebine.ts:244

**Returns:** *number*

###  getStickyRects

▸ **getStickyRects**(): *DOMRect[]*

Defined in src/scripts/utils/corebine.ts:235

**Returns:** *DOMRect[]*

###  getTagUrl

▸ **getTagUrl**(`tag`: [Tag](_src_markups_components_tags_tags_.md#tag)): *string*

Defined in src/scripts/utils/corebine.ts:186

**Parameters:**

Name | Type |
------ | ------ |
`tag` | [Tag](_src_markups_components_tags_tags_.md#tag) |

**Returns:** *string*

###  getTrackingAttributes

▸ **getTrackingAttributes**(`name`: string, ...`args`: any[]): *any*

Defined in src/scripts/utils/corebine.ts:174

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |
`...args` | any[] |

**Returns:** *any*

###  getTrackingAttributesByName

▸ **getTrackingAttributesByName**(`name`: string): *any*

Defined in src/scripts/utils/corebine.ts:167

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |

**Returns:** *any*

###  getUrlLang

▸ **getUrlLang**(`key?`: string): *string*

Defined in src/scripts/utils/corebine.ts:112

**Parameters:**

Name | Type |
------ | ------ |
`key?` | string |

**Returns:** *string*

###  getWebPath

▸ **getWebPath**(`alias?`: string): *string*

Defined in src/scripts/utils/corebine.ts:194

**Parameters:**

Name | Type |
------ | ------ |
`alias?` | string |

**Returns:** *string*

###  isCarouselFirst

▸ **isCarouselFirst**(): *boolean*

Defined in src/scripts/utils/corebine.ts:57

**Returns:** *boolean*

###  isDevMode

▸ **isDevMode**(): *boolean*

Defined in src/scripts/utils/corebine.ts:82

**Returns:** *boolean*

###  isPageType

▸ **isPageType**(`pageType`: string): *boolean*

Defined in src/scripts/utils/corebine.ts:44

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`pageType` | string | "" |

**Returns:** *boolean*

###  isPreviewPage

▸ **isPreviewPage**(): *boolean*

Defined in src/scripts/utils/corebine.ts:292

**Returns:** *boolean*

###  isRtl

▸ **isRtl**(): *boolean*

Defined in src/scripts/utils/corebine.ts:181

**Returns:** *boolean*

###  isTransparentNavigation

▸ **isTransparentNavigation**(): *boolean*

Defined in src/scripts/utils/corebine.ts:200

**Returns:** *boolean*

###  processDataTree

▸ **processDataTree**‹**T**›(`data`: [CorebinePageData](_src_scripts_types_.md#corebinepagedata), `processModule`: function): *[ModulesDataTree](_src_scripts_utils_corebine_.md#modulesdatatree)‹T›*

Defined in src/scripts/utils/corebine.ts:271

**Type parameters:**

▪ **T**

**Parameters:**

▪ **data**: *[CorebinePageData](_src_scripts_types_.md#corebinepagedata)*

▪ **processModule**: *function*

▸ (`node`: [CorebinePageData](_src_scripts_types_.md#corebinepagedata)): *any*

**Parameters:**

Name | Type |
------ | ------ |
`node` | [CorebinePageData](_src_scripts_types_.md#corebinepagedata) |

**Returns:** *[ModulesDataTree](_src_scripts_utils_corebine_.md#modulesdatatree)‹T›*

###  resolveIncludes

▸ **resolveIncludes**(`data`: [CorebinePageData](_src_scripts_types_.md#corebinepagedata) | [CorebinePageData](_src_scripts_types_.md#corebinepagedata)[], `includes`: [CorebinePageData](_src_scripts_types_.md#corebinepagedata)[]): *void*

Defined in src/scripts/utils/corebine.ts:248

**Parameters:**

Name | Type |
------ | ------ |
`data` | [CorebinePageData](_src_scripts_types_.md#corebinepagedata) &#124; [CorebinePageData](_src_scripts_types_.md#corebinepagedata)[] |
`includes` | [CorebinePageData](_src_scripts_types_.md#corebinepagedata)[] |

**Returns:** *void*

###  updateQueryString

▸ **updateQueryString**(`key`: string, `value`: string, `url`: string): *string*

Defined in src/scripts/utils/corebine.ts:138

**Parameters:**

Name | Type |
------ | ------ |
`key` | string |
`value` | string |
`url` | string |

**Returns:** *string*
