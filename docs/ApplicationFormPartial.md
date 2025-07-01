# ApplicationFormPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | [**ApplicationFormPartialDescription**](ApplicationFormPartialDescription.md) |  | [optional] [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**cover_image** | **string** |  | [optional] [default to undefined]
**team_id** | **string** |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]
**interactions_endpoint_url** | **string** |  | [optional] [default to undefined]
**explicit_content_filter** | **number** |  | [optional] [default to undefined]
**max_participants** | **number** |  | [optional] [default to undefined]
**type** | **number** |  | [optional] [default to undefined]
**tags** | **Set&lt;string&gt;** |  | [optional] [default to undefined]
**custom_install_url** | **string** |  | [optional] [default to undefined]
**install_params** | [**ApplicationOAuth2InstallParams**](ApplicationOAuth2InstallParams.md) |  | [optional] [default to undefined]
**role_connections_verification_url** | **string** |  | [optional] [default to undefined]
**integration_types_config** | [**{ [key: string]: ApplicationFormPartialIntegrationTypesConfigValue; }**](ApplicationFormPartialIntegrationTypesConfigValue.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationFormPartial } from 'dc_rest';

const instance: ApplicationFormPartial = {
    description,
    icon,
    cover_image,
    team_id,
    flags,
    interactions_endpoint_url,
    explicit_content_filter,
    max_participants,
    type,
    tags,
    custom_install_url,
    install_params,
    role_connections_verification_url,
    integration_types_config,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
