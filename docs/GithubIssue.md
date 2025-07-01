# GithubIssue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **number** |  | [default to undefined]
**number** | **number** |  | [default to undefined]
**html_url** | **string** |  | [default to undefined]
**user** | [**GithubUser**](GithubUser.md) |  | [default to undefined]
**title** | **string** |  | [default to undefined]
**body** | **string** |  | [optional] [default to undefined]
**pull_request** | **any** |  | [optional] [default to undefined]

## Example

```typescript
import { GithubIssue } from 'dc_rest';

const instance: GithubIssue = {
    id,
    number,
    html_url,
    user,
    title,
    body,
    pull_request,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
