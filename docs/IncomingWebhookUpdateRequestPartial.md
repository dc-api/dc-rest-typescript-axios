# IncomingWebhookUpdateRequestPartial


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **string** |  | [optional] [default to undefined]
**embeds** | [**Array&lt;RichEmbed&gt;**](RichEmbed.md) |  | [optional] [default to undefined]
**allowed_mentions** | [**MessageAllowedMentionsRequest**](MessageAllowedMentionsRequest.md) |  | [optional] [default to undefined]
**components** | [**Array&lt;BaseCreateMessageCreateRequestComponentsInner&gt;**](BaseCreateMessageCreateRequestComponentsInner.md) |  | [optional] [default to undefined]
**attachments** | [**Array&lt;MessageAttachmentRequest&gt;**](MessageAttachmentRequest.md) |  | [optional] [default to undefined]
**poll** | [**PollCreateRequest**](PollCreateRequest.md) |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { IncomingWebhookUpdateRequestPartial } from 'dc_rest';

const instance: IncomingWebhookUpdateRequestPartial = {
    content,
    embeds,
    allowed_mentions,
    components,
    attachments,
    poll,
    flags,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
