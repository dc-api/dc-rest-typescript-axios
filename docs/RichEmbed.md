# RichEmbed


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** |  | [optional] [default to undefined]
**url** | **string** |  | [optional] [default to undefined]
**title** | **string** |  | [optional] [default to undefined]
**color** | **number** |  | [optional] [default to undefined]
**timestamp** | **string** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**author** | [**RichEmbedAuthor**](RichEmbedAuthor.md) |  | [optional] [default to undefined]
**image** | [**RichEmbedImage**](RichEmbedImage.md) |  | [optional] [default to undefined]
**thumbnail** | [**RichEmbedThumbnail**](RichEmbedThumbnail.md) |  | [optional] [default to undefined]
**footer** | [**RichEmbedFooter**](RichEmbedFooter.md) |  | [optional] [default to undefined]
**fields** | [**Array&lt;RichEmbedField&gt;**](RichEmbedField.md) |  | [optional] [default to undefined]
**provider** | [**RichEmbedProvider**](RichEmbedProvider.md) |  | [optional] [default to undefined]
**video** | [**RichEmbedVideo**](RichEmbedVideo.md) |  | [optional] [default to undefined]

## Example

```typescript
import { RichEmbed } from 'dc_rest';

const instance: RichEmbed = {
    type,
    url,
    title,
    color,
    timestamp,
    description,
    author,
    image,
    thumbnail,
    footer,
    fields,
    provider,
    video,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
