# GuildCreateRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**region** | **string** |  | [optional] [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**verification_level** | **number** |  | [optional] [default to undefined]
**default_message_notifications** | **number** |  | [optional] [default to undefined]
**explicit_content_filter** | **number** |  | [optional] [default to undefined]
**preferred_locale** | **string** |  | [optional] [default to undefined]
**afk_timeout** | **number** |  | [optional] [default to undefined]
**roles** | [**Array&lt;CreateGuildRequestRoleItem&gt;**](CreateGuildRequestRoleItem.md) |  | [optional] [default to undefined]
**channels** | [**Array&lt;CreateGuildRequestChannelItem&gt;**](CreateGuildRequestChannelItem.md) |  | [optional] [default to undefined]
**afk_channel_id** | **string** |  | [optional] [default to undefined]
**system_channel_id** | **string** |  | [optional] [default to undefined]
**system_channel_flags** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildCreateRequest } from 'dc_rest';

const instance: GuildCreateRequest = {
    name,
    description,
    region,
    icon,
    verification_level,
    default_message_notifications,
    explicit_content_filter,
    preferred_locale,
    afk_timeout,
    roles,
    channels,
    afk_channel_id,
    system_channel_id,
    system_channel_flags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
