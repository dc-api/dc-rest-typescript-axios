# CreateStageInstanceRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**topic** | **string** |  | [default to undefined]
**channel_id** | **string** |  | [default to undefined]
**privacy_level** | **number** |  | [optional] [default to undefined]
**guild_scheduled_event_id** | **string** |  | [optional] [default to undefined]
**send_start_notification** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateStageInstanceRequest } from 'dc_rest';

const instance: CreateStageInstanceRequest = {
    topic,
    channel_id,
    privacy_level,
    guild_scheduled_event_id,
    send_start_notification,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
