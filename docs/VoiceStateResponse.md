# VoiceStateResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**deaf** | **boolean** |  | [default to undefined]
**mute** | **boolean** |  | [default to undefined]
**suppress** | **boolean** |  | [default to undefined]
**self_deaf** | **boolean** |  | [default to undefined]
**self_mute** | **boolean** |  | [default to undefined]
**self_video** | **boolean** |  | [default to undefined]
**session_id** | **string** |  | [default to undefined]
**user_id** | **string** |  | [default to undefined]
**channel_id** | **string** |  | [optional] [default to undefined]
**guild_id** | **string** |  | [optional] [default to undefined]
**member** | [**GuildMemberResponse**](GuildMemberResponse.md) |  | [optional] [default to undefined]
**request_to_speak_timestamp** | **string** |  | [optional] [default to undefined]
**self_stream** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { VoiceStateResponse } from 'dc_rest';

const instance: VoiceStateResponse = {
    deaf,
    mute,
    suppress,
    self_deaf,
    self_mute,
    self_video,
    session_id,
    user_id,
    channel_id,
    guild_id,
    member,
    request_to_speak_timestamp,
    self_stream,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
