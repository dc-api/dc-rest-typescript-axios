# ChannelSelectComponentForMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **number** |  | [default to undefined]
**custom_id** | **string** |  | [default to undefined]
**placeholder** | **string** |  | [optional] [default to undefined]
**min_values** | **number** |  | [optional] [default to undefined]
**max_values** | **number** |  | [optional] [default to undefined]
**disabled** | **boolean** |  | [optional] [default to undefined]
**default_values** | [**Array&lt;ChannelSelectDefaultValue&gt;**](ChannelSelectDefaultValue.md) |  | [optional] [default to undefined]
**channel_types** | **Set&lt;number&gt;** |  | [optional] [default to undefined]

## Example

```typescript
import { ChannelSelectComponentForMessageRequest } from 'dc_rest';

const instance: ChannelSelectComponentForMessageRequest = {
    type,
    custom_id,
    placeholder,
    min_values,
    max_values,
    disabled,
    default_values,
    channel_types,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
