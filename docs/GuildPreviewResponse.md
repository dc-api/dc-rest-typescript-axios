# GuildPreviewResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**features** | **Set&lt;string&gt;** |  | [default to undefined]
**approximate_member_count** | **number** |  | [default to undefined]
**approximate_presence_count** | **number** |  | [default to undefined]
**emojis** | [**Array&lt;EmojiResponse&gt;**](EmojiResponse.md) |  | [default to undefined]
**stickers** | [**Array&lt;GuildStickerResponse&gt;**](GuildStickerResponse.md) |  | [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**home_header** | **string** |  | [optional] [default to undefined]
**splash** | **string** |  | [optional] [default to undefined]
**discovery_splash** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildPreviewResponse } from 'dc_rest';

const instance: GuildPreviewResponse = {
    id,
    name,
    features,
    approximate_member_count,
    approximate_presence_count,
    emojis,
    stickers,
    icon,
    description,
    home_header,
    splash,
    discovery_splash,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
