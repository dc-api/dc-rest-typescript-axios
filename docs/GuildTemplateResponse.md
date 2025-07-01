# GuildTemplateResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**usage_count** | **number** |  | [default to undefined]
**creator_id** | **string** |  | [default to undefined]
**created_at** | **string** |  | [default to undefined]
**updated_at** | **string** |  | [default to undefined]
**source_guild_id** | **string** |  | [default to undefined]
**serialized_source_guild** | [**GuildTemplateSnapshotResponse**](GuildTemplateSnapshotResponse.md) |  | [default to undefined]
**description** | **string** |  | [optional] [default to undefined]
**creator** | [**UserResponse**](UserResponse.md) |  | [optional] [default to undefined]
**is_dirty** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { GuildTemplateResponse } from 'dc_rest';

const instance: GuildTemplateResponse = {
    code,
    name,
    usage_count,
    creator_id,
    created_at,
    updated_at,
    source_guild_id,
    serialized_source_guild,
    description,
    creator,
    is_dirty,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
