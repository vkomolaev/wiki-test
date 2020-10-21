[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/window-size-manager"](_src_scripts_window_size_manager_.md)

# Module: "src/scripts/window-size-manager"

## Index

### Classes

* [WindowSizeManager](../classes/_src_scripts_window_size_manager_.windowsizemanager.md)

### Type aliases

* [ScreenName](_src_scripts_window_size_manager_.md#screenname)
* [ScreenShortName](_src_scripts_window_size_manager_.md#screenshortname)
* [ScreenShortSizes](_src_scripts_window_size_manager_.md#screenshortsizes)
* [ScreenSizes](_src_scripts_window_size_manager_.md#screensizes)
* [ViewportSizes](_src_scripts_window_size_manager_.md#viewportsizes)

### Functions

* [sizesToShort](_src_scripts_window_size_manager_.md#sizestoshort)

### Object literals

* [SIZES_SHORT](_src_scripts_window_size_manager_.md#const-sizes_short)

## Type aliases

###  ScreenName

Ƭ **ScreenName**: *"small" | "medium" | "large" | "extra-large" | "max"*

Defined in src/scripts/window-size-manager.ts:16

___

###  ScreenShortName

Ƭ **ScreenShortName**: *"s" | "m" | "l" | "xl" | "max"*

Defined in src/scripts/window-size-manager.ts:17

___

###  ScreenShortSizes

Ƭ **ScreenShortSizes**: *object*

Defined in src/scripts/window-size-manager.ts:41

#### Type declaration:

___

###  ScreenSizes

Ƭ **ScreenSizes**: *object*

Defined in src/scripts/window-size-manager.ts:36

#### Type declaration:

___

###  ViewportSizes

Ƭ **ViewportSizes**: *object*

Defined in src/scripts/window-size-manager.ts:29

#### Type declaration:

* **max**: *number*

* **min**: *number*

## Functions

###  sizesToShort

▸ **sizesToShort**(`sizes`: [ScreenSizes](_src_scripts_window_size_manager_.md#screensizes)): *[ScreenShortSizes](_src_scripts_window_size_manager_.md#screenshortsizes) | any*

Defined in src/scripts/window-size-manager.ts:112

**Parameters:**

Name | Type |
------ | ------ |
`sizes` | [ScreenSizes](_src_scripts_window_size_manager_.md#screensizes) |

**Returns:** *[ScreenShortSizes](_src_scripts_window_size_manager_.md#screenshortsizes) | any*

## Object literals

### `Const` SIZES_SHORT

### ▪ **SIZES_SHORT**: *object*

Defined in src/scripts/window-size-manager.ts:19

###  extra-large

• **extra-large**: *"xl"* = "xl"

Defined in src/scripts/window-size-manager.ts:25

###  large

• **large**: *"l"* = "l"

Defined in src/scripts/window-size-manager.ts:24

###  max

• **max**: *"max"* = "max"

Defined in src/scripts/window-size-manager.ts:26

###  medium

• **medium**: *"m"* = "m"

Defined in src/scripts/window-size-manager.ts:23

###  small

• **small**: *"s"* = "s"

Defined in src/scripts/window-size-manager.ts:22
