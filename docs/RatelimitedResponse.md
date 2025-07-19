# RatelimitedResponse

Ratelimit error object returned by the Discord API

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **number** | Discord internal error code. See error code reference | [default to undefined]
**message** | **string** | Human-readable error message | [default to undefined]
**retry_after** | **number** | The number of seconds to wait before retrying your request | [default to undefined]
**global** | **boolean** | Whether you are being ratelimited by the global ratelimit or a per-endpoint ratelimit | [default to undefined]

## Example

```typescript
import { RatelimitedResponse } from 'dc_rest';

const instance: RatelimitedResponse = {
    code,
    message,
    retry_after,
    global,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
