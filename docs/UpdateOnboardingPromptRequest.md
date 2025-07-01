# UpdateOnboardingPromptRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **string** |  | [default to undefined]
**_options** | [**Array&lt;OnboardingPromptOptionRequest&gt;**](OnboardingPromptOptionRequest.md) |  | [default to undefined]
**id** | **string** |  | [default to undefined]
**single_select** | **boolean** |  | [optional] [default to undefined]
**required** | **boolean** |  | [optional] [default to undefined]
**in_onboarding** | **boolean** |  | [optional] [default to undefined]
**type** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { UpdateOnboardingPromptRequest } from 'dc_rest';

const instance: UpdateOnboardingPromptRequest = {
    title,
    _options,
    id,
    single_select,
    required,
    in_onboarding,
    type,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
