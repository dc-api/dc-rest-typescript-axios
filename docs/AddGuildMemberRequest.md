# AddGuildMemberRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**access_token** | **string** |  | [default to undefined]
**nick** | **string** |  | [optional] [default to undefined]
**roles** | **Set&lt;string | null&gt;** |  | [optional] [default to undefined]
**mute** | **boolean** |  | [optional] [default to undefined]
**deaf** | **boolean** |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { AddGuildMemberRequest } from 'dc_rest';

const instance: AddGuildMemberRequest = {
    access_token,
    nick,
    roles,
    mute,
    deaf,
    flags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
