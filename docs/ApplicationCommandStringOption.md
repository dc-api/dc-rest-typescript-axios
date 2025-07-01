# ApplicationCommandStringOption


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **number** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**description** | **string** |  | [default to undefined]
**name_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**description_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**required** | **boolean** |  | [optional] [default to undefined]
**autocomplete** | **boolean** |  | [optional] [default to undefined]
**min_length** | **number** |  | [optional] [default to undefined]
**max_length** | **number** |  | [optional] [default to undefined]
**choices** | [**Array&lt;ApplicationCommandOptionStringChoice&gt;**](ApplicationCommandOptionStringChoice.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationCommandStringOption } from 'dc_rest';

const instance: ApplicationCommandStringOption = {
    type,
    name,
    description,
    name_localizations,
    description_localizations,
    required,
    autocomplete,
    min_length,
    max_length,
    choices,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
