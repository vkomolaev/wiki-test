[corebine-web-templates-core](../README.md) › [Globals](../globals.md) › ["src/scripts/utils/form"](_src_scripts_utils_form_.md)

# Module: "src/scripts/utils/form"

## Index

### Interfaces

* [Validator](../interfaces/_src_scripts_utils_form_.validator.md)

### Type aliases

* [Field](_src_scripts_utils_form_.md#field)
* [FieldInitial](_src_scripts_utils_form_.md#fieldinitial)

### Variables

* [SALES_FORCE](_src_scripts_utils_form_.md#const-sales_force)
* [phoneRegExp](_src_scripts_utils_form_.md#const-phoneregexp)

### Functions

* [getFiledName](_src_scripts_utils_form_.md#getfiledname)
* [getRequiredMessage](_src_scripts_utils_form_.md#getrequiredmessage)
* [isFailed](_src_scripts_utils_form_.md#isfailed)
* [isSubmitted](_src_scripts_utils_form_.md#issubmitted)
* [requiredDecorator](_src_scripts_utils_form_.md#const-requireddecorator)

### Object literals

* [DEFAULT_ERROR_MESSAGES](_src_scripts_utils_form_.md#const-default_error_messages)
* [FORM_STATUSES](_src_scripts_utils_form_.md#const-form_statuses)
* [formUtils](_src_scripts_utils_form_.md#const-formutils)

## Type aliases

###  Field

Ƭ **Field**: *object*

Defined in src/scripts/utils/form.ts:42

#### Type declaration:

* **fieldId**? : *string*

* **format**: *string*

* **label**: *string*

* **mandatory**: *boolean*

* **name**: *string*

* **type**: *string*

___

###  FieldInitial

Ƭ **FieldInitial**: *object*

Defined in src/scripts/utils/form.ts:51

#### Type declaration:

* **items**: *string[]*

* **tip**: *string*

* **type**: *string*

* **value**: *string*

## Variables

### `Const` SALES_FORCE

• **SALES_FORCE**: *"SalesForce"* = "SalesForce"

Defined in src/scripts/utils/form.ts:17

___

### `Const` phoneRegExp

• **phoneRegExp**: *RegExp‹›* = /^(\+?\d{0,4})?\s?-?\s?(\(?\d{3}\)?)\s?-?\s?(\(?\d{3}\)?)\s?-?\s?(\(?\d{4}\)?)?$/

Defined in src/scripts/utils/form.ts:91

## Functions

###  getFiledName

▸ **getFiledName**(`field`: [Field](_src_scripts_utils_form_.md#field)): *string*

Defined in src/scripts/utils/form.ts:62

**Parameters:**

Name | Type |
------ | ------ |
`field` | [Field](_src_scripts_utils_form_.md#field) |

**Returns:** *string*

___

###  getRequiredMessage

▸ **getRequiredMessage**(`field`: [Field](_src_scripts_utils_form_.md#field)): *string*

Defined in src/scripts/utils/form.ts:66

**Parameters:**

Name | Type |
------ | ------ |
`field` | [Field](_src_scripts_utils_form_.md#field) |

**Returns:** *string*

___

###  isFailed

▸ **isFailed**(`status`: string): *boolean*

Defined in src/scripts/utils/form.ts:87

**Parameters:**

Name | Type |
------ | ------ |
`status` | string |

**Returns:** *boolean*

___

###  isSubmitted

▸ **isSubmitted**(`status`: string): *boolean*

Defined in src/scripts/utils/form.ts:83

**Parameters:**

Name | Type |
------ | ------ |
`status` | string |

**Returns:** *boolean*

___

### `Const` requiredDecorator

▸ **requiredDecorator**(`validator`: [Validator](../interfaces/_src_scripts_utils_form_.validator.md), `field`: [Field](_src_scripts_utils_form_.md#field)): *[Validator](../interfaces/_src_scripts_utils_form_.validator.md) | boolean*

Defined in src/scripts/utils/form.ts:70

**Parameters:**

Name | Type |
------ | ------ |
`validator` | [Validator](../interfaces/_src_scripts_utils_form_.validator.md) |
`field` | [Field](_src_scripts_utils_form_.md#field) |

**Returns:** *[Validator](../interfaces/_src_scripts_utils_form_.validator.md) | boolean*

## Object literals

### `Const` DEFAULT_ERROR_MESSAGES

### ▪ **DEFAULT_ERROR_MESSAGES**: *object*

Defined in src/scripts/utils/form.ts:19

###  email

• **email**: *string* = "Please enter a valid email address."

Defined in src/scripts/utils/form.ts:20

###  number

• **number**: *string* = "Please provide valid number."

Defined in src/scripts/utils/form.ts:22

###  phone

• **phone**: *string* = "Please enter a valid phone number."

Defined in src/scripts/utils/form.ts:21

▪ **max**: *object*

Defined in src/scripts/utils/form.ts:36

* **text**: *string* = "This field must be at most 100 characters."

* **textarea**: *string* = "This field must be at most 200 characters."

▪ **required**: *object*

Defined in src/scripts/utils/form.ts:23

* **checkbox**: *string* = "This field is required."

* **city**: *string* = "This field is required."

* **country**: *string* = "This field is required."

* **date**: *string* = "This field is required."

* **default**: *string* = "This field is required."

* **email**: *string* = "This field is required."

* **number**: *string* = "This field is required."

* **phone**: *string* = "Please enter a valid phone number."

* **radiobutton**: *string* = "This field is required."

* **region**: *string* = "This field is required."

* **time**: *string* = "This field is required."

___

### `Const` FORM_STATUSES

### ▪ **FORM_STATUSES**: *object*

Defined in src/scripts/utils/form.ts:77

###  failed

• **failed**: *string* = "failed"

Defined in src/scripts/utils/form.ts:79

###  submitting

• **submitting**: *string* = "submitting"

Defined in src/scripts/utils/form.ts:80

###  success

• **success**: *string* = "success"

Defined in src/scripts/utils/form.ts:78

___

### `Const` formUtils

### ▪ **formUtils**: *object*

Defined in src/scripts/utils/form.ts:93

###  buildValidationSchema

▸ **buildValidationSchema**(`fields`: object[], `customRules`: object): *ObjectSchema*

Defined in src/scripts/utils/form.ts:142

**Parameters:**

Name | Type |
------ | ------ |
`fields` | object[] |
`customRules` | object |

**Returns:** *ObjectSchema*

###  computeId

▸ **computeId**(`name`: string): *string*

Defined in src/scripts/utils/form.ts:110

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |

**Returns:** *string*

###  computeName

▸ **computeName**(`fieldId`: string, `label`: string): *string*

Defined in src/scripts/utils/form.ts:106

**Parameters:**

Name | Type |
------ | ------ |
`fieldId` | string |
`label` | string |

**Returns:** *string*

###  getFieldInitialValue

▸ **getFieldInitialValue**(`__namedParameters`: object): *string*

Defined in src/scripts/utils/form.ts:156

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type |
------ | ------ |
`items` | string[] |
`tip` | string |
`type` | string |
`value` | string |

**Returns:** *string*

###  getFormAction

▸ **getFormAction**(`crmType`: string, `submitUrl`: string): *string | null*

Defined in src/scripts/utils/form.ts:102

**Parameters:**

Name | Type |
------ | ------ |
`crmType` | string |
`submitUrl` | string |

**Returns:** *string | null*

###  getFormMethod

▸ **getFormMethod**(`crmType`: string): *string*

Defined in src/scripts/utils/form.ts:98

**Parameters:**

Name | Type |
------ | ------ |
`crmType` | string |

**Returns:** *string*

###  getInitialValues

▸ **getInitialValues**(`fields`: []): *object*

Defined in src/scripts/utils/form.ts:165

**Parameters:**

Name | Type |
------ | ------ |
`fields` | [] |

**Returns:** *object*

###  getValidatorByField

▸ **getValidatorByField**(`field`: [Field](_src_scripts_utils_form_.md#field)): *[Validator](../interfaces/_src_scripts_utils_form_.validator.md) | null*

Defined in src/scripts/utils/form.ts:137

**Parameters:**

Name | Type |
------ | ------ |
`field` | [Field](_src_scripts_utils_form_.md#field) |

**Returns:** *[Validator](../interfaces/_src_scripts_utils_form_.validator.md) | null*

###  isSalesForce

▸ **isSalesForce**(`crmType`: string): *boolean*

Defined in src/scripts/utils/form.ts:94

**Parameters:**

Name | Type |
------ | ------ |
`crmType` | string |

**Returns:** *boolean*

###  postDataToProsuite

▸ **postDataToProsuite**(`__namedParameters`: object, `data`: object): *Promise‹object | object›*

Defined in src/scripts/utils/form.ts:171

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type | Default |
------ | ------ | ------ |
`clientId` | string | "" |
`formId` | string | "" |
`url` | string | "" |

▪`Default value`  **data**: *object*= {}

**Returns:** *Promise‹object | object›*

▪ **validators**: *object*

Defined in src/scripts/utils/form.ts:114

* **checkbox**(): *StringSchema*

* **date**(): *StringSchema*

* **email**(): *StringSchema*

* **number**(): *NumberSchema*

* **phone**(): *StringSchema*

* **radiobutton**(): *StringSchema*

* **select**(): *StringSchema*

* **text**(): *StringSchema*

* **textarea**(): *StringSchema*

* **time**(): *StringSchema*
