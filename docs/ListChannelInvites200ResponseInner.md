# ListChannelInvites200ResponseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **string** |  | [default to undefined]
**type** | **number** |  | [optional] [default to undefined]
**inviter** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**max_age** | **number** |  | [optional] [default to undefined]
**created_at** | **string** |  | [optional] [default to undefined]
**expires_at** | **string** |  | [optional] [default to undefined]
**friends_count** | **number** |  | [optional] [default to undefined]
**channel** | [**InviteChannelResponse**](InviteChannelResponse.md) |  | [optional] [default to undefined]
**is_contact** | **boolean** |  | [optional] [default to undefined]
**uses** | **number** |  | [optional] [default to undefined]
**max_uses** | **number** |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]
**approximate_member_count** | **number** |  | [optional] [default to undefined]
**guild** | [**InviteGuildResponse**](InviteGuildResponse.md) |  | [optional] [default to undefined]
**guild_id** | **string** |  | [optional] [default to undefined]
**target_type** | **number** |  | [optional] [default to undefined]
**target_user** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**target_application** | [**InviteApplicationResponse**](InviteApplicationResponse.md) |  | [optional] [default to undefined]
**guild_scheduled_event** | [**ScheduledEventResponse**](ScheduledEventResponse.md) |  | [optional] [default to undefined]
**temporary** | **boolean** |  | [optional] [default to undefined]
**approximate_presence_count** | **number** |  | [optional] [default to undefined]
**is_nickname_changeable** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { ListChannelInvites200ResponseInner } from 'dc_rest';

const instance: ListChannelInvites200ResponseInner = {
    code,
    type,
    inviter,
    max_age,
    created_at,
    expires_at,
    friends_count,
    channel,
    is_contact,
    uses,
    max_uses,
    flags,
    approximate_member_count,
    guild,
    guild_id,
    target_type,
    target_user,
    target_application,
    guild_scheduled_event,
    temporary,
    approximate_presence_count,
    is_nickname_changeable,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
