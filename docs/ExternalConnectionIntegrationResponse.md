# ExternalConnectionIntegrationResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** |  | [default to undefined]
**id** | **string** |  | [default to undefined]
**user** | [**UserResponse**](UserResponse.md) |  | [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**account** | [**AccountResponse**](AccountResponse.md) |  | [optional] [default to undefined]
**enabled** | **boolean** |  | [optional] [default to undefined]
**revoked** | **boolean** |  | [optional] [default to undefined]
**expire_behavior** | **number** |  | [optional] [default to undefined]
**expire_grace_period** | **number** |  | [optional] [default to undefined]
**subscriber_count** | **number** |  | [optional] [default to undefined]
**synced_at** | **string** |  | [optional] [default to undefined]
**role_id** | **string** |  | [optional] [default to undefined]
**syncing** | **boolean** |  | [optional] [default to undefined]
**enable_emoticons** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { ExternalConnectionIntegrationResponse } from 'dc_rest';

const instance: ExternalConnectionIntegrationResponse = {
    type,
    id,
    user,
    name,
    account,
    enabled,
    revoked,
    expire_behavior,
    expire_grace_period,
    subscriber_count,
    synced_at,
    role_id,
    syncing,
    enable_emoticons,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
