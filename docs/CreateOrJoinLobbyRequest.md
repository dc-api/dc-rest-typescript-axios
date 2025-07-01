# CreateOrJoinLobbyRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**secret** | **string** |  | [default to undefined]
**idle_timeout_seconds** | **number** |  | [optional] [default to undefined]
**lobby_metadata** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**member_metadata** | **{ [key: string]: string; }** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateOrJoinLobbyRequest } from 'dc_rest';

const instance: CreateOrJoinLobbyRequest = {
    secret,
    idle_timeout_seconds,
    lobby_metadata,
    member_metadata,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
