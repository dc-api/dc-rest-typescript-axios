# MessageResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **number** |  | [default to undefined]
**content** | **string** |  | [default to undefined]
**mentions** | [**Array&lt;UserResponse&gt;**](UserResponse.md) |  | [default to undefined]
**mention_roles** | **Set&lt;string&gt;** |  | [default to undefined]
**attachments** | [**Array&lt;MessageAttachmentResponse&gt;**](MessageAttachmentResponse.md) |  | [default to undefined]
**embeds** | [**Array&lt;MessageEmbedResponse&gt;**](MessageEmbedResponse.md) |  | [default to undefined]
**timestamp** | **string** |  | [default to undefined]
**flags** | **number** |  | [default to undefined]
**components** | [**Array&lt;BasicMessageResponseComponentsInner&gt;**](BasicMessageResponseComponentsInner.md) |  | [default to undefined]
**id** | **string** |  | [default to undefined]
**channel_id** | **string** |  | [default to undefined]
**author** | [**UserResponse**](UserResponse.md) |  | [default to undefined]
**pinned** | **boolean** |  | [default to undefined]
**mention_everyone** | **boolean** |  | [default to undefined]
**tts** | **boolean** |  | [default to undefined]
**edited_timestamp** | **string** |  | [optional] [default to undefined]
**resolved** | [**ResolvedObjectsResponse**](ResolvedObjectsResponse.md) |  | [optional] [default to undefined]
**stickers** | [**Array&lt;GetSticker200Response&gt;**](GetSticker200Response.md) |  | [optional] [default to undefined]
**sticker_items** | [**Array&lt;MessageStickerItemResponse&gt;**](MessageStickerItemResponse.md) |  | [optional] [default to undefined]
**call** | [**MessageCallResponse**](MessageCallResponse.md) |  | [optional] [default to undefined]
**activity** | **object** |  | [optional] [default to undefined]
**application** | [**BasicApplicationResponse**](BasicApplicationResponse.md) |  | [optional] [default to undefined]
**application_id** | **string** |  | [optional] [default to undefined]
**interaction** | [**MessageInteractionResponse**](MessageInteractionResponse.md) |  | [optional] [default to undefined]
**nonce** | [**BasicMessageResponseNonce**](BasicMessageResponseNonce.md) |  | [optional] [default to undefined]
**webhook_id** | **string** |  | [optional] [default to undefined]
**message_reference** | [**MessageReferenceResponse**](MessageReferenceResponse.md) |  | [optional] [default to undefined]
**thread** | [**ThreadResponse**](ThreadResponse.md) |  | [optional] [default to undefined]
**mention_channels** | [**Array&lt;MessageMentionChannelResponse | null&gt;**](MessageMentionChannelResponse.md) |  | [optional] [default to undefined]
**role_subscription_data** | [**MessageRoleSubscriptionDataResponse**](MessageRoleSubscriptionDataResponse.md) |  | [optional] [default to undefined]
**purchase_notification** | [**PurchaseNotificationResponse**](PurchaseNotificationResponse.md) |  | [optional] [default to undefined]
**position** | **number** |  | [optional] [default to undefined]
**poll** | [**PollResponse**](PollResponse.md) |  | [optional] [default to undefined]
**interaction_metadata** | [**BasicMessageResponseInteractionMetadata**](BasicMessageResponseInteractionMetadata.md) |  | [optional] [default to undefined]
**message_snapshots** | [**Array&lt;MessageSnapshotResponse&gt;**](MessageSnapshotResponse.md) |  | [optional] [default to undefined]
**reactions** | [**Array&lt;MessageReactionResponse&gt;**](MessageReactionResponse.md) |  | [optional] [default to undefined]
**referenced_message** | [**BasicMessageResponse**](BasicMessageResponse.md) |  | [optional] [default to undefined]

## Example

```typescript
import { MessageResponse } from 'dc_rest';

const instance: MessageResponse = {
    type,
    content,
    mentions,
    mention_roles,
    attachments,
    embeds,
    timestamp,
    flags,
    components,
    id,
    channel_id,
    author,
    pinned,
    mention_everyone,
    tts,
    edited_timestamp,
    resolved,
    stickers,
    sticker_items,
    call,
    activity,
    application,
    application_id,
    interaction,
    nonce,
    webhook_id,
    message_reference,
    thread,
    mention_channels,
    role_subscription_data,
    purchase_notification,
    position,
    poll,
    interaction_metadata,
    message_snapshots,
    reactions,
    referenced_message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
