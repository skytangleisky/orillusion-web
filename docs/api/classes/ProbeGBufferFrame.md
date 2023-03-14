# Class: ProbeGBufferFrame

## Hierarchy

- [`RTFrame`](RTFrame.md)

  ↳ **`ProbeGBufferFrame`**


### Constructors

- [constructor](ProbeGBufferFrame.md#constructor)

### Methods

- [crateGBuffer](ProbeGBufferFrame.md#crategbuffer)
- [clone2Frame](ProbeGBufferFrame.md#clone2frame)
- [clone](ProbeGBufferFrame.md#clone)

### Properties

- [label](ProbeGBufferFrame.md#label)
- [customSize](ProbeGBufferFrame.md#customsize)
- [attachments](ProbeGBufferFrame.md#attachments)
- [rtDescripts](ProbeGBufferFrame.md#rtdescripts)
- [zPreTexture](ProbeGBufferFrame.md#zpretexture)
- [depthTexture](ProbeGBufferFrame.md#depthtexture)
- [depthViewIndex](ProbeGBufferFrame.md#depthviewindex)
- [depthCleanValue](ProbeGBufferFrame.md#depthcleanvalue)
- [depthLoadOp](ProbeGBufferFrame.md#depthloadop)
- [isOutTarget](ProbeGBufferFrame.md#isouttarget)

## Constructors

### constructor

• **new ProbeGBufferFrame**(`rtWidth`, `rtHeight`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `rtWidth` | `number` |
| `rtHeight` | `number` |

#### Overrides

[RTFrame](RTFrame.md).[constructor](RTFrame.md#constructor)

#### Defined in

[src/engine/gfx/renderJob/jobs/ProbeGBufferFrame.ts:8](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/ProbeGBufferFrame.ts#L8)

## Methods

### crateGBuffer

▸ **crateGBuffer**(`rtWidth`, `rtHeight`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `rtWidth` | `number` |
| `rtHeight` | `number` |

#### Returns

`void`

#### Defined in

[src/engine/gfx/renderJob/jobs/ProbeGBufferFrame.ts:13](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/ProbeGBufferFrame.ts#L13)

___

### clone2Frame

▸ **clone2Frame**(`rtFrame`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `rtFrame` | [`RTFrame`](RTFrame.md) |

#### Returns

`void`

#### Inherited from

[RTFrame](RTFrame.md).[clone2Frame](RTFrame.md#clone2frame)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:27](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L27)

___

### clone

▸ **clone**(): [`RTFrame`](RTFrame.md)

#### Returns

[`RTFrame`](RTFrame.md)

#### Inherited from

[RTFrame](RTFrame.md).[clone](RTFrame.md#clone)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:42](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L42)

## Properties

### label

• **label**: `string`

#### Inherited from

[RTFrame](RTFrame.md).[label](RTFrame.md#label)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:6](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L6)

___

### customSize

• **customSize**: `boolean` = `false`

#### Inherited from

[RTFrame](RTFrame.md).[customSize](RTFrame.md#customsize)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:7](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L7)

___

### attachments

• **attachments**: `VirtualTexture`[]

#### Inherited from

[RTFrame](RTFrame.md).[attachments](RTFrame.md#attachments)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:8](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L8)

___

### rtDescripts

• **rtDescripts**: [`RTDescript`](RTDescript.md)[]

#### Inherited from

[RTFrame](RTFrame.md).[rtDescripts](RTFrame.md#rtdescripts)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:9](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L9)

___

### zPreTexture

• **zPreTexture**: `VirtualTexture`

#### Inherited from

[RTFrame](RTFrame.md).[zPreTexture](RTFrame.md#zpretexture)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:11](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L11)

___

### depthTexture

• **depthTexture**: `VirtualTexture`

#### Inherited from

[RTFrame](RTFrame.md).[depthTexture](RTFrame.md#depthtexture)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:12](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L12)

___

### depthViewIndex

• **depthViewIndex**: `number` = `0`

#### Inherited from

[RTFrame](RTFrame.md).[depthViewIndex](RTFrame.md#depthviewindex)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:14](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L14)

___

### depthCleanValue

• **depthCleanValue**: `number` = `1`

#### Inherited from

[RTFrame](RTFrame.md).[depthCleanValue](RTFrame.md#depthcleanvalue)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:15](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L15)

___

### depthLoadOp

• **depthLoadOp**: `GPULoadOp`

#### Inherited from

[RTFrame](RTFrame.md).[depthLoadOp](RTFrame.md#depthloadop)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:16](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L16)

___

### isOutTarget

• **isOutTarget**: `boolean` = `true`

#### Inherited from

[RTFrame](RTFrame.md).[isOutTarget](RTFrame.md#isouttarget)

#### Defined in

[src/engine/gfx/renderJob/jobs/RTFrame.ts:17](https://github.com/Orillusion/orillusion/blob/main/src/engine/gfx/renderJob/jobs/RTFrame.ts#L17)