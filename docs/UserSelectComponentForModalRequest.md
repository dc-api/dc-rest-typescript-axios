# UserSelectComponentForModalRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**MessageComponentTypes**](MessageComponentTypes.md) |  | [default to undefined]
**custom_id** | **string** |  | [default to undefined]
**id** | **number** |  | [optional] [default to undefined]
**placeholder** | **string** |  | [optional] [default to undefined]
**min_values** | **number** |  | [optional] [default to undefined]
**max_values** | **number** |  | [optional] [default to undefined]
**disabled** | **boolean** |  | [optional] [default to undefined]
**required** | **boolean** |  | [optional] [default to undefined]
**default_values** | [**Array&lt;UserSelectDefaultValue&gt;**](UserSelectDefaultValue.md) |  | [optional] [default to undefined]

## Example

```typescript
import { UserSelectComponentForModalRequest } from 'dc_rest';

const instance: UserSelectComponentForModalRequest = {
    type,
    custom_id,
    id,
    placeholder,
    min_values,
    max_values,
    disabled,
    required,
    default_values,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
