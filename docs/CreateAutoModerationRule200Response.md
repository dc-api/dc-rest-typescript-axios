# CreateAutoModerationRule200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**guild_id** | **string** |  | [default to undefined]
**creator_id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**event_type** | **number** |  | [default to undefined]
**actions** | [**Array&lt;DefaultKeywordRuleResponseActionsInner&gt;**](DefaultKeywordRuleResponseActionsInner.md) |  | [default to undefined]
**trigger_type** | **number** |  | [default to undefined]
**trigger_metadata** | **object** |  | [default to undefined]
**enabled** | **boolean** |  | [optional] [default to undefined]
**exempt_roles** | **Set&lt;string&gt;** |  | [optional] [default to undefined]
**exempt_channels** | **Set&lt;string&gt;** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateAutoModerationRule200Response } from 'dc_rest';

const instance: CreateAutoModerationRule200Response = {
    id,
    guild_id,
    creator_id,
    name,
    event_type,
    actions,
    trigger_type,
    trigger_metadata,
    enabled,
    exempt_roles,
    exempt_channels,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
