# WidgetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**channels** | [**Array&lt;WidgetChannel&gt;**](WidgetChannel.md) |  | [default to undefined]
**members** | [**Array&lt;WidgetMember&gt;**](WidgetMember.md) |  | [default to undefined]
**presence_count** | **number** |  | [default to undefined]
**instant_invite** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { WidgetResponse } from 'dc_rest';

const instance: WidgetResponse = {
    id,
    name,
    channels,
    members,
    presence_count,
    instant_invite,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
