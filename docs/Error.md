# ModelError

A single error, either for an API response or a specific field.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **number** | Discord internal error code. See error code reference | [default to undefined]
**message** | **string** | Human-readable error message | [default to undefined]

## Example

```typescript
import { ModelError } from 'dc_rest';

const instance: ModelError = {
    code,
    message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
