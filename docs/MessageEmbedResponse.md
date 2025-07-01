# MessageEmbedResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** |  | [default to undefined]
**url** | **string** |  | [optional] [default to undefined]
**title** | **string** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**color** | **number** |  | [optional] [default to undefined]
**timestamp** | **string** |  | [optional] [default to undefined]
**fields** | [**Array&lt;MessageEmbedFieldResponse&gt;**](MessageEmbedFieldResponse.md) |  | [optional] [default to undefined]
**author** | [**MessageEmbedAuthorResponse**](MessageEmbedAuthorResponse.md) |  | [optional] [default to undefined]
**provider** | [**MessageEmbedProviderResponse**](MessageEmbedProviderResponse.md) |  | [optional] [default to undefined]
**image** | [**MessageEmbedImageResponse**](MessageEmbedImageResponse.md) |  | [optional] [default to undefined]
**thumbnail** | [**MessageEmbedImageResponse**](MessageEmbedImageResponse.md) |  | [optional] [default to undefined]
**video** | [**MessageEmbedVideoResponse**](MessageEmbedVideoResponse.md) |  | [optional] [default to undefined]
**footer** | [**MessageEmbedFooterResponse**](MessageEmbedFooterResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { MessageEmbedResponse } from 'dc_rest';

const instance: MessageEmbedResponse = {
    type,
    url,
    title,
    description,
    color,
    timestamp,
    fields,
    author,
    provider,
    image,
    thumbnail,
    video,
    footer,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
