# PollResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | [**PollMediaResponse**](PollMediaResponse.md) |  | [default to undefined]
**answers** | [**Array&lt;PollAnswerResponse&gt;**](PollAnswerResponse.md) |  | [default to undefined]
**expiry** | **string** |  | [default to undefined]
**allow_multiselect** | **boolean** |  | [default to undefined]
**layout_type** | **number** |  | [default to undefined]
**results** | [**PollResultsResponse**](PollResultsResponse.md) |  | [default to undefined]

## Example

```typescript
import { PollResponse } from 'dc_rest';

const instance: PollResponse = {
    question,
    answers,
    expiry,
    allow_multiselect,
    layout_type,
    results,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
