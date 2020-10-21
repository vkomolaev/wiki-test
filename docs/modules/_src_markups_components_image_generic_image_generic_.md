[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/image-generic/image-generic"](_src_markups_components_image_generic_image_generic_.md)

# Module: "src/markups/components/image-generic/image-generic"

## Index

### Classes

* [ImageGeneric](../classes/_src_markups_components_image_generic_image_generic_.imagegeneric.md)

### Type aliases

* [DraggableType](_src_markups_components_image_generic_image_generic_.md#draggabletype)
* [ImageGenericProps](_src_markups_components_image_generic_image_generic_.md#imagegenericprops)
* [ImageGenericState](_src_markups_components_image_generic_image_generic_.md#imagegenericstate)

### Functions

* [hydrate](_src_markups_components_image_generic_image_generic_.md#hydrate)
* [render](_src_markups_components_image_generic_image_generic_.md#render)

## Type aliases

###  DraggableType

Ƭ **DraggableType**: *object*

Defined in src/markups/components/image-generic/image-generic.tsx:19

#### Type declaration:

* **onDragStart**? : *React.ReactEventHandler*

* **onMouseDown**? : *React.ReactEventHandler*

___

###  ImageGenericProps

Ƭ **ImageGenericProps**: *object*

Defined in src/markups/components/image-generic/image-generic.tsx:24

#### Type declaration:

* **alt**? : *string*

* **className**? : *string*

* **drag**? : *boolean*

* **errorClassName**? : *string*

* **image**? : *[ImageType](_src_markups_components_image_image_.md#imagetype)*

* **isExternalSource**? : *boolean*

* **onError**(): *function*

  * (): *void*

* **onLoaded**(): *function*

  * (): *void*

* **source**? : *string*

* **successClassName**? : *string*

* **visible**? : *boolean*

___

###  ImageGenericState

Ƭ **ImageGenericState**: *object*

Defined in src/markups/components/image-generic/image-generic.tsx:49

#### Type declaration:

* **hasError**: *boolean*

* **isLoaded**: *boolean*

* **visible**: *boolean*

## Functions

###  hydrate

▸ **hydrate**(`props`: [ImageGenericProps](_src_markups_components_image_generic_image_generic_.md#imagegenericprops), `targetElement`: HTMLElement, `callback`: function): *void*

Defined in src/markups/components/image-generic/image-generic.tsx:167

**Parameters:**

▪ **props**: *[ImageGenericProps](_src_markups_components_image_generic_image_generic_.md#imagegenericprops)*

▪ **targetElement**: *HTMLElement*

▪ **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

###  render

▸ **render**(`props`: [ImageGenericProps](_src_markups_components_image_generic_image_generic_.md#imagegenericprops), `targetElement`: HTMLElement): *void*

Defined in src/markups/components/image-generic/image-generic.tsx:160

**Parameters:**

Name | Type |
------ | ------ |
`props` | [ImageGenericProps](_src_markups_components_image_generic_image_generic_.md#imagegenericprops) |
`targetElement` | HTMLElement |

**Returns:** *void*
