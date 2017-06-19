[typedoc-plugin-markdown](../index.md) > ["functions"](../modules/_functions_.md)

# External module: "functions"

## Index

### Modules

* [moduleFunction](_functions_.modulefunction.md)


### Functions

* [createSomething](_functions_.md#createsomething)
* [exportedFunction](_functions_.md#exportedfunction)
* [functionWithArguments](_functions_.md#functionwitharguments)
* [functionWithDefaults](_functions_.md#functionwithdefaults)
* [functionWithDocLink](_functions_.md#functionwithdoclink)
* [functionWithOptionalValue](_functions_.md#functionwithoptionalvalue)
* [functionWithRest](_functions_.md#functionwithrest)
* [genericFunction](_functions_.md#genericfunction)
* [internalFunction](_functions_.md#internalfunction)
* [multipleSignatures](_functions_.md#multiplesignatures)
* [variableFunction](_functions_.md#variablefunction)



## Functions

<a id="createsomething"></a>
###  createSomething

► **createSomething**(): object

*Defined in functions.ts:161*

A function that returns an object.
Also no type information is given, the object should be correctly reflected.




**Returns:** object

----


<a id="exportedfunction"></a>
###  exportedFunction

► **exportedFunction**(): void

*Defined in functions.ts:12*

This is a simple exported function.




**Returns:** void

----


<a id="functionwitharguments"></a>
###  functionWithArguments

► **functionWithArguments**(paramZ: *string*, paramG: *any*, paramA: *[INameInterface](../interfaces/_classes_.inameinterface.md)*): number

*Defined in functions.ts:41*

This is a function with multiple arguments and a return value.


#### Parameters:

| Name  | Type                | Default | Description  |
| ------ | ------------------- | ------------ | ------------ |
| paramZ  | string | - | This is a string parameter. |
| paramG  | any | - | This is a parameter flagged with any.    This sentence is placed in the next line. |
| paramA  | [INameInterface](../interfaces/_classes_.inameinterface.md) | - | This is a **parameter** pointing to an interface. |





**Returns:** number

----


<a id="functionwithdefaults"></a>
###  functionWithDefaults

► **functionWithDefaults**(valueA?: *string*, valueB?: *number*, valueC?: *number*, valueD?: *boolean*, valueE?: *boolean*): string

*Defined in functions.ts:61*

This is a function with a parameter that has a default value.


#### Parameters:

| Name  | Type                | Default | Description  |
| ------ | ------------------- | ------------ | ------------ |
| valueA  | string | &quot;defaultValue&quot; | - |
| valueB  | number | 100 | - |
| valueC  | number |  Number.NaN | - |
| valueD  | boolean | true | - |
| valueE  | boolean | false | - |





**Returns:** string
The input value or the default value.


----


<a id="functionwithdoclink"></a>
###  functionWithDocLink

► **functionWithDocLink**(): void

*Defined in functions.ts:176*

See {@linkcode INameInterface} and [INameInterface's name property]{@link INameInterface.name}.
Also, check out {@link http://www.google.com|Google} and
{@link https://github.com GitHub}.

Taken from http://usejsdoc.org/tags-inline-link.html.





**Returns:** void

----


<a id="functionwithoptionalvalue"></a>
###  functionWithOptionalValue

► **functionWithOptionalValue**(requiredParam: *string*, optionalParam?: *string*): void

*Defined in functions.ts:52*

This is a function with a parameter that is optional.


#### Parameters:

| Name  | Type                | Default | Description  |
| ------ | ------------------- | ------------ | ------------ |
| requiredParam  | string | - | A normal parameter. |
| optionalParam  | string | - | An optional parameter. |





**Returns:** void

----


<a id="functionwithrest"></a>
###  functionWithRest

► **functionWithRest**(...rest: *string[]*): string

*Defined in functions.ts:78*

This is a function with rest parameter.


#### Parameters:

| Name  | Type                | Default | Description  |
| ------ | ------------------- | ------------ | ------------ |
| rest  | string[] | - | Multiple strings. |





**Returns:** string
The combined string.


----


<a id="genericfunction"></a>
###  genericFunction

► **genericFunction**T(value: *T*): T

*Defined in functions.ts:121*

This is a generic function.


**Type parameters:**

#### T 

The type parameter.

#### Parameters:

| Name  | Type                | Default | Description  |
| ------ | ------------------- | ------------ | ------------ |
| value  | T | - | The typed value. |





**Returns:** T
Returns the typed value.


----


<a id="internalfunction"></a>
###  internalFunction

► **internalFunction**(): void

*Defined in functions.ts:6*

This is an internal function.




**Returns:** void

----


<a id="multiplesignatures"></a>
###  multipleSignatures

► **multipleSignatures**(value: *string*): string► **multipleSignatures**(value: *object*): string

*Defined in functions.ts:88*

This is the first signature of a function with multiple signatures.


#### Parameters:

| Name  | Type                | Default | Description  |
| ------ | ------------------- | ------------ | ------------ |
| value  | string | - | The name value. |





**Returns:** string

*Defined in functions.ts:96*

This is the second signature of a function with multiple signatures.


#### Parameters:

| Name  | Type                | Default | Description  |
| ------ | ------------------- | ------------ | ------------ |
| value  | object | - | An object containing the name value. |





**Returns:** string

----


<a id="variablefunction"></a>
###  variableFunction

► **variableFunction**(paramZ: *string*, paramG: *any*, paramA: *[INameInterface](../interfaces/_classes_.inameinterface.md)*): number

*Defined in functions.ts:25*

This is a function with multiple arguments and a return value.


#### Parameters:

| Name  | Type                | Default | Description  |
| ------ | ------------------- | ------------ | ------------ |
| paramZ  | string | - | This is a string parameter. |
| paramG  | any | - | This is a parameter flagged with any.    This sentence is placed in the next line. |
| paramA  | [INameInterface](../interfaces/_classes_.inameinterface.md) | - | This is a **parameter** pointing to an interface. |





**Returns:** number

----



