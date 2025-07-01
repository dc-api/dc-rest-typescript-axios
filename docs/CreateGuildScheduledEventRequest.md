# CreateGuildScheduledEventRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [default to undefined]
**scheduled_start_time** | **string** |  | [default to undefined]
**privacy_level** | **any** |  | [default to undefined]
**entity_type** | **number** |  | [default to undefined]
**entity_metadata** | **object** |  | [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**image** | **string** |  | [optional] [default to undefined]
**scheduled_end_time** | **string** |  | [optional] [default to undefined]
**channel_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateGuildScheduledEventRequest } from 'dc_rest';

const instance: CreateGuildScheduledEventRequest = {
    name,
    scheduled_start_time,
    privacy_level,
    entity_type,
    entity_metadata,
    description,
    image,
    scheduled_end_time,
    channel_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
