# GetChannel200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**guild_id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**position** | **number** |  | [default to undefined]
**recipients** | [**Array&lt;UserResponse&gt;**](UserResponse.md) |  | [default to undefined]
**owner_id** | **string** |  | [default to undefined]
**message_count** | **number** |  | [default to undefined]
**member_count** | **number** |  | [default to undefined]
**total_message_sent** | **number** |  | [default to undefined]
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
**icon** | **string** |  | [optional] [default to undefined]
**managed** | **boolean** |  | [optional] [default to undefined]
**application_id** | **string** |  | [optional] [default to undefined]
**thread_metadata** | [**ThreadMetadataResponse**](ThreadMetadataResponse.md) |  | [optional] [default to undefined]
**applied_tags** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**member** | [**ThreadMemberResponse**](ThreadMemberResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { GetChannel200Response } from 'dc_rest';

const instance: GetChannel200Response = {
    id,
    type,
    flags,
    guild_id,
    name,
    position,
    recipients,
    owner_id,
    message_count,
    member_count,
    total_message_sent,
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
    icon,
    managed,
    application_id,
    thread_metadata,
    applied_tags,
    member,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
