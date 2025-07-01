# MLSpamUpsertRequestPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [optional] [default to undefined]
**event_type** | **number** |  | [optional] [default to undefined]
**actions** | [**Array&lt;DefaultKeywordListUpsertRequestActionsInner&gt;**](DefaultKeywordListUpsertRequestActionsInner.md) |  | [optional] [default to undefined]
**enabled** | **boolean** |  | [optional] [default to undefined]
**exempt_roles** | **Set&lt;string&gt;** |  | [optional] [default to undefined]
**exempt_channels** | **Set&lt;string&gt;** |  | [optional] [default to undefined]
**trigger_type** | **number** |  | [optional] [default to undefined]
**trigger_metadata** | **object** |  | [optional] [default to undefined]

## Example

```typescript
import { MLSpamUpsertRequestPartial } from 'dc_rest';

const instance: MLSpamUpsertRequestPartial = {
    name,
    event_type,
    actions,
    enabled,
    exempt_roles,
    exempt_channels,
    trigger_type,
    trigger_metadata,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
