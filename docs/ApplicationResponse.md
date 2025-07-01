# ApplicationResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**description** | **string** |  | [default to undefined]
**verify_key** | **string** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**type** | **number** |  | [optional] [default to undefined]
**cover_image** | **string** |  | [optional] [default to undefined]
**primary_sku_id** | **string** |  | [optional] [default to undefined]
**bot** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**slug** | **string** |  | [optional] [default to undefined]
**guild_id** | **string** |  | [optional] [default to undefined]
**rpc_origins** | **Array&lt;string | null&gt;** |  | [optional] [default to undefined]
**bot_public** | **boolean** |  | [optional] [default to undefined]
**bot_require_code_grant** | **boolean** |  | [optional] [default to undefined]
**terms_of_service_url** | **string** |  | [optional] [default to undefined]
**privacy_policy_url** | **string** |  | [optional] [default to undefined]
**custom_install_url** | **string** |  | [optional] [default to undefined]
**install_params** | [**ApplicationOAuth2InstallParamsResponse**](ApplicationOAuth2InstallParamsResponse.md) |  | [optional] [default to undefined]
**integration_types_config** | [**{ [key: string]: ApplicationIntegrationTypeConfigurationResponse; }**](ApplicationIntegrationTypeConfigurationResponse.md) |  | [optional] [default to undefined]
**max_participants** | **number** |  | [optional] [default to undefined]
**tags** | **Set&lt;string&gt;** |  | [optional] [default to undefined]

## Example

```typescript
import { ApplicationResponse } from 'dc_rest';

const instance: ApplicationResponse = {
    id,
    name,
    description,
    verify_key,
    flags,
    icon,
    type,
    cover_image,
    primary_sku_id,
    bot,
    slug,
    guild_id,
    rpc_origins,
    bot_public,
    bot_require_code_grant,
    terms_of_service_url,
    privacy_policy_url,
    custom_install_url,
    install_params,
    integration_types_config,
    max_participants,
    tags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
