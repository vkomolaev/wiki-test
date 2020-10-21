[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/video-youtube/video-youtube"](../modules/_src_markups_components_video_youtube_video_youtube_.md) › [VideoYoutube](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md)

# Class: VideoYoutube

## Hierarchy

* Component‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops), [VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›

  ↳ **VideoYoutube**

## Index

### Constructors

* [constructor](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#constructor)

### Properties

* [apiCallsQueue](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#apicallsqueue)
* [container](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#container)
* [context](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#context)
* [currentTime](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#currenttime)
* [player](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#player)
* [playerContainer](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#playercontainer)
* [props](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#readonly-props)
* [refs](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#refs)
* [state](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#state)
* [timeUpdateInterval](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#timeupdateinterval)
* [trackProgress](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#trackprogress)
* [contextType](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#static-optional-contexttype)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#optional-unsafe_componentwillupdate)
* [checkDuration](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#checkduration)
* [componentDidCatch](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#componentdidmount)
* [componentDidUpdate](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#componentdidupdate)
* [componentWillMount](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#componentwillunmount)
* [componentWillUpdate](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#optional-componentwillupdate)
* [executePlayerApi](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#executeplayerapi)
* [forceUpdate](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#forceupdate)
* [getPropValue](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#getpropvalue)
* [getSnapshotBeforeUpdate](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#optional-getsnapshotbeforeupdate)
* [getStateFromProps](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#getstatefromprops)
* [getVideoId](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#getvideoid)
* [hasApiSupport](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#hasapisupport)
* [isPlaying](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#isplaying)
* [onLayout](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#onlayout)
* [onOutOfScreen](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#onoutofscreen)
* [onScreen](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#onscreen)
* [onTimeUpdate](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#ontimeupdate)
* [pause](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#pause)
* [play](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#play)
* [render](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#render)
* [renderVideoSection](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#rendervideosection)
* [replayIfNeeded](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#replayifneeded)
* [setState](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#setstate)
* [shouldComponentUpdate](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#optional-shouldcomponentupdate)
* [stop](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#stop)
* [trackEvent](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#trackevent)

### Object literals

* [defaultProps](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md#static-defaultprops)

## Constructors

###  constructor

\+ **new VideoYoutube**(`props`: [VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)): *[VideoYoutube](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md)*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[constructor](_src_markups_components_tags_tags_.tags.md#constructor)*

Defined in src/markups/components/video-youtube/video-youtube.tsx:77

**Parameters:**

Name | Type |
------ | ------ |
`props` | [VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops) |

**Returns:** *[VideoYoutube](_src_markups_components_video_youtube_video_youtube_.videoyoutube.md)*

## Properties

###  apiCallsQueue

• **apiCallsQueue**: *function[]*

Defined in src/markups/components/video-youtube/video-youtube.tsx:75

___

###  container

• **container**: *RefObject‹HTMLDivElement›* = React.createRef()

Defined in src/markups/components/video-youtube/video-youtube.tsx:71

___

###  context

• **context**: *any*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[context](_src_markups_components_tags_tags_.tags.md#context)*

Defined in node_modules/@types/react/index.d.ts:476

If using the new style context, re-declare this in your class to be the
`React.ContextType` of your `static contextType`.
Should be used with type annotation or static contextType.

```ts
static contextType = MyContext
// For TS pre-3.7:
context!: React.ContextType<typeof MyContext>
// For TS 3.7 and above:
declare context: React.ContextType<typeof MyContext>
```

**`see`** https://reactjs.org/docs/context.html

___

###  currentTime

• **currentTime**: *number*

Defined in src/markups/components/video-youtube/video-youtube.tsx:77

___

###  player

• **player**: *Player*

Defined in src/markups/components/video-youtube/video-youtube.tsx:67

___

###  playerContainer

• **playerContainer**: *RefObject‹HTMLDivElement›* = React.createRef()

Defined in src/markups/components/video-youtube/video-youtube.tsx:69

___

### `Readonly` props

• **props**: *Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› & Readonly‹object›*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[props](_src_markups_components_tags_tags_.tags.md#readonly-props)*

Defined in node_modules/@types/react/index.d.ts:501

___

###  refs

• **refs**: *object*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[refs](_src_markups_components_tags_tags_.tags.md#refs)*

Defined in node_modules/@types/react/index.d.ts:507

**`deprecated`** 
https://reactjs.org/docs/refs-and-the-dom.html#legacy-api-string-refs

#### Type declaration:

* \[ **key**: *string*\]: ReactInstance

___

###  state

• **state**: *Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[state](_src_markups_components_tags_tags_.tags.md#state)*

Defined in node_modules/@types/react/index.d.ts:502

___

###  timeUpdateInterval

• **timeUpdateInterval**: *number*

Defined in src/markups/components/video-youtube/video-youtube.tsx:73

___

###  trackProgress

• **trackProgress**: *DebouncedFunc‹(Anonymous function)›* = _.throttle(() => {
        this.trackEvent('progress', {trackProgress: this.player.getCurrentTime()});
    }, 5000)

Defined in src/markups/components/video-youtube/video-youtube.tsx:215

___

### `Static` `Optional` contextType

▪ **contextType**? : *Context‹any›*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[contextType](_src_markups_components_tags_tags_.tags.md#static-optional-contexttype)*

Defined in node_modules/@types/react/index.d.ts:458

If set, `this.context` will be set at runtime to the current value of the given Context.

Usage:

```ts
type MyContext = number
const Ctx = React.createContext<MyContext>(0)

class Foo extends React.Component {
  static contextType = Ctx
  context!: React.ContextType<typeof Ctx>
  render () {
    return <>My context's value: {this.context}</>;
  }
}
```

**`see`** https://reactjs.org/docs/context.html#classcontexttype

## Methods

### `Optional` UNSAFE_componentWillMount

▸ **UNSAFE_componentWillMount**(): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[UNSAFE_componentWillMount](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-unsafe_componentwillmount)*

Defined in node_modules/@types/react/index.d.ts:712

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillReceiveProps

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›, `nextContext`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[UNSAFE_componentWillReceiveProps](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-unsafe_componentwillreceiveprops)*

Defined in node_modules/@types/react/index.d.ts:744

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›, `nextState`: Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›, `nextContext`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[UNSAFE_componentWillUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-unsafe_componentwillupdate)*

Defined in node_modules/@types/react/index.d.ts:772

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |
`nextState` | Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)› |
`nextContext` | any |

**Returns:** *void*

___

###  checkDuration

▸ **checkDuration**(`player`: Player): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:231

**Parameters:**

Name | Type |
------ | ------ |
`player` | Player |

**Returns:** *void*

___

### `Optional` componentDidCatch

▸ **componentDidCatch**(`error`: Error, `errorInfo`: ErrorInfo): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidCatch](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidcatch)*

Defined in node_modules/@types/react/index.d.ts:641

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

**Parameters:**

Name | Type |
------ | ------ |
`error` | Error |
`errorInfo` | ErrorInfo |

**Returns:** *void*

___

###  componentDidMount

▸ **componentDidMount**(): *void*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidMount](_src_markups_components_tags_tags_.tags.md#optional-componentdidmount)*

Defined in src/markups/components/video-youtube/video-youtube.tsx:107

**Returns:** *void*

___

###  componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›): *void*

*Overrides [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentDidUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentdidupdate)*

Defined in src/markups/components/video-youtube/video-youtube.tsx:256

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |

**Returns:** *void*

___

### `Optional` componentWillMount

▸ **componentWillMount**(): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentWillMount](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentwillmount)*

Defined in node_modules/@types/react/index.d.ts:698

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Returns:** *void*

___

###  componentWillReceiveProps

▸ **componentWillReceiveProps**(`nextProps`: Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›): *void*

*Overrides [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentWillReceiveProps](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentwillreceiveprops)*

Defined in src/markups/components/video-youtube/video-youtube.tsx:240

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |

**Returns:** *void*

___

###  componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Overrides [AccessoLink](_src_markups_components_link_accesso_link_accesso_.accessolink.md).[componentWillUnmount](_src_markups_components_link_accesso_link_accesso_.accessolink.md#optional-componentwillunmount)*

Defined in src/markups/components/video-youtube/video-youtube.tsx:219

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›, `nextState`: Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›, `nextContext`: any): *void*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[componentWillUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-componentwillupdate)*

Defined in node_modules/@types/react/index.d.ts:757

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |
`nextState` | Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)› |
`nextContext` | any |

**Returns:** *void*

___

###  executePlayerApi

▸ **executePlayerApi**(`callback`: function): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:223

**Parameters:**

▪ **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

###  forceUpdate

▸ **forceUpdate**(`callback?`: function): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[forceUpdate](_src_markups_components_tags_tags_.tags.md#forceupdate)*

Defined in node_modules/@types/react/index.d.ts:493

**Parameters:**

▪`Optional`  **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

###  getPropValue

▸ **getPropValue**(`props`: Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›, `propName`: string, `defaultVal`: any): *boolean*

Defined in src/markups/components/video-youtube/video-youtube.tsx:90

**Parameters:**

Name | Type |
------ | ------ |
`props` | Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |
`propName` | string |
`defaultVal` | any |

**Returns:** *boolean*

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›, `prevState`: Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›): *any | null*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[getSnapshotBeforeUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-getsnapshotbeforeupdate)*

Defined in node_modules/@types/react/index.d.ts:677

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |
`prevState` | Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)› |

**Returns:** *any | null*

___

###  getStateFromProps

▸ **getStateFromProps**(`props`: Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›, `state?`: Partial‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›): *Partial‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›*

Defined in src/markups/components/video-youtube/video-youtube.tsx:99

**Parameters:**

Name | Type |
------ | ------ |
`props` | Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |
`state?` | Partial‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)› |

**Returns:** *Partial‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›*

___

###  getVideoId

▸ **getVideoId**(`props`: Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›): *string*

Defined in src/markups/components/video-youtube/video-youtube.tsx:94

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`props` | Partial‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› | this.props |

**Returns:** *string*

___

###  hasApiSupport

▸ **hasApiSupport**(): *boolean*

Defined in src/markups/components/video-youtube/video-youtube.tsx:86

**Returns:** *boolean*

___

###  isPlaying

▸ **isPlaying**(): *boolean*

Defined in src/markups/components/video-youtube/video-youtube.tsx:305

**Returns:** *boolean*

___

###  onLayout

▸ **onLayout**(): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:185

**Returns:** *void*

___

###  onOutOfScreen

▸ **onOutOfScreen**(): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:199

**Returns:** *void*

___

###  onScreen

▸ **onScreen**(): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:193

**Returns:** *void*

___

###  onTimeUpdate

▸ **onTimeUpdate**(): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:207

**Returns:** *void*

___

###  pause

▸ **pause**(): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:289

**Returns:** *void*

___

###  play

▸ **play**(): *Promise‹void›*

Defined in src/markups/components/video-youtube/video-youtube.tsx:277

**Returns:** *Promise‹void›*

___

###  render

▸ **render**(): *Element‹›*

*Overrides void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:329

**Returns:** *Element‹›*

___

###  renderVideoSection

▸ **renderVideoSection**(): *Element‹›*

Defined in src/markups/components/video-youtube/video-youtube.tsx:340

**Returns:** *Element‹›*

___

###  replayIfNeeded

▸ **replayIfNeeded**(): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:309

**Returns:** *void*

___

###  setState

▸ **setState**‹**K**›(`state`: function | Pick‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate), K› | [VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate) | null, `callback?`: function): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[setState](_src_markups_components_tags_tags_.tags.md#setstate)*

Defined in node_modules/@types/react/index.d.ts:488

**Type parameters:**

▪ **K**: *keyof VideoYoutubeState*

**Parameters:**

▪ **state**: *function | Pick‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate), K› | [VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate) | null*

▪`Optional`  **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)›, `nextState`: Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)›, `nextContext`: any): *boolean*

*Inherited from [AdDfp](_src_markups_components_ad_dfp_ad_dfp_.addfp.md).[shouldComponentUpdate](_src_markups_components_ad_dfp_ad_dfp_.addfp.md#optional-shouldcomponentupdate)*

Defined in node_modules/@types/react/index.d.ts:631

Called to determine whether the change in props and state should trigger a re-render.

`Component` always returns true.
`PureComponent` implements a shallow comparison on props and state and returns true if any
props or states have changed.

If false is returned, `Component#render`, `componentWillUpdate`
and `componentDidUpdate` will not be called.

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹[VideoYoutubeProps](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubeprops)› |
`nextState` | Readonly‹[VideoYoutubeState](../modules/_src_markups_components_video_youtube_video_youtube_.md#videoyoutubestate)› |
`nextContext` | any |

**Returns:** *boolean*

___

###  stop

▸ **stop**(): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:295

**Returns:** *void*

___

###  trackEvent

▸ **trackEvent**(`event`: string, `payload`: object): *void*

Defined in src/markups/components/video-youtube/video-youtube.tsx:315

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`event` | string | - |
`payload` | object | {} |

**Returns:** *void*

## Object literals

### `Static` defaultProps

### ▪ **defaultProps**: *object*

Defined in src/markups/components/video-youtube/video-youtube.tsx:60

###  className

• **className**: *string* = ""

Defined in src/markups/components/video-youtube/video-youtube.tsx:61

###  errorClassName

• **errorClassName**: *string* = ""

Defined in src/markups/components/video-youtube/video-youtube.tsx:62

###  successClassName

• **successClassName**: *string* = ""

Defined in src/markups/components/video-youtube/video-youtube.tsx:63

###  volume

• **volume**: *number* = 100

Defined in src/markups/components/video-youtube/video-youtube.tsx:64
