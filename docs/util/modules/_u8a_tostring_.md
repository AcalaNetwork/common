

# Functions

<a id="u8atostring"></a>

##  u8aToString

▸ **u8aToString**(value?: *`Uint8Array`*): `string`

*Defined in [u8a/toString.ts:28](https://github.com/polkadot-js/common/blob/3988773/packages/util/src/u8a/toString.ts#L28)*

*__name__*: u8aToString

*__signature__*: u8aToString (value?: UInt8Array): string

*__summary__*: Creates a utf-8 string from a Uint8Array object.

*__description__*: `UInt8Array` input values return the actual decoded utf-8 string. `null` or `undefined` values returns an empty string.

*__example__*:   

```javascript
import { u8aToString } from '@polkadot/util';

u8aToString(new Uint8Array([0x68, 0x65, 0x6c, 0x6c, 0x6f])); // hello
```

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` value | `Uint8Array` |

**Returns:** `string`

___

