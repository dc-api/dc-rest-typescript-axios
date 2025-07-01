# UpdateGuildMemberRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nick** | **string** |  | [optional] [default to undefined]
**roles** | **Set&lt;string | null&gt;** |  | [optional] [default to undefined]
**mute** | **boolean** |  | [optional] [default to undefined]
**deaf** | **boolean** |  | [optional] [default to undefined]
**channel_id** | **string** |  | [optional] [default to undefined]
**communication_disabled_until** | **string** |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { UpdateGuildMemberRequest } from 'dc_rest';

const instance: UpdateGuildMemberRequest = {
    nick,
    roles,
    mute,
    deaf,
    channel_id,
    communication_disabled_until,
    flags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
