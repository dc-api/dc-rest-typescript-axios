# GuildHomeSettingsResponseNewMemberActionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**channel_id** | **string** |  | [default to undefined]
**action_type** | [**NewMemberActionType**](NewMemberActionType.md) |  | [default to undefined]
**title** | **string** |  | [default to undefined]
**description** | **string** |  | [default to undefined]
**emoji** | [**SettingsEmojiResponse**](SettingsEmojiResponse.md) |  | [optional] [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildHomeSettingsResponseNewMemberActionsInner } from 'dc_rest';

const instance: GuildHomeSettingsResponseNewMemberActionsInner = {
    channel_id,
    action_type,
    title,
    description,
    emoji,
    icon,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
