# BotAddGuildMemberRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**access_token** | **string** |  | [default to undefined]
**nick** | **string** |  | [optional] [default to undefined]
**roles** | **Set&lt;string&gt;** |  | [optional] [default to undefined]
**mute** | **boolean** |  | [optional] [default to undefined]
**deaf** | **boolean** |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { BotAddGuildMemberRequest } from 'dc_rest';

const instance: BotAddGuildMemberRequest = {
    access_token,
    nick,
    roles,
    mute,
    deaf,
    flags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
