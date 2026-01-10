# MLSpamRuleResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**guild_id** | **string** |  | [default to undefined]
**creator_id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**event_type** | [**AutomodEventType**](AutomodEventType.md) |  | [default to undefined]
**actions** | [**Array&lt;DefaultKeywordRuleResponseActionsInner&gt;**](DefaultKeywordRuleResponseActionsInner.md) |  | [default to undefined]
**trigger_type** | [**AutomodTriggerType**](AutomodTriggerType.md) |  | [default to undefined]
**enabled** | **boolean** |  | [default to undefined]
**exempt_roles** | **Set&lt;string&gt;** |  | [default to undefined]
**exempt_channels** | **Set&lt;string&gt;** |  | [default to undefined]
**trigger_metadata** | **object** |  | [default to undefined]

## Example

```typescript
import { MLSpamRuleResponse } from 'dc_rest';

const instance: MLSpamRuleResponse = {
    id,
    guild_id,
    creator_id,
    name,
    event_type,
    actions,
    trigger_type,
    enabled,
    exempt_roles,
    exempt_channels,
    trigger_metadata,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
