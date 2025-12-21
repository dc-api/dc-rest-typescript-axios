# ThreadSearchResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**threads** | [**Array&lt;ThreadResponse&gt;**](ThreadResponse.md) |  | [default to undefined]
**members** | [**Array&lt;ThreadMemberResponse&gt;**](ThreadMemberResponse.md) |  | [default to undefined]
**has_more** | **boolean** |  | [default to undefined]
**total_results** | **number** |  | [default to undefined]
**first_messages** | [**Array&lt;MessageResponse&gt;**](MessageResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ThreadSearchResponse } from 'dc_rest';

const instance: ThreadSearchResponse = {
    threads,
    members,
    has_more,
    total_results,
    first_messages,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
