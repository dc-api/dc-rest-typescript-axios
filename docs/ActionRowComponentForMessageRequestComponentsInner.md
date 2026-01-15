# ActionRowComponentForMessageRequestComponentsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**MessageComponentTypes**](MessageComponentTypes.md) |  | [default to undefined]
**custom_id** | **string** |  | [default to undefined]
**style** | [**ButtonStyleTypes**](ButtonStyleTypes.md) |  | [default to undefined]
**_options** | [**Array&lt;StringSelectOptionForRequest&gt;**](StringSelectOptionForRequest.md) |  | [default to undefined]
**id** | **number** |  | [optional] [default to undefined]
**label** | **string** |  | [optional] [default to undefined]
**disabled** | **boolean** |  | [optional] [default to undefined]
**url** | **string** |  | [optional] [default to undefined]
**sku_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**emoji** | [**ButtonComponentForMessageRequestEmoji**](ButtonComponentForMessageRequestEmoji.md) |  | [optional] [default to undefined]
**placeholder** | **string** |  | [optional] [default to undefined]
**min_values** | **number** |  | [optional] [default to undefined]
**max_values** | **number** |  | [optional] [default to undefined]
**required** | **boolean** |  | [optional] [default to undefined]
**default_values** | [**Array&lt;UserSelectDefaultValue&gt;**](UserSelectDefaultValue.md) |  | [optional] [default to undefined]
**channel_types** | [**Set&lt;ChannelTypes&gt;**](ChannelTypes.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ActionRowComponentForMessageRequestComponentsInner } from 'dc_rest';

const instance: ActionRowComponentForMessageRequestComponentsInner = {
    type,
    custom_id,
    style,
    _options,
    id,
    label,
    disabled,
    url,
    sku_id,
    emoji,
    placeholder,
    min_values,
    max_values,
    required,
    default_values,
    channel_types,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
