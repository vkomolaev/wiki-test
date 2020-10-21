[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/window-size-manager"](../modules/_src_scripts_window_size_manager_.md) › [WindowSizeManager](_src_scripts_window_size_manager_.windowsizemanager.md)

# Class: WindowSizeManager

## Hierarchy

* **WindowSizeManager**

## Index

### Constructors

* [constructor](_src_scripts_window_size_manager_.windowsizemanager.md#constructor)

### Properties

* [isExtraLarge](_src_scripts_window_size_manager_.windowsizemanager.md#isextralarge)
* [isLarge](_src_scripts_window_size_manager_.windowsizemanager.md#islarge)
* [isMax](_src_scripts_window_size_manager_.windowsizemanager.md#ismax)
* [isMedium](_src_scripts_window_size_manager_.windowsizemanager.md#ismedium)
* [isSmall](_src_scripts_window_size_manager_.windowsizemanager.md#issmall)
* [screenSizes](_src_scripts_window_size_manager_.windowsizemanager.md#protected-screensizes)
* [width](_src_scripts_window_size_manager_.windowsizemanager.md#width)

### Methods

* [_checkScreenSize](_src_scripts_window_size_manager_.windowsizemanager.md#_checkscreensize)
* [_getCheckSizeMethodName](_src_scripts_window_size_manager_.windowsizemanager.md#_getchecksizemethodname)
* [_initScreenSizeCheckMethods](_src_scripts_window_size_manager_.windowsizemanager.md#_initscreensizecheckmethods)
* [getScreenSize](_src_scripts_window_size_manager_.windowsizemanager.md#getscreensize)
* [getScreenSizes](_src_scripts_window_size_manager_.windowsizemanager.md#getscreensizes)

## Constructors

###  constructor

\+ **new WindowSizeManager**(): *[WindowSizeManager](_src_scripts_window_size_manager_.windowsizemanager.md)*

Defined in src/scripts/window-size-manager.ts:50

**Returns:** *[WindowSizeManager](_src_scripts_window_size_manager_.windowsizemanager.md)*

## Properties

###  isExtraLarge

• **isExtraLarge**: *function*

Defined in src/scripts/window-size-manager.ts:79

#### Type declaration:

▸ (): *boolean*

___

###  isLarge

• **isLarge**: *function*

Defined in src/scripts/window-size-manager.ts:77

#### Type declaration:

▸ (): *boolean*

___

###  isMax

• **isMax**: *function*

Defined in src/scripts/window-size-manager.ts:81

#### Type declaration:

▸ (): *boolean*

___

###  isMedium

• **isMedium**: *function*

Defined in src/scripts/window-size-manager.ts:75

#### Type declaration:

▸ (): *boolean*

___

###  isSmall

• **isSmall**: *function*

Defined in src/scripts/window-size-manager.ts:73

#### Type declaration:

▸ (): *boolean*

___

### `Protected` screenSizes

• **screenSizes**: *[ScreenSizes](../modules/_src_scripts_window_size_manager_.md#screensizes)*

Defined in src/scripts/window-size-manager.ts:48

___

###  width

• **width**: *any* = domUtils.getViewportSize().width

Defined in src/scripts/window-size-manager.ts:50

## Methods

###  _checkScreenSize

▸ **_checkScreenSize**(`size`: [ViewportSizes](../modules/_src_scripts_window_size_manager_.md#viewportsizes)): *boolean*

Defined in src/scripts/window-size-manager.ts:104

**Parameters:**

Name | Type |
------ | ------ |
`size` | [ViewportSizes](../modules/_src_scripts_window_size_manager_.md#viewportsizes) |

**Returns:** *boolean*

___

###  _getCheckSizeMethodName

▸ **_getCheckSizeMethodName**(`key`: [ScreenName](../modules/_src_scripts_window_size_manager_.md#screenname)): *string*

Defined in src/scripts/window-size-manager.ts:95

**Parameters:**

Name | Type |
------ | ------ |
`key` | [ScreenName](../modules/_src_scripts_window_size_manager_.md#screenname) |

**Returns:** *string*

___

###  _initScreenSizeCheckMethods

▸ **_initScreenSizeCheckMethods**(): *void*

Defined in src/scripts/window-size-manager.ts:83

**Returns:** *void*

___

###  getScreenSize

▸ **getScreenSize**(`isShort`: boolean): *[ScreenName](../modules/_src_scripts_window_size_manager_.md#screenname) | [ScreenShortName](../modules/_src_scripts_window_size_manager_.md#screenshortname)*

Defined in src/scripts/window-size-manager.ts:64

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`isShort` | boolean | false |

**Returns:** *[ScreenName](../modules/_src_scripts_window_size_manager_.md#screenname) | [ScreenShortName](../modules/_src_scripts_window_size_manager_.md#screenshortname)*

___

###  getScreenSizes

▸ **getScreenSizes**(`isShort`: boolean): *[ScreenSizes](../modules/_src_scripts_window_size_manager_.md#screensizes) | [ScreenShortSizes](../modules/_src_scripts_window_size_manager_.md#screenshortsizes)*

Defined in src/scripts/window-size-manager.ts:69

**Parameters:**

Name | Type |
------ | ------ |
`isShort` | boolean |

**Returns:** *[ScreenSizes](../modules/_src_scripts_window_size_manager_.md#screensizes) | [ScreenShortSizes](../modules/_src_scripts_window_size_manager_.md#screenshortsizes)*
