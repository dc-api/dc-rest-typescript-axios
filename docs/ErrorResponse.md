# ErrorResponse

Errors object returned by the Discord API

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **number** | Discord internal error code. See error code reference | [default to undefined]
**message** | **string** | Human-readable error message | [default to undefined]
**errors** | [**ErrorDetails**](ErrorDetails.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ErrorResponse } from 'dc_rest';

const instance: ErrorResponse = {
    code,
    message,
    errors,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
