[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/slider-slide/slider-slide"](_src_markups_components_slider_slide_slider_slide_.md)

# Module: "src/markups/components/slider-slide/slider-slide"

## Index

### Classes

* [SliderSlide](../classes/_src_markups_components_slider_slide_slider_slide_.sliderslide.md)

### Type aliases

* [SlideType](_src_markups_components_slider_slide_slider_slide_.md#slidetype)
* [SliderSlideProps](_src_markups_components_slider_slide_slider_slide_.md#sliderslideprops)
* [SliderSlideState](_src_markups_components_slider_slide_slider_slide_.md#sliderslidestate)

## Type aliases

###  SlideType

Ƭ **SlideType**: *object*

Defined in src/markups/components/slider-slide/slider-slide.tsx:66

#### Type declaration:

* **action**? : *[ActionType](_src_scripts_types_.md#actiontype)*

* **image**? : *[ImageType](_src_markups_components_image_image_.md#imagetype)*

* **isVideo**? : *boolean*

* **sponsor**? : *[SponsorType](_src_markups_components_sponsor_sponsor_.md#sponsortype)*

* **subTitle**? : *string*

* **title**? : *string*

* **video**? : *[VideoProps](_src_markups_components_video_corebine_video_corebine_.md#videoprops)*

* **volume**? : *number*

___

###  SliderSlideProps

Ƭ **SliderSlideProps**: *object*

Defined in src/markups/components/slider-slide/slider-slide.tsx:28

#### Type declaration:

* **className**? : *string*

* **cloudinaryOptions**? : *[CloudinaryOptions](_src_markups_components_image_cloudinary_image_cloudinary_.md#cloudinaryoptions)*

* **innerRef**? : *React.LegacyRef‹HTMLDivElement› | null*

* **isMediaControlled**? : *boolean*

* **mediaClassName**? : *string*

* **mediaOptions**? : *object*

* **onClick**(): *function*

  * (): *void*

* **onVideoPause**(): *function*

  * (): *void*

* **onVideoPlay**(): *function*

  * (): *void*

* **onVideoStop**(): *function*

  * (`arg`: boolean): *void*

* **renderDescription**? : *boolean*

* **setRef**(): *function*

  * (`el`: [SliderSlide](../classes/_src_markups_components_slider_slide_slider_slide_.sliderslide.md)): *void*

* **slide**? : *[SlideType](_src_markups_components_slider_slide_slider_slide_.md#slidetype)*

* **slideIndex**? : *number*

* **visible**? : *boolean*

___

###  SliderSlideState

Ƭ **SliderSlideState**: *object*

Defined in src/markups/components/slider-slide/slider-slide.tsx:60

#### Type declaration:

* **isVideoPaused**: *boolean*

* **isVideoPlaying**: *boolean*

* **isVideoStopped**: *boolean*
