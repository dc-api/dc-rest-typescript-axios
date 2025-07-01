# ThreadsResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**threads** | [**Array&lt;ThreadResponse&gt;**](ThreadResponse.md) |  | [default to undefined]
**members** | [**Array&lt;ThreadMemberResponse&gt;**](ThreadMemberResponse.md) |  | [default to undefined]
**has_more** | **boolean** |  | [optional] [default to undefined]
**first_messages** | [**Array&lt;MessageResponse&gt;**](MessageResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ThreadsResponse } from 'dc_rest';

const instance: ThreadsResponse = {
    threads,
    members,
    has_more,
    first_messages,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
