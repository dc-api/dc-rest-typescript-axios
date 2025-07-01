# ApplicationCommandResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**application_id** | **string** |  | [default to undefined]
**version** | **string** |  | [default to undefined]
**type** | **number** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**description** | **string** |  | [default to undefined]
**default_member_permissions** | **string** |  | [optional] [default to undefined]
**name_localized** | **string** |  | [optional] [default to undefined]
**name_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**description_localized** | **string** |  | [optional] [default to undefined]
**description_localizations** | **{ [key: string]: string; }** |  | [optional] [default to undefined]
**guild_id** | **string** |  | [optional] [default to undefined]
**dm_permission** | **boolean** |  | [optional] [default to undefined]
**contexts** | **Set&lt;number&gt;** |  | [optional] [default to undefined]
**integration_types** | **Set&lt;number&gt;** |  | [optional] [default to undefined]
**_options** | [**Array&lt;ApplicationCommandResponseOptionsInner&gt;**](ApplicationCommandResponseOptionsInner.md) |  | [optional] [default to undefined]
**nsfw** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationCommandResponse } from 'dc_rest';

const instance: ApplicationCommandResponse = {
    id,
    application_id,
    version,
    type,
    name,
    description,
    default_member_permissions,
    name_localized,
    name_localizations,
    description_localized,
    description_localizations,
    guild_id,
    dm_permission,
    contexts,
    integration_types,
    _options,
    nsfw,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
