# MessageAttachmentResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**filename** | **string** |  | [default to undefined]
**size** | **number** |  | [default to undefined]
**url** | **string** |  | [default to undefined]
**proxy_url** | **string** |  | [default to undefined]
**width** | **number** |  | [optional] [default to undefined]
**height** | **number** |  | [optional] [default to undefined]
**duration_secs** | **number** |  | [optional] [default to undefined]
**waveform** | **string** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**content_type** | **string** |  | [optional] [default to undefined]
**ephemeral** | **boolean** |  | [optional] [default to undefined]
**title** | **string** |  | [optional] [default to undefined]
**application** | [**ApplicationResponse**](ApplicationResponse.md) |  | [optional] [default to undefined]
**clip_created_at** | **string** |  | [optional] [default to undefined]
**clip_participants** | [**Array&lt;UserResponse&gt;**](UserResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { MessageAttachmentResponse } from 'dc_rest';

const instance: MessageAttachmentResponse = {
    id,
    filename,
    size,
    url,
    proxy_url,
    width,
    height,
    duration_secs,
    waveform,
    description,
    content_type,
    ephemeral,
    title,
    application,
    clip_created_at,
    clip_participants,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
