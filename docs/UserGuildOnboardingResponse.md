# UserGuildOnboardingResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**guild_id** | **string** |  | [default to undefined]
**prompts** | [**Array&lt;OnboardingPromptResponse&gt;**](OnboardingPromptResponse.md) |  | [default to undefined]
**default_channel_ids** | **Set&lt;string&gt;** |  | [default to undefined]
**enabled** | **boolean** |  | [default to undefined]

## Example

```typescript
import { UserGuildOnboardingResponse } from 'dc_rest';

const instance: UserGuildOnboardingResponse = {
    guild_id,
    prompts,
    default_channel_ids,
    enabled,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
