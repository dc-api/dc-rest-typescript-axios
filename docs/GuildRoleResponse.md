# GuildRoleResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**permissions** | **string** |  | [default to undefined]
**position** | **number** |  | [default to undefined]
**color** | **number** |  | [default to undefined]
**hoist** | **boolean** |  | [default to undefined]
**managed** | **boolean** |  | [default to undefined]
**mentionable** | **boolean** |  | [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**icon** | **string** |  | [optional] [default to undefined]
**unicode_emoji** | **string** |  | [optional] [default to undefined]
**tags** | [**GuildRoleTagsResponse**](GuildRoleTagsResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { GuildRoleResponse } from 'dc_rest';

const instance: GuildRoleResponse = {
    id,
    name,
    permissions,
    position,
    color,
    hoist,
    managed,
    mentionable,
    description,
    icon,
    unicode_emoji,
    tags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
