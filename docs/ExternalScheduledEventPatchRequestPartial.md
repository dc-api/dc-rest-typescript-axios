# ExternalScheduledEventPatchRequestPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **number** |  | [optional] [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**image** | **string** |  | [optional] [default to undefined]
**scheduled_start_time** | **string** |  | [optional] [default to undefined]
**scheduled_end_time** | **string** |  | [optional] [default to undefined]
**entity_type** | **number** |  | [optional] [default to undefined]
**privacy_level** | **any** |  | [optional] [default to undefined]
**channel_id** | **string** |  | [optional] [default to undefined]
**entity_metadata** | [**EntityMetadataExternal**](EntityMetadataExternal.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ExternalScheduledEventPatchRequestPartial } from 'dc_rest';

const instance: ExternalScheduledEventPatchRequestPartial = {
    status,
    name,
    description,
    image,
    scheduled_start_time,
    scheduled_end_time,
    entity_type,
    privacy_level,
    channel_id,
    entity_metadata,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
