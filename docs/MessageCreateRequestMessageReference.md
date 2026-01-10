# MessageCreateRequestMessageReference


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_id** | **string** |  | [default to undefined]
**guild_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**channel_id** | [**GetEntitlementsSkuIdsParameterOneOfInner**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**fail_if_not_exists** | **boolean** |  | [optional] [default to undefined]
**type** | [**MessageReferenceRequestType**](MessageReferenceRequestType.md) |  | [optional] [default to undefined]

## Example

```typescript
import { MessageCreateRequestMessageReference } from 'dc_rest';

const instance: MessageCreateRequestMessageReference = {
    message_id,
    guild_id,
    channel_id,
    fail_if_not_exists,
    type,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
