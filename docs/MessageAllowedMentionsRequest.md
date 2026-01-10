# MessageAllowedMentionsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**parse** | [**Set&lt;MessageAllowedMentionsRequestParseInner&gt;**](MessageAllowedMentionsRequestParseInner.md) |  | [optional] [default to undefined]
**users** | [**Set&lt;GetEntitlementsSkuIdsParameterOneOfInner&gt;**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**roles** | [**Set&lt;GetEntitlementsSkuIdsParameterOneOfInner&gt;**](GetEntitlementsSkuIdsParameterOneOfInner.md) |  | [optional] [default to undefined]
**replied_user** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { MessageAllowedMentionsRequest } from 'dc_rest';

const instance: MessageAllowedMentionsRequest = {
    parse,
    users,
    roles,
    replied_user,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
