# StringSelectComponentForMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**MessageComponentTypes**](MessageComponentTypes.md) |  | [default to undefined]
**custom_id** | **string** |  | [default to undefined]
**_options** | [**Array&lt;StringSelectOptionForRequest&gt;**](StringSelectOptionForRequest.md) |  | [default to undefined]
**id** | **number** |  | [optional] [default to undefined]
**placeholder** | **string** |  | [optional] [default to undefined]
**min_values** | **number** |  | [optional] [default to undefined]
**max_values** | **number** |  | [optional] [default to undefined]
**disabled** | **boolean** |  | [optional] [default to undefined]
**required** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { StringSelectComponentForMessageRequest } from 'dc_rest';

const instance: StringSelectComponentForMessageRequest = {
    type,
    custom_id,
    _options,
    id,
    placeholder,
    min_values,
    max_values,
    disabled,
    required,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
