# CreatedThreadResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**guild_id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
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
**thread_metadata** | [**ThreadMetadataResponse**](ThreadMetadataResponse.md) |  | [optional] [default to undefined]
**applied_tags** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**member** | [**ThreadMemberResponse**](ThreadMemberResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { CreatedThreadResponse } from 'dc_rest';

const instance: CreatedThreadResponse = {
    id,
    type,
    flags,
    guild_id,
    name,
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
    thread_metadata,
    applied_tags,
    member,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
