# DiscordIntegrationResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** |  | [default to undefined]
**id** | **string** |  | [default to undefined]
**application** | [**IntegrationApplicationResponse**](IntegrationApplicationResponse.md) |  | [default to undefined]
**scopes** | **Set&lt;string&gt;** |  | [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**account** | [**AccountResponse**](AccountResponse.md) |  | [optional] [default to undefined]
**enabled** | **boolean** |  | [optional] [default to undefined]
**user** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { DiscordIntegrationResponse } from 'dc_rest';

const instance: DiscordIntegrationResponse = {
    type,
    id,
    application,
    scopes,
    name,
    account,
    enabled,
    user,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
