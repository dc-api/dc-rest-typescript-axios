# AddGroupDmUser201Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**recipients** | [**Array&lt;UserResponse&gt;**](UserResponse.md) |  | [default to undefined]
**last_message_id** | **string** |  | [optional] [default to undefined]
**last_pin_timestamp** | **string** |  | [optional] [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**owner_id** | **string** |  | [optional] [default to undefined]
**managed** | **boolean** |  | [optional] [default to undefined]
**application_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { AddGroupDmUser201Response } from 'dc_rest';

const instance: AddGroupDmUser201Response = {
    id,
    type,
    flags,
    recipients,
    last_message_id,
    last_pin_timestamp,
    name,
    icon,
    owner_id,
    managed,
    application_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
