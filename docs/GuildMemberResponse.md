# GuildMemberResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**flags** | **number** |  | [default to undefined]
**joined_at** | **string** |  | [default to undefined]
**pending** | **boolean** |  | [default to undefined]
**roles** | **Set&lt;string&gt;** |  | [default to undefined]
**user** | [**UserResponse**](UserResponse.md) |  | [default to undefined]
**mute** | **boolean** |  | [default to undefined]
**deaf** | **boolean** |  | [default to undefined]
**avatar** | **string** |  | [optional] [default to undefined]
**avatar_decoration_data** | [**UserAvatarDecorationResponse**](UserAvatarDecorationResponse.md) |  | [optional] [default to undefined]
**banner** | **string** |  | [optional] [default to undefined]
**communication_disabled_until** | **string** |  | [optional] [default to undefined]
**nick** | **string** |  | [optional] [default to undefined]
**premium_since** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildMemberResponse } from 'dc_rest';

const instance: GuildMemberResponse = {
    flags,
    joined_at,
    pending,
    roles,
    user,
    mute,
    deaf,
    avatar,
    avatar_decoration_data,
    banner,
    communication_disabled_until,
    nick,
    premium_since,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
