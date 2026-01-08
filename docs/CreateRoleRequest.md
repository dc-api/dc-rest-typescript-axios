# CreateRoleRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [optional] [default to undefined]
**permissions** | **number** |  | [optional] [default to undefined]
**color** | **number** |  | [optional] [default to undefined]
**colors** | [**CreateRoleRequestColors**](CreateRoleRequestColors.md) |  | [optional] [default to undefined]
**hoist** | **boolean** |  | [optional] [default to undefined]
**mentionable** | **boolean** |  | [optional] [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**unicode_emoji** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateRoleRequest } from 'dc_rest';

const instance: CreateRoleRequest = {
    name,
    permissions,
    color,
    colors,
    hoist,
    mentionable,
    icon,
    unicode_emoji,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
