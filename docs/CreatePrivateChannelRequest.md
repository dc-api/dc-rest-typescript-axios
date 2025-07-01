# CreatePrivateChannelRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**recipient_id** | **string** |  | [optional] [default to undefined]
**access_tokens** | **Set&lt;string&gt;** |  | [optional] [default to undefined]
**nicks** | **{ [key: string]: string | null; }** |  | [optional] [default to undefined]

## Example

```typescript
import { CreatePrivateChannelRequest } from 'dc_rest';

const instance: CreatePrivateChannelRequest = {
    recipient_id,
    access_tokens,
    nicks,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
