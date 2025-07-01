# MessageReferenceRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_id** | **string** |  | [default to undefined]
**guild_id** | **string** |  | [optional] [default to undefined]
**channel_id** | **string** |  | [optional] [default to undefined]
**fail_if_not_exists** | **boolean** |  | [optional] [default to undefined]
**type** | **any** |  | [optional] [default to undefined]

## Example

```typescript
import { MessageReferenceRequest } from 'dc_rest';

const instance: MessageReferenceRequest = {
    message_id,
    guild_id,
    channel_id,
    fail_if_not_exists,
    type,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
