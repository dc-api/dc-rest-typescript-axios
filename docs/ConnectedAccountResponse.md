# ConnectedAccountResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**type** | **string** |  | [default to undefined]
**friend_sync** | **boolean** |  | [default to undefined]
**show_activity** | **boolean** |  | [default to undefined]
**two_way_link** | **boolean** |  | [default to undefined]
**verified** | **boolean** |  | [default to undefined]
**visibility** | **number** |  | [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**integrations** | [**Array&lt;ConnectedAccountIntegrationResponse&gt;**](ConnectedAccountIntegrationResponse.md) |  | [optional] [default to undefined]
**revoked** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { ConnectedAccountResponse } from 'dc_rest';

const instance: ConnectedAccountResponse = {
    id,
    type,
    friend_sync,
    show_activity,
    two_way_link,
    verified,
    visibility,
    name,
    integrations,
    revoked,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
