# UserPIIResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**username** | **string** |  | [default to undefined]
**discriminator** | **string** |  | [default to undefined]
**public_flags** | **number** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**mfa_enabled** | **boolean** |  | [default to undefined]
**locale** | **string** |  | [default to undefined]
**avatar** | **string** |  | [optional] [default to undefined]
**bot** | **boolean** |  | [optional] [default to undefined]
**system** | **boolean** |  | [optional] [default to undefined]
**banner** | **string** |  | [optional] [default to undefined]
**accent_color** | **number** |  | [optional] [default to undefined]
**global_name** | **string** |  | [optional] [default to undefined]
**avatar_decoration_data** | [**UserAvatarDecorationResponse**](UserAvatarDecorationResponse.md) |  | [optional] [default to undefined]
**collectibles** | [**UserCollectiblesResponse**](UserCollectiblesResponse.md) |  | [optional] [default to undefined]
**primary_guild** | [**UserPrimaryGuildResponse**](UserPrimaryGuildResponse.md) |  | [optional] [default to undefined]
**premium_type** | **number** |  | [optional] [default to undefined]
**email** | **string** |  | [optional] [default to undefined]
**verified** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { UserPIIResponse } from 'dc_rest';

const instance: UserPIIResponse = {
    id,
    username,
    discriminator,
    public_flags,
    flags,
    mfa_enabled,
    locale,
    avatar,
    bot,
    system,
    banner,
    accent_color,
    global_name,
    avatar_decoration_data,
    collectibles,
    primary_guild,
    premium_type,
    email,
    verified,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
