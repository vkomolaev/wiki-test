[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/social/gpt"](_src_scripts_social_gpt_.md)

# Module: "src/scripts/social/gpt"

## Index

### Namespaces

* [__global](_src_scripts_social_gpt_.__global.md)

### Classes

* [GPT](../classes/_src_scripts_social_gpt_.gpt.md)

### Type aliases

* [CreatedGPTSlot](_src_scripts_social_gpt_.md#createdgptslot)
* [ResponsiveSizes](_src_scripts_social_gpt_.md#responsivesizes)
* [SizeTuple](_src_scripts_social_gpt_.md#sizetuple)
* [SlotType](_src_scripts_social_gpt_.md#slottype)

### Variables

* [googletag](_src_scripts_social_gpt_.md#const-googletag)
* [gpt](_src_scripts_social_gpt_.md#const-gpt)

## Type aliases

###  CreatedGPTSlot

Ƭ **CreatedGPTSlot**: *object*

Defined in src/scripts/social/gpt.ts:40

#### Type declaration:

* **update**(): *function*

  * (): *void*

___

###  ResponsiveSizes

Ƭ **ResponsiveSizes**: *([SizeTuple](_src_scripts_social_gpt_.md#sizetuple) | [SizeTuple](_src_scripts_social_gpt_.md#sizetuple)[])[][]*

Defined in src/scripts/social/gpt.ts:46

___

###  SizeTuple

Ƭ **SizeTuple**: *[number, number]*

Defined in src/scripts/social/gpt.ts:44

___

###  SlotType

Ƭ **SlotType**: *object*

Defined in src/scripts/social/gpt.ts:48

#### Type declaration:

* **displayed**: *boolean*

* **getDomId**(): *function*

  * (): *string*

* **getSlotId**(): *function*

  * (): *[SlotType](_src_scripts_social_gpt_.md#slottype)*

* **addService**(`pubads`: [pubadsType](_src_scripts_social_gpt_.__global.md#pubadstype)): *void*

* **defineSizeMapping**(`sizeMapping`: [ResponsiveSizes](_src_scripts_social_gpt_.md#responsivesizes)): *void*

## Variables

### `Const` googletag

• **googletag**: *object* = window.googletag

Defined in src/scripts/social/gpt.ts:57

#### Type declaration:

* **apiReady**? : *boolean*

* **cmd**? : *function[]*

* **defineSlot**(`slotName`: string, `defaultSize`: [SizeTuple](_src_scripts_social_gpt_.md#sizetuple)[], `elementId`: string): *[SlotType](_src_scripts_social_gpt_.md#slottype)*

* **display**(`slotId`: string): *void*

* **enableServices**(): *void*

* **pubads**(): *[pubadsType](_src_scripts_social_gpt_.__global.md#pubadstype)*

___

### `Const` gpt

• **gpt**: *[GPT](../classes/_src_scripts_social_gpt_.gpt.md)‹›* = new GPT()

Defined in src/scripts/social/gpt.ts:267
