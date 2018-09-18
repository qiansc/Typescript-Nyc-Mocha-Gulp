[DMR Pipeline](../README.md) > [Middleware](../classes/middleware.md)

# Class: Middleware

Middleware abstract Class
*__export__*: 

*__abstract__*: 

*__class__*: Middleware

## Hierarchy

**Middleware**

## Index

### Constructors

* [constructor](middleware.md#constructor)

### Properties

* [options](middleware.md#options)

### Methods

* [_handle](middleware.md#_handle)
* [handle](middleware.md#handle)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new Middleware**(options?: *[MiddlewareOptions](../interfaces/middlewareoptions.md)*): [Middleware](middleware.md)

*Defined in [middleware.ts:15](https://github.com/qiansc/Typescript-Nyc-Mocha-Gulp/blob/f011cd6/src/middleware.ts#L15)*

**Parameters:**

| Param | Type | Default value |
| ------ | ------ | ------ |
| `Default value` options | [MiddlewareOptions](../interfaces/middlewareoptions.md) |  {} |

**Returns:** [Middleware](middleware.md)

___

## Properties

<a id="options"></a>

### `<Protected>` options

**● options**: *[MiddlewareOptions](../interfaces/middlewareoptions.md)*

*Defined in [middleware.ts:15](https://github.com/qiansc/Typescript-Nyc-Mocha-Gulp/blob/f011cd6/src/middleware.ts#L15)*

___

## Methods

<a id="_handle"></a>

### `<Protected>``<Abstract>` _handle

▸ **_handle**(result: *[Result](../#result)*, gather: *[GatherCallback](../#gathercallback)*): `void`

*Defined in [middleware.ts:22](https://github.com/qiansc/Typescript-Nyc-Mocha-Gulp/blob/f011cd6/src/middleware.ts#L22)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| result | [Result](../#result) |
| gather | [GatherCallback](../#gathercallback) |

**Returns:** `void`

___
<a id="handle"></a>

###  handle

▸ **handle**(result: *[Result](../#result)*, gather: *[GatherCallback](../#gathercallback)*): `void`

*Defined in [middleware.ts:19](https://github.com/qiansc/Typescript-Nyc-Mocha-Gulp/blob/f011cd6/src/middleware.ts#L19)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| result | [Result](../#result) |
| gather | [GatherCallback](../#gathercallback) |

**Returns:** `void`

___

