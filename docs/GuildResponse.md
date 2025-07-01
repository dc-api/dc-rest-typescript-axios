# GuildResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**features** | **Set&lt;string&gt;** |  | [default to undefined]
**owner_id** | **string** |  | [default to undefined]
**region** | **string** |  | [default to undefined]
**afk_timeout** | **number** |  | [default to undefined]
**system_channel_flags** | **number** |  | [default to undefined]
**widget_enabled** | **boolean** |  | [default to undefined]
**verification_level** | **number** |  | [default to undefined]
**roles** | [**Array&lt;GuildRoleResponse&gt;**](GuildRoleResponse.md) |  | [default to undefined]
**default_message_notifications** | **number** |  | [default to undefined]
**mfa_level** | **number** |  | [default to undefined]
**explicit_content_filter** | **number** |  | [default to undefined]
**premium_tier** | **number** |  | [default to undefined]
**premium_subscription_count** | **number** |  | [default to undefined]
**preferred_locale** | **string** |  | [default to undefined]
**premium_progress_bar_enabled** | **boolean** |  | [default to undefined]
**nsfw** | **boolean** |  | [default to undefined]
**nsfw_level** | **number** |  | [default to undefined]
**emojis** | [**Array&lt;EmojiResponse&gt;**](EmojiResponse.md) |  | [default to undefined]
**stickers** | [**Array&lt;GuildStickerResponse&gt;**](GuildStickerResponse.md) |  | [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**home_header** | **string** |  | [optional] [default to undefined]
**splash** | **string** |  | [optional] [default to undefined]
**discovery_splash** | **string** |  | [optional] [default to undefined]
**banner** | **string** |  | [optional] [default to undefined]
**application_id** | **string** |  | [optional] [default to undefined]
**afk_channel_id** | **string** |  | [optional] [default to undefined]
**system_channel_id** | **string** |  | [optional] [default to undefined]
**widget_channel_id** | **string** |  | [optional] [default to undefined]
**max_presences** | **number** |  | [optional] [default to undefined]
**max_members** | **number** |  | [optional] [default to undefined]
**max_stage_video_channel_users** | **number** |  | [optional] [default to undefined]
**max_video_channel_users** | **number** |  | [optional] [default to undefined]
**vanity_url_code** | **string** |  | [optional] [default to undefined]
**rules_channel_id** | **string** |  | [optional] [default to undefined]
**safety_alerts_channel_id** | **string** |  | [optional] [default to undefined]
**public_updates_channel_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildResponse } from 'dc_rest';

const instance: GuildResponse = {
    id,
    name,
    features,
    owner_id,
    region,
    afk_timeout,
    system_channel_flags,
    widget_enabled,
    verification_level,
    roles,
    default_message_notifications,
    mfa_level,
    explicit_content_filter,
    premium_tier,
    premium_subscription_count,
    preferred_locale,
    premium_progress_bar_enabled,
    nsfw,
    nsfw_level,
    emojis,
    stickers,
    icon,
    description,
    home_header,
    splash,
    discovery_splash,
    banner,
    application_id,
    afk_channel_id,
    system_channel_id,
    widget_channel_id,
    max_presences,
    max_members,
    max_stage_video_channel_users,
    max_video_channel_users,
    vanity_url_code,
    rules_channel_id,
    safety_alerts_channel_id,
    public_updates_channel_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
