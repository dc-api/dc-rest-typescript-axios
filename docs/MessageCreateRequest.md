# MessageCreateRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **string** |  | [optional] [default to undefined]
**embeds** | [**Array&lt;RichEmbed&gt;**](RichEmbed.md) |  | [optional] [default to undefined]
**allowed_mentions** | [**BaseCreateMessageCreateRequestAllowedMentions**](BaseCreateMessageCreateRequestAllowedMentions.md) |  | [optional] [default to undefined]
**sticker_ids** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**components** | [**Array&lt;BaseCreateMessageCreateRequestComponentsInner&gt;**](BaseCreateMessageCreateRequestComponentsInner.md) |  | [optional] [default to undefined]
**flags** | **number** |  | [optional] [default to undefined]
**attachments** | [**Array&lt;MessageAttachmentRequest&gt;**](MessageAttachmentRequest.md) |  | [optional] [default to undefined]
**poll** | [**BaseCreateMessageCreateRequestPoll**](BaseCreateMessageCreateRequestPoll.md) |  | [optional] [default to undefined]
**shared_client_theme** | [**BaseCreateMessageCreateRequestSharedClientTheme**](BaseCreateMessageCreateRequestSharedClientTheme.md) |  | [optional] [default to undefined]
**confetti_potion** | [**BaseCreateMessageCreateRequestConfettiPotion**](BaseCreateMessageCreateRequestConfettiPotion.md) |  | [optional] [default to undefined]
**message_reference** | [**MessageCreateRequestMessageReference**](MessageCreateRequestMessageReference.md) |  | [optional] [default to undefined]
**nonce** | [**BasicMessageResponseNonce**](BasicMessageResponseNonce.md) |  | [optional] [default to undefined]
**enforce_nonce** | **boolean** |  | [optional] [default to undefined]
**tts** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { MessageCreateRequest } from 'dc_rest';

const instance: MessageCreateRequest = {
    content,
    embeds,
    allowed_mentions,
    sticker_ids,
    components,
    flags,
    attachments,
    poll,
    shared_client_theme,
    confetti_potion,
    message_reference,
    nonce,
    enforce_nonce,
    tts,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
