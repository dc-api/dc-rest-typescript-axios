# CreateLobbyRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**idle_timeout_seconds** | **number** |  | [optional] [default to undefined]
**members** | [**Array&lt;LobbyMemberRequest&gt;**](LobbyMemberRequest.md) |  | [optional] [default to undefined]
**metadata** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**flags** | [**CreateOrJoinLobbyRequestFlags**](CreateOrJoinLobbyRequestFlags.md) |  | [optional] [default to undefined]
**override_event_webhooks_url** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateLobbyRequest } from 'dc_rest';

const instance: CreateLobbyRequest = {
    idle_timeout_seconds,
    members,
    metadata,
    flags,
    override_event_webhooks_url,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
