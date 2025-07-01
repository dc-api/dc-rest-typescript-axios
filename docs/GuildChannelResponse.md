# GuildChannelResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**guild_id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**position** | **number** |  | [default to undefined]
**last_message_id** | **string** |  | [optional] [default to undefined]
**last_pin_timestamp** | **string** |  | [optional] [default to undefined]
**parent_id** | **string** |  | [optional] [default to undefined]
**rate_limit_per_user** | **number** |  | [optional] [default to undefined]
**bitrate** | **number** |  | [optional] [default to undefined]
**user_limit** | **number** |  | [optional] [default to undefined]
**rtc_region** | **string** |  | [optional] [default to undefined]
**video_quality_mode** | **number** |  | [optional] [default to undefined]
**permissions** | **string** |  | [optional] [default to undefined]
**topic** | **string** |  | [optional] [default to undefined]
**default_auto_archive_duration** | **number** |  | [optional] [default to undefined]
**default_thread_rate_limit_per_user** | **number** |  | [optional] [default to undefined]
**permission_overwrites** | [**Array&lt;ChannelPermissionOverwriteResponse&gt;**](ChannelPermissionOverwriteResponse.md) |  | [optional] [default to undefined]
**nsfw** | **boolean** |  | [optional] [default to undefined]
**available_tags** | [**Array&lt;ForumTagResponse&gt;**](ForumTagResponse.md) |  | [optional] [default to undefined]
**default_reaction_emoji** | [**DefaultReactionEmojiResponse**](DefaultReactionEmojiResponse.md) |  | [optional] [default to undefined]
**default_sort_order** | **number** |  | [optional] [default to undefined]
**default_forum_layout** | **number** |  | [optional] [default to undefined]
**default_tag_setting** | **string** |  | [optional] [default to undefined]
**hd_streaming_until** | **string** |  | [optional] [default to undefined]
**hd_streaming_buyer_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildChannelResponse } from 'dc_rest';

const instance: GuildChannelResponse = {
    id,
    type,
    flags,
    guild_id,
    name,
    position,
    last_message_id,
    last_pin_timestamp,
    parent_id,
    rate_limit_per_user,
    bitrate,
    user_limit,
    rtc_region,
    video_quality_mode,
    permissions,
    topic,
    default_auto_archive_duration,
    default_thread_rate_limit_per_user,
    permission_overwrites,
    nsfw,
    available_tags,
    default_reaction_emoji,
    default_sort_order,
    default_forum_layout,
    default_tag_setting,
    hd_streaming_until,
    hd_streaming_buyer_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
