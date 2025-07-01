# LobbyMessageResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**content** | **string** |  | [default to undefined]
**lobby_id** | **string** |  | [default to undefined]
**channel_id** | **string** |  | [default to undefined]
**author** | [**UserResponse**](UserResponse.md) |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**metadata** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**application_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { LobbyMessageResponse } from 'dc_rest';

const instance: LobbyMessageResponse = {
    id,
    type,
    content,
    lobby_id,
    channel_id,
    author,
    flags,
    metadata,
    application_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
