# ScheduledEventUserResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**guild_scheduled_event_id** | **string** |  | [default to undefined]
**user_id** | **string** |  | [default to undefined]
**user** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**member** | [**GuildMemberResponse**](GuildMemberResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ScheduledEventUserResponse } from 'dc_rest';

const instance: ScheduledEventUserResponse = {
    guild_scheduled_event_id,
    user_id,
    user,
    member,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
