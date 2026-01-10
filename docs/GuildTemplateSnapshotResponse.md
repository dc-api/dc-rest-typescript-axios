# GuildTemplateSnapshotResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [default to undefined]
**verification_level** | [**VerificationLevels**](VerificationLevels.md) |  | [default to undefined]
**default_message_notifications** | [**UserNotificationSettings**](UserNotificationSettings.md) |  | [default to undefined]
**explicit_content_filter** | [**GuildExplicitContentFilterTypes**](GuildExplicitContentFilterTypes.md) |  | [default to undefined]
**preferred_locale** | [**AvailableLocalesEnum**](AvailableLocalesEnum.md) |  | [default to undefined]
**afk_timeout** | [**AfkTimeouts**](AfkTimeouts.md) |  | [default to undefined]
**system_channel_flags** | **number** |  | [default to undefined]
**roles** | [**Array&lt;GuildTemplateRoleResponse&gt;**](GuildTemplateRoleResponse.md) |  | [default to undefined]
**channels** | [**Array&lt;GuildTemplateChannelResponse&gt;**](GuildTemplateChannelResponse.md) |  | [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**region** | **string** |  | [optional] [default to undefined]
**afk_channel_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**system_channel_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]

## Example

```typescript
import { GuildTemplateSnapshotResponse } from 'dc_rest';

const instance: GuildTemplateSnapshotResponse = {
    name,
    verification_level,
    default_message_notifications,
    explicit_content_filter,
    preferred_locale,
    afk_timeout,
    system_channel_flags,
    roles,
    channels,
    description,
    region,
    afk_channel_id,
    system_channel_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
