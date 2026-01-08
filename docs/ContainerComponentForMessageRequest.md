# ContainerComponentForMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**MessageComponentTypes**](MessageComponentTypes.md) |  | [default to undefined]
**components** | [**Array&lt;ContainerComponentForMessageRequestComponentsInner&gt;**](ContainerComponentForMessageRequestComponentsInner.md) |  | [default to undefined]
**id** | **number** |  | [optional] [default to undefined]
**accent_color** | **number** |  | [optional] [default to undefined]
**spoiler** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { ContainerComponentForMessageRequest } from 'dc_rest';

const instance: ContainerComponentForMessageRequest = {
    type,
    components,
    id,
    accent_color,
    spoiler,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
