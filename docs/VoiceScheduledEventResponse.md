# VoiceScheduledEventResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**guild_id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**scheduled_start_time** | **string** |  | [default to undefined]
**status** | **number** |  | [default to undefined]
**entity_type** | **number** |  | [default to undefined]
**privacy_level** | **any** |  | [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**channel_id** | **string** |  | [optional] [default to undefined]
**creator_id** | **string** |  | [optional] [default to undefined]
**creator** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**image** | **string** |  | [optional] [default to undefined]
**scheduled_end_time** | **string** |  | [optional] [default to undefined]
**entity_id** | **string** |  | [optional] [default to undefined]
**user_count** | **number** |  | [optional] [default to undefined]
**user_rsvp** | [**ScheduledEventUserResponse**](ScheduledEventUserResponse.md) |  | [optional] [default to undefined]
**entity_metadata** | **object** |  | [optional] [default to undefined]

## Example

```typescript
import { VoiceScheduledEventResponse } from 'dc_rest';

const instance: VoiceScheduledEventResponse = {
    id,
    guild_id,
    name,
    scheduled_start_time,
    status,
    entity_type,
    privacy_level,
    description,
    channel_id,
    creator_id,
    creator,
    image,
    scheduled_end_time,
    entity_id,
    user_count,
    user_rsvp,
    entity_metadata,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
