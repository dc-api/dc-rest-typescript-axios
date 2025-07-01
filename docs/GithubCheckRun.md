# GithubCheckRun


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [default to undefined]
**html_url** | **string** |  | [default to undefined]
**check_suite** | [**GithubCheckSuite**](GithubCheckSuite.md) |  | [default to undefined]
**conclusion** | **string** |  | [optional] [default to undefined]
**details_url** | **string** |  | [optional] [default to undefined]
**output** | [**GithubCheckRunOutput**](GithubCheckRunOutput.md) |  | [optional] [default to undefined]
**pull_requests** | [**Array&lt;GithubCheckPullRequest&gt;**](GithubCheckPullRequest.md) |  | [optional] [default to undefined]

## Example

```typescript
import { GithubCheckRun } from 'dc_rest';

const instance: GithubCheckRun = {
    name,
    html_url,
    check_suite,
    conclusion,
    details_url,
    output,
    pull_requests,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
