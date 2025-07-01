# BasicMessageResponseComponentsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **number** |  | [default to undefined]
**id** | **number** |  | [default to undefined]
**components** | [**Array&lt;TextDisplayComponentResponse&gt;**](TextDisplayComponentResponse.md) |  | [default to undefined]
**spoiler** | **boolean** |  | [default to undefined]
**file** | [**UnfurledMediaResponse**](UnfurledMediaResponse.md) |  | [default to undefined]
**items** | [**Array&lt;MediaGalleryItemResponse&gt;**](MediaGalleryItemResponse.md) |  | [default to undefined]
**accessory** | [**SectionComponentResponseAccessory**](SectionComponentResponseAccessory.md) |  | [default to undefined]
**spacing** | **number** |  | [default to undefined]
**divider** | **boolean** |  | [default to undefined]
**content** | **string** |  | [default to undefined]
**accent_color** | **number** |  | [optional] [default to undefined]
**name** | **string** |  | [optional] [default to undefined]
**size** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { BasicMessageResponseComponentsInner } from 'dc_rest';

const instance: BasicMessageResponseComponentsInner = {
    type,
    id,
    components,
    spoiler,
    file,
    items,
    accessory,
    spacing,
    divider,
    content,
    accent_color,
    name,
    size,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
