# FriendInviteResponse


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

## Example

```typescript
import { FriendInviteResponse } from 'dc_rest';

const instance: FriendInviteResponse = {
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
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
