# BaseCreateMessageCreateRequest


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
**shared_client_theme** | [**CustomClientThemeShareRequest**](CustomClientThemeShareRequest.md) |  | [optional] [default to undefined]
**confetti_potion** | **object** |  | [optional] [default to undefined]

## Example

```typescript
import { BaseCreateMessageCreateRequest } from 'dc_rest';

const instance: BaseCreateMessageCreateRequest = {
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
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
