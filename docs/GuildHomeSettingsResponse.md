# GuildHomeSettingsResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**guild_id** | **string** |  | [default to undefined]
**enabled** | **boolean** |  | [default to undefined]
**new_member_actions** | [**Array&lt;GuildHomeSettingsResponseNewMemberActionsInner&gt;**](GuildHomeSettingsResponseNewMemberActionsInner.md) |  | [default to undefined]
**resource_channels** | [**Array&lt;GuildHomeSettingsResponseResourceChannelsInner&gt;**](GuildHomeSettingsResponseResourceChannelsInner.md) |  | [default to undefined]
**welcome_message** | [**WelcomeMessageResponse**](WelcomeMessageResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { GuildHomeSettingsResponse } from 'dc_rest';

const instance: GuildHomeSettingsResponse = {
    guild_id,
    enabled,
    new_member_actions,
    resource_channels,
    welcome_message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
