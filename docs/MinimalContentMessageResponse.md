# MinimalContentMessageResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **number** |  | [default to undefined]
**content** | **string** |  | [default to undefined]
**mentions** | [**Array&lt;UserResponse&gt;**](UserResponse.md) |  | [default to undefined]
**mention_roles** | **Set&lt;string&gt;** |  | [default to undefined]
**attachments** | [**Array&lt;MessageAttachmentResponse&gt;**](MessageAttachmentResponse.md) |  | [default to undefined]
**embeds** | [**Array&lt;MessageEmbedResponse&gt;**](MessageEmbedResponse.md) |  | [default to undefined]
**timestamp** | **string** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**components** | [**Array&lt;BasicMessageResponseComponentsInner&gt;**](BasicMessageResponseComponentsInner.md) |  | [default to undefined]
**edited_timestamp** | **string** |  | [optional] [default to undefined]
**resolved** | [**ResolvedObjectsResponse**](ResolvedObjectsResponse.md) |  | [optional] [default to undefined]
**stickers** | [**Array&lt;GetSticker200Response&gt;**](GetSticker200Response.md) |  | [optional] [default to undefined]
**sticker_items** | [**Array&lt;MessageStickerItemResponse&gt;**](MessageStickerItemResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { MinimalContentMessageResponse } from 'dc_rest';

const instance: MinimalContentMessageResponse = {
    type,
    content,
    mentions,
    mention_roles,
    attachments,
    embeds,
    timestamp,
    flags,
    components,
    edited_timestamp,
    resolved,
    stickers,
    sticker_items,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
