# ApplicationCommandIntegerOption


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**ApplicationCommandOptionType**](ApplicationCommandOptionType.md) |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**description** | **string** |  | [default to undefined]
**name_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**description_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**required** | **boolean** |  | [optional] [default to undefined]
**autocomplete** | **boolean** |  | [optional] [default to undefined]
**choices** | [**Array&lt;ApplicationCommandOptionIntegerChoice&gt;**](ApplicationCommandOptionIntegerChoice.md) |  | [optional] [default to undefined]
**min_value** | [**ApplicationCommandIntegerOptionMinValue**](ApplicationCommandIntegerOptionMinValue.md) |  | [optional] [default to undefined]
**max_value** | [**ApplicationCommandIntegerOptionMinValue**](ApplicationCommandIntegerOptionMinValue.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationCommandIntegerOption } from 'dc_rest';

const instance: ApplicationCommandIntegerOption = {
    type,
    name,
    description,
    name_localizations,
    description_localizations,
    required,
    autocomplete,
    choices,
    min_value,
    max_value,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
