# WidgetMember


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**username** | **string** |  | [default to undefined]
**discriminator** | **string** |  | [default to undefined]
**status** | **string** |  | [default to undefined]
**avatar_url** | **string** |  | [default to undefined]
**avatar** | **any** |  | [optional] [default to undefined]
**activity** | [**WidgetActivity**](WidgetActivity.md) |  | [optional] [default to undefined]
**deaf** | **boolean** |  | [optional] [default to undefined]
**mute** | **boolean** |  | [optional] [default to undefined]
**self_deaf** | **boolean** |  | [optional] [default to undefined]
**self_mute** | **boolean** |  | [optional] [default to undefined]
**suppress** | **boolean** |  | [optional] [default to undefined]
**channel_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { WidgetMember } from 'dc_rest';

const instance: WidgetMember = {
    id,
    username,
    discriminator,
    status,
    avatar_url,
    avatar,
    activity,
    deaf,
    mute,
    self_deaf,
    self_mute,
    suppress,
    channel_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
