[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/ad-dfp/ad-dfp"](_src_markups_components_ad_dfp_ad_dfp_.md)

# Module: "src/markups/components/ad-dfp/ad-dfp"

## Index

### Classes

* [AdDfp](../classes/_src_markups_components_ad_dfp_ad_dfp_.addfp.md)

### Type aliases

* [AdDfpProps](_src_markups_components_ad_dfp_ad_dfp_.md#addfpprops)
* [AdDfpState](_src_markups_components_ad_dfp_ad_dfp_.md#addfpstate)
* [AdSize](_src_markups_components_ad_dfp_ad_dfp_.md#adsize)

### Functions

* [hydrate](_src_markups_components_ad_dfp_ad_dfp_.md#hydrate)
* [render](_src_markups_components_ad_dfp_ad_dfp_.md#render)

## Type aliases

###  AdDfpProps

Ƭ **AdDfpProps**: *object*

Defined in src/markups/components/ad-dfp/ad-dfp.tsx:24

#### Type declaration:

* **className**? : *string*

* **responsiveSizes**? : *[AdSize](_src_markups_components_ad_dfp_ad_dfp_.md#adsize)[]*

* **sizes**? : *[Size](_src_scripts_types_.md#size)[]*

* **unitId**? : *string*

___

###  AdDfpState

Ƭ **AdDfpState**: *object*

Defined in src/markups/components/ad-dfp/ad-dfp.tsx:35

#### Type declaration:

* **adId**: *string*

* **slot**: *[CreatedGPTSlot](_src_scripts_social_gpt_.md#createdgptslot)*

___

###  AdSize

Ƭ **AdSize**: *object*

Defined in src/markups/components/ad-dfp/ad-dfp.tsx:19

#### Type declaration:

* **screenSize**: *[Size](_src_scripts_types_.md#size)*

* **sizes**: *[Size](_src_scripts_types_.md#size)[]*

## Functions

###  hydrate

▸ **hydrate**(`props`: [AdDfpProps](_src_markups_components_ad_dfp_ad_dfp_.md#addfpprops), `targetElement`: HTMLElement, `callback`: function): *void*

Defined in src/markups/components/ad-dfp/ad-dfp.tsx:115

**Parameters:**

▪ **props**: *[AdDfpProps](_src_markups_components_ad_dfp_ad_dfp_.md#addfpprops)*

▪ **targetElement**: *HTMLElement*

▪ **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

###  render

▸ **render**(`props`: [AdDfpProps](_src_markups_components_ad_dfp_ad_dfp_.md#addfpprops), `targetElement`: HTMLElement): *void*

Defined in src/markups/components/ad-dfp/ad-dfp.tsx:108

**Parameters:**

Name | Type |
------ | ------ |
`props` | [AdDfpProps](_src_markups_components_ad_dfp_ad_dfp_.md#addfpprops) |
`targetElement` | HTMLElement |

**Returns:** *void*
