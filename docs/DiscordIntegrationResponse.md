# DiscordIntegrationResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**IntegrationTypes**](IntegrationTypes.md) |  | [default to undefined]
**account** | [**AccountResponse**](AccountResponse.md) |  | [default to undefined]
**enabled** | **boolean** |  | [default to undefined]
**id** | **string** |  | [default to undefined]
**application** | [**IntegrationApplicationResponse**](IntegrationApplicationResponse.md) |  | [default to undefined]
**scopes** | [**Set&lt;OAuth2Scopes&gt;**](OAuth2Scopes.md) |  | [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**user** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { DiscordIntegrationResponse } from 'dc_rest';

const instance: DiscordIntegrationResponse = {
    type,
    account,
    enabled,
    id,
    application,
    scopes,
    name,
    user,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
