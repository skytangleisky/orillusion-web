# Class: SolidColorSky

create a cube texture, which filled by solid color.

## Hierarchy

- [`HDRTextureCube`](HDRTextureCube.md)

  ↳ **`SolidColorSky`**


### Properties

- [name](SolidColorSky.md#name)
- [url](SolidColorSky.md#url)
- [pid](SolidColorSky.md#pid)
- [view](SolidColorSky.md#view)
- [gpuSampler](SolidColorSky.md#gpusampler)
- [gpuSampler\_comparison](SolidColorSky.md#gpusampler_comparison)
- [format](SolidColorSky.md#format)
- [usage](SolidColorSky.md#usage)
- [numberLayer](SolidColorSky.md#numberlayer)
- [viewDescriptor](SolidColorSky.md#viewdescriptor)
- [textureDescriptor](SolidColorSky.md#texturedescriptor)
- [sampler\_comparisonBindingLayout](SolidColorSky.md#sampler_comparisonbindinglayout)
- [flipY](SolidColorSky.md#flipy)
- [isVideoTexture](SolidColorSky.md#isvideotexture)
- [mipmapCount](SolidColorSky.md#mipmapcount)
- [width](SolidColorSky.md#width)
- [height](SolidColorSky.md#height)
- [depthOrArrayLayers](SolidColorSky.md#depthorarraylayers)
- [visibility](SolidColorSky.md#visibility)
- [textureBindingLayout](SolidColorSky.md#texturebindinglayout)
- [samplerBindingLayout](SolidColorSky.md#samplerbindinglayout)

### Methods

- [init](SolidColorSky.md#init)
- [getGPUTexture](SolidColorSky.md#getgputexture)
- [getGPUView](SolidColorSky.md#getgpuview)
- [bindStateChange](SolidColorSky.md#bindstatechange)
- [unBindStateChange](SolidColorSky.md#unbindstatechange)
- [destoryView](SolidColorSky.md#destoryview)
- [destroy](SolidColorSky.md#destroy)
- [createFromHDRData](SolidColorSky.md#createfromhdrdata)
- [createFromTexture](SolidColorSky.md#createfromtexture)
- [uploadErpTexture](SolidColorSky.md#uploaderptexture)
- [uploadTexture](SolidColorSky.md#uploadtexture)
- [load](SolidColorSky.md#load)

### Accessors

- [useMipmap](SolidColorSky.md#usemipmap)
- [addressModeU](SolidColorSky.md#addressmodeu)
- [addressModeV](SolidColorSky.md#addressmodev)
- [addressModeW](SolidColorSky.md#addressmodew)
- [magFilter](SolidColorSky.md#magfilter)
- [minFilter](SolidColorSky.md#minfilter)
- [mipmapFilter](SolidColorSky.md#mipmapfilter)
- [lodMinClamp](SolidColorSky.md#lodminclamp)
- [lodMaxClamp](SolidColorSky.md#lodmaxclamp)
- [compare](SolidColorSky.md#compare)
- [maxAnisotropy](SolidColorSky.md#maxanisotropy)
- [color](SolidColorSky.md#color)

### Constructors

- [constructor](SolidColorSky.md#constructor)

## Properties

### name

• **name**: `string`

name of texture

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[name](HDRTextureCube.md#name)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:14](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L14)

___

### url

• **url**: `string`

source url

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[url](HDRTextureCube.md#url)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:18](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L18)

___

### pid

• **pid**: `number`

Return index in texture array

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[pid](HDRTextureCube.md#pid)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:27](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L27)

___

### view

• **view**: `GPUTextureView`

GPUTextureView

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[view](HDRTextureCube.md#view)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:32](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L32)

___

### gpuSampler

• **gpuSampler**: `GPUSampler`

GPUSampler

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[gpuSampler](HDRTextureCube.md#gpusampler)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:37](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L37)

___

### gpuSampler\_comparison

• **gpuSampler\_comparison**: `GPUSampler`

GPUSampler for comparison

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[gpuSampler_comparison](HDRTextureCube.md#gpusampler_comparison)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:42](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L42)

___

### format

• **format**: `GPUTextureFormat`

GPUTextureFormat

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[format](HDRTextureCube.md#format)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:47](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L47)

___

### usage

• **usage**: `number`

GPUTextureUsage

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[usage](HDRTextureCube.md#usage)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:51](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L51)

___

### numberLayer

• **numberLayer**: `number` = `1`

depth or layers, default value is 1

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[numberLayer](HDRTextureCube.md#numberlayer)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:67](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L67)

___

### viewDescriptor

• **viewDescriptor**: `GPUTextureViewDescriptor`

GPUTextureViewDescriptor

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[viewDescriptor](HDRTextureCube.md#viewdescriptor)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:71](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L71)

___

### textureDescriptor

• **textureDescriptor**: `GPUTextureDescriptor`

GPUTextureDescriptor

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[textureDescriptor](HDRTextureCube.md#texturedescriptor)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:75](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L75)

___

### sampler\_comparisonBindingLayout

• **sampler\_comparisonBindingLayout**: `GPUSamplerBindingLayout`

GPUSamplerBindingLayout

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[sampler_comparisonBindingLayout](HDRTextureCube.md#sampler_comparisonbindinglayout)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:97](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L97)

___

### flipY

• **flipY**: `boolean`

whether to flip the image on the y-axis

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[flipY](HDRTextureCube.md#flipy)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:104](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L104)

___

### isVideoTexture

• `Optional` **isVideoTexture**: `boolean`

whether is video texture

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[isVideoTexture](HDRTextureCube.md#isvideotexture)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:108](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L108)

___

### mipmapCount

• **mipmapCount**: `number` = `1`

mipmap Count, default value is 1

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[mipmapCount](HDRTextureCube.md#mipmapcount)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:116](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L116)

___

### width

• **width**: `number` = `4`

texture width, default value is 4

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[width](HDRTextureCube.md#width)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/TextureCube.ts:12](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/TextureCube.ts#L12)

___

### height

• **height**: `number` = `4`

texture height, default value is 4

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[height](HDRTextureCube.md#height)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/TextureCube.ts:16](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/TextureCube.ts#L16)

___

### depthOrArrayLayers

• **depthOrArrayLayers**: `number` = `6`

depth or array layers, default value is 6

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[depthOrArrayLayers](HDRTextureCube.md#depthorarraylayers)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/TextureCube.ts:20](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/TextureCube.ts#L20)

___

### visibility

• **visibility**: `number` = `GPUShaderStage.FRAGMENT`

GPUShaderStage

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[visibility](HDRTextureCube.md#visibility)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/TextureCube.ts:25](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/TextureCube.ts#L25)

___

### textureBindingLayout

• **textureBindingLayout**: `GPUTextureBindingLayout`

GPUTextureBindingLayout

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[textureBindingLayout](HDRTextureCube.md#texturebindinglayout)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/TextureCube.ts:30](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/TextureCube.ts#L30)

___

### samplerBindingLayout

• **samplerBindingLayout**: `GPUSamplerBindingLayout`

GPUSamplerBindingLayout

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[samplerBindingLayout](HDRTextureCube.md#samplerbindinglayout)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/TextureCube.ts:38](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/TextureCube.ts#L38)

## Methods

### init

▸ **init**(): [`SolidColorSky`](SolidColorSky.md)

#### Returns

[`SolidColorSky`](SolidColorSky.md)

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[init](HDRTextureCube.md#init)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:138](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L138)

___

### getGPUTexture

▸ **getGPUTexture**(): `GPUTexture`

create or get GPUTexture

#### Returns

`GPUTexture`

GPUTexture

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[getGPUTexture](HDRTextureCube.md#getgputexture)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:291](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L291)

___

### getGPUView

▸ **getGPUView**(`index?`): `GPUTextureView` \| `GPUExternalTexture`

create or get GPUTextureView

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `index` | `number` | `0` |

#### Returns

`GPUTextureView` \| `GPUExternalTexture`

GPUTextureView | GPUExternalTexture

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[getGPUView](HDRTextureCube.md#getgpuview)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:302](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L302)

___

### bindStateChange

▸ **bindStateChange**(`fun`, `ref`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fun` | `Function` |
| `ref` | `any` |

#### Returns

`void`

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[bindStateChange](HDRTextureCube.md#bindstatechange)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:313](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L313)

___

### unBindStateChange

▸ **unBindStateChange**(`ref`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ref` | `any` |

#### Returns

`void`

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[unBindStateChange](HDRTextureCube.md#unbindstatechange)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:317](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L317)

___

### destoryView

▸ **destoryView**(): [`SolidColorSky`](SolidColorSky.md)

#### Returns

[`SolidColorSky`](SolidColorSky.md)

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[destoryView](HDRTextureCube.md#destoryview)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:328](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L328)

___

### destroy

▸ **destroy**(): `void`

release the texture

#### Returns

`void`

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[destroy](HDRTextureCube.md#destroy)

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:336](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L336)

___

### createFromHDRData

▸ **createFromHDRData**(`size`, `data`): [`SolidColorSky`](SolidColorSky.md)

fill this texture by array of numbers;the format as [red0, green0, blue0, alpha0, red1, green1, blue1, alpha1...]

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `size` | `number` | assign the cube texture size |
| `data` | `Object` | raw data of cubeTexture; the format is { width: number; height: number; array: Uint8Array } |
| `data.width` | `number` | - |
| `data.height` | `number` | - |
| `data.array` | `Uint8Array` | - |

#### Returns

[`SolidColorSky`](SolidColorSky.md)

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[createFromHDRData](HDRTextureCube.md#createfromhdrdata)

#### Defined in

[src/textures/HDRTextureCube.ts:36](https://github.com/Orillusion/orillusion/blob/main/src/textures/HDRTextureCube.ts#L36)

___

### createFromTexture

▸ **createFromTexture**(`size`, `texture`): [`SolidColorSky`](SolidColorSky.md)

fill this texture by a texture2D, which is a 360 panorama image

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `size` | `number` | assign the cube texture size |
| `texture` | [`Texture`](Texture.md) | the image texture |

#### Returns

[`SolidColorSky`](SolidColorSky.md)

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[createFromTexture](HDRTextureCube.md#createfromtexture)

#### Defined in

[src/textures/HDRTextureCube.ts:51](https://github.com/Orillusion/orillusion/blob/main/src/textures/HDRTextureCube.ts#L51)

___

### uploadErpTexture

▸ **uploadErpTexture**(`texture`): [`SolidColorSky`](SolidColorSky.md)

fill this texture by a texture2D, which is a 360 panorama image

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `texture` | [`Texture`](Texture.md) | a panorama image |

#### Returns

[`SolidColorSky`](SolidColorSky.md)

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[uploadErpTexture](HDRTextureCube.md#uploaderptexture)

#### Defined in

[src/textures/HDRTextureCube.ts:76](https://github.com/Orillusion/orillusion/blob/main/src/textures/HDRTextureCube.ts#L76)

___

### uploadTexture

▸ **uploadTexture**(`mip`, `texture`): [`SolidColorSky`](SolidColorSky.md)

fill this texture by a texture2D, which is a 360 panorama image
assign mipmap level

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mip` | `number` | mipmap level |
| `texture` | [`Texture`](Texture.md) | a panorama image |

#### Returns

[`SolidColorSky`](SolidColorSky.md)

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[uploadTexture](HDRTextureCube.md#uploadtexture)

#### Defined in

[src/textures/HDRTextureCube.ts:92](https://github.com/Orillusion/orillusion/blob/main/src/textures/HDRTextureCube.ts#L92)

___

### load

▸ **load**(`url`, `loaderFunctions?`): `Promise`<[`HDRTextureCube`](HDRTextureCube.md)\>

load texture data from web url, which is a 360 panorama image

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | web url |
| `loaderFunctions?` | [`LoaderFunctions`](../types/LoaderFunctions.md) | callback function when load complete |

#### Returns

`Promise`<[`HDRTextureCube`](HDRTextureCube.md)\>

#### Inherited from

[HDRTextureCube](HDRTextureCube.md).[load](HDRTextureCube.md#load)

#### Defined in

[src/textures/HDRTextureCube.ts:154](https://github.com/Orillusion/orillusion/blob/main/src/textures/HDRTextureCube.ts#L154)

## Accessors

### useMipmap

• `get` **useMipmap**(): `boolean`

enable/disable mipmap

#### Returns

`boolean`

#### Inherited from

HDRTextureCube.useMipmap

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:233](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L233)

• `set` **useMipmap**(`value`): `void`

get mipmap

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.useMipmap

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:240](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L240)

___

### addressModeU

• `get` **addressModeU**(): `GPUAddressMode`

#### Returns

`GPUAddressMode`

#### Inherited from

HDRTextureCube.addressModeU

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:346](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L346)

• `set` **addressModeU**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `GPUAddressMode` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.addressModeU

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:349](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L349)

___

### addressModeV

• `get` **addressModeV**(): `GPUAddressMode`

#### Returns

`GPUAddressMode`

#### Inherited from

HDRTextureCube.addressModeV

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:358](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L358)

• `set` **addressModeV**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `GPUAddressMode` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.addressModeV

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:361](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L361)

___

### addressModeW

• `get` **addressModeW**(): `GPUAddressMode`

#### Returns

`GPUAddressMode`

#### Inherited from

HDRTextureCube.addressModeW

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:372](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L372)

• `set` **addressModeW**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `GPUAddressMode` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.addressModeW

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:375](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L375)

___

### magFilter

• `get` **magFilter**(): `GPUFilterMode`

#### Returns

`GPUFilterMode`

#### Inherited from

HDRTextureCube.magFilter

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:386](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L386)

• `set` **magFilter**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `GPUFilterMode` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.magFilter

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:389](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L389)

___

### minFilter

• `get` **minFilter**(): `GPUFilterMode`

#### Returns

`GPUFilterMode`

#### Inherited from

HDRTextureCube.minFilter

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:399](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L399)

• `set` **minFilter**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `GPUFilterMode` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.minFilter

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:402](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L402)

___

### mipmapFilter

• `get` **mipmapFilter**(): `GPUMipmapFilterMode`

#### Returns

`GPUMipmapFilterMode`

#### Inherited from

HDRTextureCube.mipmapFilter

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:412](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L412)

• `set` **mipmapFilter**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `GPUMipmapFilterMode` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.mipmapFilter

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:415](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L415)

___

### lodMinClamp

• `get` **lodMinClamp**(): `number`

#### Returns

`number`

#### Inherited from

HDRTextureCube.lodMinClamp

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:424](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L424)

• `set` **lodMinClamp**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.lodMinClamp

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:427](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L427)

___

### lodMaxClamp

• `get` **lodMaxClamp**(): `number`

#### Returns

`number`

#### Inherited from

HDRTextureCube.lodMaxClamp

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:438](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L438)

• `set` **lodMaxClamp**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.lodMaxClamp

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:441](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L441)

___

### compare

• `get` **compare**(): `GPUCompareFunction`

#### Returns

`GPUCompareFunction`

#### Inherited from

HDRTextureCube.compare

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:454](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L454)

• `set` **compare**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `GPUCompareFunction` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.compare

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:457](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L457)

___

### maxAnisotropy

• `get` **maxAnisotropy**(): `number`

#### Returns

`number`

#### Inherited from

HDRTextureCube.maxAnisotropy

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:470](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L470)

• `set` **maxAnisotropy**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Inherited from

HDRTextureCube.maxAnisotropy

#### Defined in

[src/gfx/graphics/webGpu/core/texture/Texture.ts:473](https://github.com/Orillusion/orillusion/blob/main/src/gfx/graphics/webGpu/core/texture/Texture.ts#L473)

___

### color

• `get` **color**(): [`Color`](Color.md)

#### Returns

[`Color`](Color.md)

#### Defined in

[src/textures/SolidColorSky.ts:41](https://github.com/Orillusion/orillusion/blob/main/src/textures/SolidColorSky.ts#L41)

• `set` **color**(`value`): `void`

change solid color

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | [`Color`](Color.md) | target color |

#### Returns

`void`

#### Defined in

[src/textures/SolidColorSky.ts:50](https://github.com/Orillusion/orillusion/blob/main/src/textures/SolidColorSky.ts#L50)

## Constructors

### constructor

• **new SolidColorSky**(`color`)

create a cube texture, which filled by solid color.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `color` | [`Color`](Color.md) | solid color |

#### Overrides

[HDRTextureCube](HDRTextureCube.md).[constructor](HDRTextureCube.md#constructor)

#### Defined in

[src/textures/SolidColorSky.ts:22](https://github.com/Orillusion/orillusion/blob/main/src/textures/SolidColorSky.ts#L22)
