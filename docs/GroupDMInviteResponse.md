# GroupDMInviteResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **string** |  | [default to undefined]
**type** | **number** |  | [optional] [default to undefined]
**inviter** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**max_age** | **number** |  | [optional] [default to undefined]
**created_at** | **string** |  | [optional] [default to undefined]
**expires_at** | **string** |  | [optional] [default to undefined]
**channel** | [**InviteChannelResponse**](InviteChannelResponse.md) |  | [optional] [default to undefined]
**approximate_member_count** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { GroupDMInviteResponse } from 'dc_rest';

const instance: GroupDMInviteResponse = {
    code,
    type,
    inviter,
    max_age,
    created_at,
    expires_at,
    channel,
    approximate_member_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
