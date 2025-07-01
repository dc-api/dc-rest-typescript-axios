# BaseCreateMessageCreateRequestComponentsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **number** |  | [default to undefined]
**components** | [**Array&lt;TextDisplayComponentForMessageRequest&gt;**](TextDisplayComponentForMessageRequest.md) |  | [default to undefined]
**file** | [**UnfurledMediaRequestWithAttachmentReferenceRequired**](UnfurledMediaRequestWithAttachmentReferenceRequired.md) |  | [default to undefined]
**items** | [**Array&lt;MediaGalleryItemRequest&gt;**](MediaGalleryItemRequest.md) |  | [default to undefined]
**accessory** | [**SectionComponentForMessageRequestAccessory**](SectionComponentForMessageRequestAccessory.md) |  | [default to undefined]
**content** | **string** |  | [default to undefined]
**accent_color** | **number** |  | [optional] [default to undefined]
**spoiler** | **boolean** |  | [optional] [default to undefined]
**spacing** | **number** |  | [optional] [default to undefined]
**divider** | **boolean** |  | [optional] [default to undefined]

## Example

```typescript
import { BaseCreateMessageCreateRequestComponentsInner } from 'dc_rest';

const instance: BaseCreateMessageCreateRequestComponentsInner = {
    type,
    components,
    file,
    items,
    accessory,
    content,
    accent_color,
    spoiler,
    spacing,
    divider,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
