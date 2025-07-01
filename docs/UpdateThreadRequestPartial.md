# UpdateThreadRequestPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [optional] [default to undefined]
**archived** | **boolean** |  | [optional] [default to undefined]
**locked** | **boolean** |  | [optional] [default to undefined]
**invitable** | **boolean** |  | [optional] [default to undefined]
**auto_archive_duration** | **number** |  | [optional] [default to undefined]
**rate_limit_per_user** | **number** |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]
**applied_tags** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**bitrate** | **number** |  | [optional] [default to undefined]
**user_limit** | **number** |  | [optional] [default to undefined]
**rtc_region** | **string** |  | [optional] [default to undefined]
**video_quality_mode** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { UpdateThreadRequestPartial } from 'dc_rest';

const instance: UpdateThreadRequestPartial = {
    name,
    archived,
    locked,
    invitable,
    auto_archive_duration,
    rate_limit_per_user,
    flags,
    applied_tags,
    bitrate,
    user_limit,
    rtc_region,
    video_quality_mode,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
