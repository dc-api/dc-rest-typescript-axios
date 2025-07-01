# DefaultKeywordListUpsertRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [default to undefined]
**event_type** | **number** |  | [default to undefined]
**trigger_type** | **number** |  | [default to undefined]
**trigger_metadata** | [**DefaultKeywordListTriggerMetadata**](DefaultKeywordListTriggerMetadata.md) |  | [default to undefined]
**actions** | [**Array&lt;DefaultKeywordListUpsertRequestActionsInner&gt;**](DefaultKeywordListUpsertRequestActionsInner.md) |  | [optional] [default to undefined]
**enabled** | **boolean** |  | [optional] [default to undefined]
**exempt_roles** | **Set&lt;string&gt;** |  | [optional] [default to undefined]
**exempt_channels** | **Set&lt;string&gt;** |  | [optional] [default to undefined]

## Example

```typescript
import { DefaultKeywordListUpsertRequest } from 'dc_rest';

const instance: DefaultKeywordListUpsertRequest = {
    name,
    event_type,
    trigger_type,
    trigger_metadata,
    actions,
    enabled,
    exempt_roles,
    exempt_channels,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
