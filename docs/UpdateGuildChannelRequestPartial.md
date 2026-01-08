# UpdateGuildChannelRequestPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**CreateGuildChannelRequestType**](CreateGuildChannelRequestType.md) |  | [optional] [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**position** | **number** |  | [optional] [default to undefined]
**topic** | **string** |  | [optional] [default to undefined]
**bitrate** | **number** |  | [optional] [default to undefined]
**user_limit** | **number** |  | [optional] [default to undefined]
**nsfw** | **boolean** |  | [optional] [default to undefined]
**rate_limit_per_user** | **number** |  | [optional] [default to undefined]
**parent_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**permission_overwrites** | [**Array&lt;ChannelPermissionOverwriteRequest&gt;**](ChannelPermissionOverwriteRequest.md) |  | [optional] [default to undefined]
**rtc_region** | **string** |  | [optional] [default to undefined]
**video_quality_mode** | [**CreateGuildChannelRequestVideoQualityMode**](CreateGuildChannelRequestVideoQualityMode.md) |  | [optional] [default to undefined]
**default_auto_archive_duration** | [**CreateForumThreadRequestAutoArchiveDuration**](CreateForumThreadRequestAutoArchiveDuration.md) |  | [optional] [default to undefined]
**default_reaction_emoji** | [**CreateGuildChannelRequestDefaultReactionEmoji**](CreateGuildChannelRequestDefaultReactionEmoji.md) |  | [optional] [default to undefined]
**default_thread_rate_limit_per_user** | **number** |  | [optional] [default to undefined]
**default_sort_order** | [**CreateGuildChannelRequestDefaultSortOrder**](CreateGuildChannelRequestDefaultSortOrder.md) |  | [optional] [default to undefined]
**default_forum_layout** | [**CreateGuildChannelRequestDefaultForumLayout**](CreateGuildChannelRequestDefaultForumLayout.md) |  | [optional] [default to undefined]
**default_tag_setting** | [**CreateGuildChannelRequestDefaultTagSetting**](CreateGuildChannelRequestDefaultTagSetting.md) |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]
**available_tags** | [**Array&lt;UpdateThreadTagRequest&gt;**](UpdateThreadTagRequest.md) |  | [optional] [default to undefined]

## Example

```typescript
import { UpdateGuildChannelRequestPartial } from 'dc_rest';

const instance: UpdateGuildChannelRequestPartial = {
    type,
    name,
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
    flags,
    available_tags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
