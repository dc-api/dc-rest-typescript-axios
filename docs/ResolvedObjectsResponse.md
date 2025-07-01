# ResolvedObjectsResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**users** | [**{ [key: string]: UserResponse; }**](UserResponse.md) |  | [default to undefined]
**members** | [**{ [key: string]: GuildMemberResponse; }**](GuildMemberResponse.md) |  | [default to undefined]
**channels** | [**{ [key: string]: GetChannel200Response; }**](GetChannel200Response.md) |  | [default to undefined]
**roles** | [**{ [key: string]: GuildRoleResponse; }**](GuildRoleResponse.md) |  | [default to undefined]

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
