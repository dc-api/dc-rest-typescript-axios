# AuditLogEntryResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**action_type** | [**AuditLogActionTypes**](AuditLogActionTypes.md) |  | [default to undefined]
**user_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**target_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**changes** | [**Array&lt;AuditLogObjectChangeResponse&gt;**](AuditLogObjectChangeResponse.md) |  | [optional] [default to undefined]
**_options** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**reason** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { AuditLogEntryResponse } from 'dc_rest';

const instance: AuditLogEntryResponse = {
    id,
    action_type,
    user_id,
    target_id,
    changes,
    _options,
    reason,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
