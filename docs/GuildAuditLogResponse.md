# GuildAuditLogResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**audit_log_entries** | [**Array&lt;AuditLogEntryResponse&gt;**](AuditLogEntryResponse.md) |  | [default to undefined]
**users** | [**Array&lt;UserResponse&gt;**](UserResponse.md) |  | [default to undefined]
**integrations** | [**Array&lt;GuildAuditLogResponseIntegrationsInner&gt;**](GuildAuditLogResponseIntegrationsInner.md) |  | [default to undefined]
**webhooks** | [**Array&lt;ListChannelWebhooks200ResponseInner&gt;**](ListChannelWebhooks200ResponseInner.md) |  | [default to undefined]
**guild_scheduled_events** | [**Array&lt;ListGuildScheduledEvents200ResponseInner&gt;**](ListGuildScheduledEvents200ResponseInner.md) |  | [default to undefined]
**threads** | [**Array&lt;ThreadResponse&gt;**](ThreadResponse.md) |  | [default to undefined]
**application_commands** | [**Array&lt;ApplicationCommandResponse&gt;**](ApplicationCommandResponse.md) |  | [default to undefined]
**auto_moderation_rules** | [**Array&lt;ListAutoModerationRules200ResponseInner&gt;**](ListAutoModerationRules200ResponseInner.md) |  | [default to undefined]

## Example

```typescript
import { GuildAuditLogResponse } from 'dc_rest';

const instance: GuildAuditLogResponse = {
    audit_log_entries,
    users,
    integrations,
    webhooks,
    guild_scheduled_events,
    threads,
    application_commands,
    auto_moderation_rules,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
