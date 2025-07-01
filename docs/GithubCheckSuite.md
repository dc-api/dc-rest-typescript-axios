# GithubCheckSuite


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**head_sha** | **string** |  | [default to undefined]
**app** | [**GithubCheckApp**](GithubCheckApp.md) |  | [default to undefined]
**conclusion** | **string** |  | [optional] [default to undefined]
**head_branch** | **string** |  | [optional] [default to undefined]
**pull_requests** | [**Array&lt;GithubCheckPullRequest&gt;**](GithubCheckPullRequest.md) |  | [optional] [default to undefined]

## Example

```typescript
import { GithubCheckSuite } from 'dc_rest';

const instance: GithubCheckSuite = {
    head_sha,
    app,
    conclusion,
    head_branch,
    pull_requests,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
