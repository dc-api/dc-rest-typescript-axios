# CreateGuildChannelRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [default to undefined]
**type** | **number** |  | [optional] [default to undefined]
**position** | **number** |  | [optional] [default to undefined]
**topic** | **string** |  | [optional] [default to undefined]
**bitrate** | **number** |  | [optional] [default to undefined]
**user_limit** | **number** |  | [optional] [default to undefined]
**nsfw** | **boolean** |  | [optional] [default to undefined]
**rate_limit_per_user** | **number** |  | [optional] [default to undefined]
**parent_id** | **string** |  | [optional] [default to undefined]
**permission_overwrites** | [**Array&lt;ChannelPermissionOverwriteRequest&gt;**](ChannelPermissionOverwriteRequest.md) |  | [optional] [default to undefined]
**rtc_region** | **string** |  | [optional] [default to undefined]
**video_quality_mode** | **number** |  | [optional] [default to undefined]
**default_auto_archive_duration** | **number** |  | [optional] [default to undefined]
**default_reaction_emoji** | [**UpdateDefaultReactionEmojiRequest**](UpdateDefaultReactionEmojiRequest.md) |  | [optional] [default to undefined]
**default_thread_rate_limit_per_user** | **number** |  | [optional] [default to undefined]
**default_sort_order** | **number** |  | [optional] [default to undefined]
**default_forum_layout** | **number** |  | [optional] [default to undefined]
**default_tag_setting** | **string** |  | [optional] [default to undefined]
**available_tags** | [**Array&lt;CreateOrUpdateThreadTagRequest | null&gt;**](CreateOrUpdateThreadTagRequest.md) |  | [optional] [default to undefined]

## Example

```typescript
import { CreateGuildChannelRequest } from 'dc_rest';

const instance: CreateGuildChannelRequest = {
    name,
    type,
    position,
    topic,
    bitrate,
    user_limit,
    nsfw,
    rate_limit_per_user,
    parent_id,
    permission_overwrites,
    rtc_region,
    video_quality_mode,
    default_auto_archive_duration,
    default_reaction_emoji,
    default_thread_rate_limit_per_user,
    default_sort_order,
    default_forum_layout,
    default_tag_setting,
    available_tags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
