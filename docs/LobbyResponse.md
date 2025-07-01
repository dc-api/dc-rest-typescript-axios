# LobbyResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**application_id** | **string** |  | [default to undefined]
**metadata** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**members** | [**Array&lt;LobbyMemberResponse&gt;**](LobbyMemberResponse.md) |  | [optional] [default to undefined]
**linked_channel** | [**GuildChannelResponse**](GuildChannelResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { LobbyResponse } from 'dc_rest';

const instance: LobbyResponse = {
    id,
    application_id,
    metadata,
    members,
    linked_channel,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
