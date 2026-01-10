# ApplicationCommandPatchRequestPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [optional] [default to undefined]
**name_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**description_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**_options** | [**Array&lt;ApplicationCommandCreateRequestOptionsInner&gt;**](ApplicationCommandCreateRequestOptionsInner.md) |  | [optional] [default to undefined]
**default_member_permissions** | **number** |  | [optional] [default to undefined]
**dm_permission** | **boolean** |  | [optional] [default to undefined]
**contexts** | [**Set&lt;InteractionContextType&gt;**](InteractionContextType.md) |  | [optional] [default to undefined]
**integration_types** | [**Set&lt;ApplicationIntegrationType&gt;**](ApplicationIntegrationType.md) |  | [optional] [default to undefined]
**handler** | [**ApplicationCommandCreateRequestHandler**](ApplicationCommandCreateRequestHandler.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationCommandPatchRequestPartial } from 'dc_rest';

const instance: ApplicationCommandPatchRequestPartial = {
    name,
    name_localizations,
    description,
    description_localizations,
    _options,
    default_member_permissions,
    dm_permission,
    contexts,
    integration_types,
    handler,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
