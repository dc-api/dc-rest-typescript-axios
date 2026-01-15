# VoiceScheduledEventCreateRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [default to undefined]
**scheduled_start_time** | **string** |  | [default to undefined]
**privacy_level** | [**GuildScheduledEventPrivacyLevels**](GuildScheduledEventPrivacyLevels.md) |  | [default to undefined]
**entity_type** | [**GuildScheduledEventEntityTypes**](GuildScheduledEventEntityTypes.md) |  | [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**image** | **string** |  | [optional] [default to undefined]
**scheduled_end_time** | **string** |  | [optional] [default to undefined]
**channel_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**entity_metadata** | [**VoiceScheduledEventCreateRequestEntityMetadata**](VoiceScheduledEventCreateRequestEntityMetadata.md) |  | [optional] [default to undefined]

## Example

```typescript
import { VoiceScheduledEventCreateRequest } from 'dc_rest';

const instance: VoiceScheduledEventCreateRequest = {
    name,
    scheduled_start_time,
    privacy_level,
    entity_type,
    description,
    image,
    scheduled_end_time,
    channel_id,
    entity_metadata,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
