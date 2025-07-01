# MessageComponentInteractionMetadataResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**authorizing_integration_owners** | **{ [key: string]: string; }** |  | [default to undefined]
**interacted_message_id** | **string** |  | [default to undefined]
**user** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**original_response_message_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { MessageComponentInteractionMetadataResponse } from 'dc_rest';

const instance: MessageComponentInteractionMetadataResponse = {
    id,
    type,
    authorizing_integration_owners,
    interacted_message_id,
    user,
    original_response_message_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
