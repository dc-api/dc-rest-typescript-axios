# GuildTemplateChannelResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **number** |  | [default to undefined]
**bitrate** | **number** |  | [default to undefined]
**user_limit** | **number** |  | [default to undefined]
**nsfw** | **boolean** |  | [default to undefined]
**rate_limit_per_user** | **number** |  | [default to undefined]
**permission_overwrites** | [**Array&lt;ChannelPermissionOverwriteResponse | null&gt;**](ChannelPermissionOverwriteResponse.md) |  | [default to undefined]
**template** | **string** |  | [default to undefined]
**id** | **number** |  | [optional] [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**position** | **number** |  | [optional] [default to undefined]
**topic** | **string** |  | [optional] [default to undefined]
**parent_id** | **string** |  | [optional] [default to undefined]
**default_auto_archive_duration** | **number** |  | [optional] [default to undefined]
**available_tags** | [**Array&lt;GuildTemplateChannelTags&gt;**](GuildTemplateChannelTags.md) |  | [optional] [default to undefined]
**default_reaction_emoji** | [**DefaultReactionEmojiResponse**](DefaultReactionEmojiResponse.md) |  | [optional] [default to undefined]
**default_thread_rate_limit_per_user** | **number** |  | [optional] [default to undefined]
**default_sort_order** | **number** |  | [optional] [default to undefined]
**default_forum_layout** | **number** |  | [optional] [default to undefined]
**default_tag_setting** | **string** |  | [optional] [default to undefined]
**icon_emoji** | **object** |  | [optional] [default to undefined]
**theme_color** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildTemplateChannelResponse } from 'dc_rest';

const instance: GuildTemplateChannelResponse = {
    type,
    bitrate,
    user_limit,
    nsfw,
    rate_limit_per_user,
    permission_overwrites,
    template,
    id,
    name,
    position,
    topic,
    parent_id,
    default_auto_archive_duration,
    available_tags,
    default_reaction_emoji,
    default_thread_rate_limit_per_user,
    default_sort_order,
    default_forum_layout,
    default_tag_setting,
    icon_emoji,
    theme_color,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
