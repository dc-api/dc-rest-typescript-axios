# StickerPackResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**sku_id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**stickers** | [**Array&lt;StandardStickerResponse&gt;**](StandardStickerResponse.md) |  | [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**cover_sticker_id** | **string** |  | [optional] [default to undefined]
**banner_asset_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { StickerPackResponse } from 'dc_rest';

const instance: StickerPackResponse = {
    id,
    sku_id,
    name,
    stickers,
    description,
    cover_sticker_id,
    banner_asset_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
