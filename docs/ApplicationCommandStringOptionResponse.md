# ApplicationCommandStringOptionResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **number** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**description** | **string** |  | [default to undefined]
**name_localized** | **string** |  | [optional] [default to undefined]
**name_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**description_localized** | **string** |  | [optional] [default to undefined]
**description_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**required** | **boolean** |  | [optional] [default to undefined]
**autocomplete** | **boolean** |  | [optional] [default to undefined]
**choices** | [**Array&lt;ApplicationCommandOptionStringChoiceResponse&gt;**](ApplicationCommandOptionStringChoiceResponse.md) |  | [optional] [default to undefined]
**min_length** | **number** |  | [optional] [default to undefined]
**max_length** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationCommandStringOptionResponse } from 'dc_rest';

const instance: ApplicationCommandStringOptionResponse = {
    type,
    name,
    description,
    name_localized,
    name_localizations,
    description_localized,
    description_localizations,
    required,
    autocomplete,
    choices,
    min_length,
    max_length,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
