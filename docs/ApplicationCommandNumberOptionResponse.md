# ApplicationCommandNumberOptionResponse


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
**choices** | [**Array&lt;ApplicationCommandOptionNumberChoiceResponse&gt;**](ApplicationCommandOptionNumberChoiceResponse.md) |  | [optional] [default to undefined]
**min_value** | **number** |  | [optional] [default to undefined]
**max_value** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationCommandNumberOptionResponse } from 'dc_rest';

const instance: ApplicationCommandNumberOptionResponse = {
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
    min_value,
    max_value,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
