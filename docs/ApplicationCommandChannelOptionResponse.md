# ApplicationCommandChannelOptionResponse


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
**channel_types** | **Set&lt;number&gt;** |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationCommandChannelOptionResponse } from 'dc_rest';

const instance: ApplicationCommandChannelOptionResponse = {
    type,
    name,
    description,
    name_localized,
    name_localizations,
    description_localized,
    description_localizations,
    required,
    channel_types,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
