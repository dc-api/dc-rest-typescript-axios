# UpdateGuildOnboardingRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prompts** | [**Array&lt;UpdateOnboardingPromptRequest&gt;**](UpdateOnboardingPromptRequest.md) |  | [optional] [default to undefined]
**enabled** | **boolean** |  | [optional] [default to undefined]
**default_channel_ids** | **Set&lt;string&gt;** |  | [optional] [default to undefined]
**mode** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { UpdateGuildOnboardingRequest } from 'dc_rest';

const instance: UpdateGuildOnboardingRequest = {
    prompts,
    enabled,
    default_channel_ids,
    mode,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
