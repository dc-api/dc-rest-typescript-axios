# GuildPatchRequestPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**region** | **string** |  | [optional] [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**verification_level** | **number** |  | [optional] [default to undefined]
**default_message_notifications** | **number** |  | [optional] [default to undefined]
**explicit_content_filter** | **number** |  | [optional] [default to undefined]
**preferred_locale** | **string** |  | [optional] [default to undefined]
**afk_timeout** | **number** |  | [optional] [default to undefined]
**afk_channel_id** | **string** |  | [optional] [default to undefined]
**system_channel_id** | **string** |  | [optional] [default to undefined]
**owner_id** | **string** |  | [optional] [default to undefined]
**splash** | **string** |  | [optional] [default to undefined]
**banner** | **string** |  | [optional] [default to undefined]
**system_channel_flags** | **number** |  | [optional] [default to undefined]
**features** | **Set&lt;string | null&gt;** |  | [optional] [default to undefined]
**discovery_splash** | **string** |  | [optional] [default to undefined]
**home_header** | **string** |  | [optional] [default to undefined]
**rules_channel_id** | **string** |  | [optional] [default to undefined]
**safety_alerts_channel_id** | **string** |  | [optional] [default to undefined]
**public_updates_channel_id** | **string** |  | [optional] [default to undefined]
**premium_progress_bar_enabled** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildPatchRequestPartial } from 'dc_rest';

const instance: GuildPatchRequestPartial = {
    name,
    description,
    region,
    icon,
    verification_level,
    default_message_notifications,
    explicit_content_filter,
    preferred_locale,
    afk_timeout,
    afk_channel_id,
    system_channel_id,
    owner_id,
    splash,
    banner,
    system_channel_flags,
    features,
    discovery_splash,
    home_header,
    rules_channel_id,
    safety_alerts_channel_id,
    public_updates_channel_id,
    premium_progress_bar_enabled,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
