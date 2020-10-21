[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/markups/components/google-structured-data/google-structured-data"](../modules/_src_markups_components_google_structured_data_google_structured_data_.md) › [GoogleStructuredData](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md)

# Class: GoogleStructuredData

## Hierarchy

* Component

  ↳ **GoogleStructuredData**

## Index

### Constructors

* [constructor](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#constructor)

### Properties

* [context](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#context)
* [description](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#description)
* [displayDate](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#displaydate)
* [logoUrl](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#logourl)
* [props](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#readonly-props)
* [refs](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#refs)
* [siteUrl](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#siteurl)
* [state](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#state)
* [tags](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#tags)
* [title](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#title)
* [contextType](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#static-optional-contexttype)

### Methods

* [UNSAFE_componentWillMount](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-unsafe_componentwillmount)
* [UNSAFE_componentWillReceiveProps](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-unsafe_componentwillreceiveprops)
* [UNSAFE_componentWillUpdate](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-unsafe_componentwillupdate)
* [changeDateFormat](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#changedateformat)
* [componentDidCatch](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-componentdidcatch)
* [componentDidMount](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-componentdidmount)
* [componentDidUpdate](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-componentdidupdate)
* [componentWillMount](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-componentwillmount)
* [componentWillReceiveProps](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-componentwillreceiveprops)
* [componentWillUnmount](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-componentwillunmount)
* [componentWillUpdate](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-componentwillupdate)
* [createUrl](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#createurl)
* [forceUpdate](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#forceupdate)
* [getArticle](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getarticle)
* [getBreadcrumbs](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getbreadcrumbs)
* [getBreadcrumbsList](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getbreadcrumbslist)
* [getData](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getdata)
* [getItem](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getitem)
* [getLogo](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getlogo)
* [getSearch](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getsearch)
* [getSnapshotBeforeUpdate](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-getsnapshotbeforeupdate)
* [getSpeakble](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getspeakble)
* [getVideo](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getvideo)
* [getVideoThumbnail](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#getvideothumbnail)
* [render](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#render)
* [setState](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#setstate)
* [shouldComponentUpdate](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md#optional-shouldcomponentupdate)

## Constructors

###  constructor

\+ **new GoogleStructuredData**(`props`: any): *[GoogleStructuredData](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md)*

*Overrides [Tags](_src_markups_components_tags_tags_.tags.md).[constructor](_src_markups_components_tags_tags_.tags.md#constructor)*

Defined in src/markups/components/google-structured-data/google-structured-data.js:32

**Parameters:**

Name | Type |
------ | ------ |
`props` | any |

**Returns:** *[GoogleStructuredData](_src_markups_components_google_structured_data_google_structured_data_.googlestructureddata.md)*

## Properties

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

###  description

• **description**: *string* = ""

Defined in src/markups/components/google-structured-data/google-structured-data.js:28

___

###  displayDate

• **displayDate**: *string* = ""

Defined in src/markups/components/google-structured-data/google-structured-data.js:26

___

###  logoUrl

• **logoUrl**: *string* = ""

Defined in src/markups/components/google-structured-data/google-structured-data.js:32

___

### `Readonly` props

• **props**: *Readonly‹object› & Readonly‹object›*

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

###  siteUrl

• **siteUrl**: *string* = ""

Defined in src/markups/components/google-structured-data/google-structured-data.js:30

___

###  state

• **state**: *Readonly‹object›*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[state](_src_markups_components_tags_tags_.tags.md#state)*

Defined in node_modules/@types/react/index.d.ts:502

___

###  tags

• **tags**: *any[]* = []

Defined in src/markups/components/google-structured-data/google-structured-data.js:22

___

###  title

• **title**: *string* = ""

Defined in src/markups/components/google-structured-data/google-structured-data.js:24

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

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[UNSAFE_componentWillMount](_src_markups_components_tags_tags_.tags.md#optional-unsafe_componentwillmount)*

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

▸ **UNSAFE_componentWillReceiveProps**(`nextProps`: Readonly‹object›, `nextContext`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[UNSAFE_componentWillReceiveProps](_src_markups_components_tags_tags_.tags.md#optional-unsafe_componentwillreceiveprops)*

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
`nextProps` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` UNSAFE_componentWillUpdate

▸ **UNSAFE_componentWillUpdate**(`nextProps`: Readonly‹object›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[UNSAFE_componentWillUpdate](_src_markups_components_tags_tags_.tags.md#optional-unsafe_componentwillupdate)*

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
`nextProps` | Readonly‹object› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

###  changeDateFormat

▸ **changeDateFormat**(`date`: any): *string*

Defined in src/markups/components/google-structured-data/google-structured-data.js:189

**Parameters:**

Name | Type |
------ | ------ |
`date` | any |

**Returns:** *string*

___

### `Optional` componentDidCatch

▸ **componentDidCatch**(`error`: [Error](_src_markups_modules_error_error_.error.md), `errorInfo`: ErrorInfo): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidCatch](_src_markups_components_tags_tags_.tags.md#optional-componentdidcatch)*

Defined in node_modules/@types/react/index.d.ts:641

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

**Parameters:**

Name | Type |
------ | ------ |
`error` | [Error](_src_markups_modules_error_error_.error.md) |
`errorInfo` | ErrorInfo |

**Returns:** *void*

___

### `Optional` componentDidMount

▸ **componentDidMount**(): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidMount](_src_markups_components_tags_tags_.tags.md#optional-componentdidmount)*

Defined in node_modules/@types/react/index.d.ts:620

Called immediately after a component is mounted. Setting state here will trigger re-rendering.

**Returns:** *void*

___

### `Optional` componentDidUpdate

▸ **componentDidUpdate**(`prevProps`: Readonly‹object›, `prevState`: Readonly‹object›, `snapshot?`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentDidUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentdidupdate)*

Defined in node_modules/@types/react/index.d.ts:683

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹object› |
`prevState` | Readonly‹object› |
`snapshot?` | any |

**Returns:** *void*

___

### `Optional` componentWillMount

▸ **componentWillMount**(): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillMount](_src_markups_components_tags_tags_.tags.md#optional-componentwillmount)*

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

### `Optional` componentWillReceiveProps

▸ **componentWillReceiveProps**(`nextProps`: Readonly‹object›, `nextContext`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillReceiveProps](_src_markups_components_tags_tags_.tags.md#optional-componentwillreceiveprops)*

Defined in node_modules/@types/react/index.d.ts:727

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

**Parameters:**

Name | Type |
------ | ------ |
`nextProps` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

### `Optional` componentWillUnmount

▸ **componentWillUnmount**(): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillUnmount](_src_markups_components_tags_tags_.tags.md#optional-componentwillunmount)*

Defined in node_modules/@types/react/index.d.ts:636

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

**Returns:** *void*

___

### `Optional` componentWillUpdate

▸ **componentWillUpdate**(`nextProps`: Readonly‹object›, `nextState`: Readonly‹object›, `nextContext`: any): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[componentWillUpdate](_src_markups_components_tags_tags_.tags.md#optional-componentwillupdate)*

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
`nextProps` | Readonly‹object› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *void*

___

###  createUrl

▸ **createUrl**(`url`: any): *string*

Defined in src/markups/components/google-structured-data/google-structured-data.js:185

**Parameters:**

Name | Type |
------ | ------ |
`url` | any |

**Returns:** *string*

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

###  getArticle

▸ **getArticle**(): *object*

Defined in src/markups/components/google-structured-data/google-structured-data.js:89

**Returns:** *object*

* **@type**: *string* = "Article"

* **datePublished**: *string* = this.changeDateFormat(this.displayDate)

* **headline**: *string* = this.title

* **image**: *string* = imageUrl

* **keywords**: *any[]* = this.tags.map(tag => tag.title)

* ### **author**: *object*

  * **@type**: *string* = "Person"

  * **name**: *any* = author

* ### **mainEntityOfPage**: *object*

  * **@id**: *string* = pageUrl

  * **@type**: *string* = "WebPage"

* ### **publisher**: *object*

  * **@type**: *string* = "Organization"

  * **name**: *any* = publisher

  * **logo**: *object*

    * **@type**: *string* = "ImageObject"

    * **url**: *string* = this.logoUrl

___

###  getBreadcrumbs

▸ **getBreadcrumbs**(): *object*

Defined in src/markups/components/google-structured-data/google-structured-data.js:149

**Returns:** *object*

* **@type**: *string* = "BreadcrumbList"

* **itemListElement**: *any* = this.getBreadcrumbsList(breadcrumbs)

___

###  getBreadcrumbsList

▸ **getBreadcrumbsList**(`breadcrumbsList`: any): *any*

Defined in src/markups/components/google-structured-data/google-structured-data.js:161

**Parameters:**

Name | Type |
------ | ------ |
`breadcrumbsList` | any |

**Returns:** *any*

___

###  getData

▸ **getData**(): *(object | object | object | object)[]*

Defined in src/markups/components/google-structured-data/google-structured-data.js:59

**Returns:** *(object | object | object | object)[]*

___

###  getItem

▸ **getItem**(): *object*

Defined in src/markups/components/google-structured-data/google-structured-data.js:52

**Returns:** *object*

* **@context**: *string* = "https://schema.org"

* **@graph**: *(object | object | object | object)[]* = this.getData()

___

###  getLogo

▸ **getLogo**(): *object*

Defined in src/markups/components/google-structured-data/google-structured-data.js:141

**Returns:** *object*

* **@type**: *string* = "Organization"

* **logo**: *string* = this.logoUrl

* **url**: *string* = this.siteUrl

___

###  getSearch

▸ **getSearch**(): *object*

Defined in src/markups/components/google-structured-data/google-structured-data.js:129

**Returns:** *object*

* **@type**: *string* = "WebSite"

* **url**: *string* = this.siteUrl

* ### **potentialAction**: *object*

  * **@type**: *string* = "SearchAction"

  * **query-input**: *string* = "required name=search_term_string"

  * **target**: *string* = (`${this.siteUrl}?search={search_term_string}`)

___

### `Optional` getSnapshotBeforeUpdate

▸ **getSnapshotBeforeUpdate**(`prevProps`: Readonly‹object›, `prevState`: Readonly‹object›): *any | null*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[getSnapshotBeforeUpdate](_src_markups_components_tags_tags_.tags.md#optional-getsnapshotbeforeupdate)*

Defined in node_modules/@types/react/index.d.ts:677

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

**Parameters:**

Name | Type |
------ | ------ |
`prevProps` | Readonly‹object› |
`prevState` | Readonly‹object› |

**Returns:** *any | null*

___

###  getSpeakble

▸ **getSpeakble**(): *object*

Defined in src/markups/components/google-structured-data/google-structured-data.js:119

**Returns:** *object*

* **@type**: *string* = "WebPage"

* ### **speakable**: *object*

  * **@type**: *string* = "SpeakableSpecification"

  * **xpath**: *string* = "/html/head/title"

___

###  getVideo

▸ **getVideo**(): *object*

Defined in src/markups/components/google-structured-data/google-structured-data.js:74

**Returns:** *object*

* **@type**: *string* = "VideoObject"

* **description**: *string* = this.description.replace(/<[^>]+>/g, '').replace(/(\r\n|\n|\r)/gm, '')

* **embedUrl**: *string* = videoUrl

* **keywords**: *any[]* = this.tags.map(tag => tag.title)

* **name**: *string* = this.title

* **thumbnailUrl**: *string* = this.getVideoThumbnail(videoEmbedCode)

* **uploadDate**: *string* = this.changeDateFormat(this.displayDate)

___

###  getVideoThumbnail

▸ **getVideoThumbnail**(`url`: any): *string*

Defined in src/markups/components/google-structured-data/google-structured-data.js:175

**Parameters:**

Name | Type |
------ | ------ |
`url` | any |

**Returns:** *string*

___

###  render

▸ **render**(): *Element‹›*

*Overrides void*

Defined in src/markups/components/google-structured-data/google-structured-data.js:44

**Returns:** *Element‹›*

___

###  setState

▸ **setState**‹**K**›(`state`: function | Pick‹object, K› | object | null, `callback?`: function): *void*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[setState](_src_markups_components_tags_tags_.tags.md#setstate)*

Defined in node_modules/@types/react/index.d.ts:488

**Type parameters:**

▪ **K**: *keyof object*

**Parameters:**

▪ **state**: *function | Pick‹object, K› | object | null*

▪`Optional`  **callback**: *function*

▸ (): *void*

**Returns:** *void*

___

### `Optional` shouldComponentUpdate

▸ **shouldComponentUpdate**(`nextProps`: Readonly‹object›, `nextState`: Readonly‹object›, `nextContext`: any): *boolean*

*Inherited from [Tags](_src_markups_components_tags_tags_.tags.md).[shouldComponentUpdate](_src_markups_components_tags_tags_.tags.md#optional-shouldcomponentupdate)*

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
`nextProps` | Readonly‹object› |
`nextState` | Readonly‹object› |
`nextContext` | any |

**Returns:** *boolean*
