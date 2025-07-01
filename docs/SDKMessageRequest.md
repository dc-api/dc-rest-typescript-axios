# SDKMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **string** |  | [optional] [default to undefined]
**embeds** | [**Array&lt;RichEmbed&gt;**](RichEmbed.md) |  | [optional] [default to undefined]
**allowed_mentions** | [**MessageAllowedMentionsRequest**](MessageAllowedMentionsRequest.md) |  | [optional] [default to undefined]
**sticker_ids** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**components** | [**Array&lt;BaseCreateMessageCreateRequestComponentsInner&gt;**](BaseCreateMessageCreateRequestComponentsInner.md) |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]
**attachments** | [**Array&lt;MessageAttachmentRequest&gt;**](MessageAttachmentRequest.md) |  | [optional] [default to undefined]
**poll** | [**PollCreateRequest**](PollCreateRequest.md) |  | [optional] [default to undefined]
**confetti_potion** | **object** |  | [optional] [default to undefined]
**message_reference** | [**MessageReferenceRequest**](MessageReferenceRequest.md) |  | [optional] [default to undefined]
**nonce** | [**BasicMessageResponseNonce**](BasicMessageResponseNonce.md) |  | [optional] [default to undefined]
**enforce_nonce** | **boolean** |  | [optional] [default to undefined]
**tts** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { SDKMessageRequest } from 'dc_rest';

const instance: SDKMessageRequest = {
    content,
    embeds,
    allowed_mentions,
    sticker_ids,
    components,
    flags,
    attachments,
    poll,
    confetti_potion,
    message_reference,
    nonce,
    enforce_nonce,
    tts,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
