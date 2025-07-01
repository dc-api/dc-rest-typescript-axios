# ProvisionalTokenResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**token_type** | **string** |  | [default to undefined]
**access_token** | **string** |  | [default to undefined]
**expires_in** | **number** |  | [default to undefined]
**scope** | **string** |  | [default to undefined]
**id_token** | **string** |  | [default to undefined]
**refresh_token** | **string** |  | [optional] [default to undefined]
**scopes** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**expires_at_s** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { ProvisionalTokenResponse } from 'dc_rest';

const instance: ProvisionalTokenResponse = {
    token_type,
    access_token,
    expires_in,
    scope,
    id_token,
    refresh_token,
    scopes,
    expires_at_s,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
