# GuildIncomingWebhookResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**application_id** | **string** |  | [optional] [default to undefined]
**avatar** | **string** |  | [optional] [default to undefined]
**channel_id** | **string** |  | [optional] [default to undefined]
**guild_id** | **string** |  | [optional] [default to undefined]
**user** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**token** | **string** |  | [optional] [default to undefined]
**url** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildIncomingWebhookResponse } from 'dc_rest';

const instance: GuildIncomingWebhookResponse = {
    id,
    name,
    type,
    application_id,
    avatar,
    channel_id,
    guild_id,
    user,
    token,
    url,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
