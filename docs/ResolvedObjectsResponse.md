# ResolvedObjectsResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**users** | [**{ [key: string]: UserResponse; }**](UserResponse.md) |  | [optional] [default to undefined]
**members** | [**{ [key: string]: BasicGuildMemberResponse; }**](BasicGuildMemberResponse.md) |  | [optional] [default to undefined]
**channels** | [**{ [key: string]: GetChannel200Response; }**](GetChannel200Response.md) |  | [optional] [default to undefined]
**roles** | [**{ [key: string]: GuildRoleResponse; }**](GuildRoleResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ResolvedObjectsResponse } from 'dc_rest';

const instance: ResolvedObjectsResponse = {
    users,
    members,
    channels,
    roles,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
