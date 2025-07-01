# GuildHomeSettingsResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**guild_id** | **string** |  | [default to undefined]
**enabled** | **boolean** |  | [default to undefined]
**welcome_message** | [**WelcomeMessageResponse**](WelcomeMessageResponse.md) |  | [optional] [default to undefined]
**new_member_actions** | [**Array&lt;NewMemberActionResponse | null&gt;**](NewMemberActionResponse.md) |  | [optional] [default to undefined]
**resource_channels** | [**Array&lt;ResourceChannelResponse | null&gt;**](ResourceChannelResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { GuildHomeSettingsResponse } from 'dc_rest';

const instance: GuildHomeSettingsResponse = {
    guild_id,
    enabled,
    welcome_message,
    new_member_actions,
    resource_channels,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
