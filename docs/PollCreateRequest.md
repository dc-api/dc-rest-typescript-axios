# PollCreateRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | [**PollMedia**](PollMedia.md) |  | [default to undefined]
**answers** | [**Array&lt;PollAnswerCreateRequest&gt;**](PollAnswerCreateRequest.md) |  | [default to undefined]
**allow_multiselect** | **boolean** |  | [optional] [default to undefined]
**layout_type** | **number** |  | [optional] [default to undefined]
**duration** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { PollCreateRequest } from 'dc_rest';

const instance: PollCreateRequest = {
    question,
    answers,
    allow_multiselect,
    layout_type,
    duration,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
