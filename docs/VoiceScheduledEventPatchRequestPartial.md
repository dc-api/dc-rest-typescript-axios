# VoiceScheduledEventPatchRequestPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | [**ExternalScheduledEventPatchRequestPartialStatus**](ExternalScheduledEventPatchRequestPartialStatus.md) |  | [optional] [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**image** | **string** |  | [optional] [default to undefined]
**scheduled_start_time** | **string** |  | [optional] [default to undefined]
**scheduled_end_time** | **string** |  | [optional] [default to undefined]
**entity_type** | [**VoiceScheduledEventPatchRequestPartialEntityType**](VoiceScheduledEventPatchRequestPartialEntityType.md) |  | [optional] [default to undefined]
**privacy_level** | [**GuildScheduledEventPrivacyLevels**](GuildScheduledEventPrivacyLevels.md) |  | [optional] [default to undefined]
**channel_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**entity_metadata** | [**VoiceScheduledEventCreateRequestEntityMetadata**](VoiceScheduledEventCreateRequestEntityMetadata.md) |  | [optional] [default to undefined]

## Example

```typescript
import { VoiceScheduledEventPatchRequestPartial } from 'dc_rest';

const instance: VoiceScheduledEventPatchRequestPartial = {
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
