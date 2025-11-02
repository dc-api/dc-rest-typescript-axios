# PrivateGroupChannelResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**recipients** | [**Array&lt;UserResponse&gt;**](UserResponse.md) |  | [default to undefined]
**owner_id** | **string** |  | [default to undefined]
**last_message_id** | **string** |  | [optional] [default to undefined]
**last_pin_timestamp** | **string** |  | [optional] [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**managed** | **boolean** |  | [optional] [default to undefined]
**application_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { PrivateGroupChannelResponse } from 'dc_rest';

const instance: PrivateGroupChannelResponse = {
    id,
    type,
    flags,
    recipients,
    owner_id,
    last_message_id,
    last_pin_timestamp,
    name,
    icon,
    managed,
    application_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
