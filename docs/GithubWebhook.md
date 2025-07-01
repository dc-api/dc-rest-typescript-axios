# GithubWebhook


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sender** | [**GithubUser**](GithubUser.md) |  | [default to undefined]
**action** | **string** |  | [optional] [default to undefined]
**ref** | **string** |  | [optional] [default to undefined]
**ref_type** | **string** |  | [optional] [default to undefined]
**comment** | [**GithubComment**](GithubComment.md) |  | [optional] [default to undefined]
**issue** | [**GithubIssue**](GithubIssue.md) |  | [optional] [default to undefined]
**pull_request** | [**GithubIssue**](GithubIssue.md) |  | [optional] [default to undefined]
**repository** | [**GithubRepository**](GithubRepository.md) |  | [optional] [default to undefined]
**forkee** | [**GithubRepository**](GithubRepository.md) |  | [optional] [default to undefined]
**member** | [**GithubUser**](GithubUser.md) |  | [optional] [default to undefined]
**release** | [**GithubRelease**](GithubRelease.md) |  | [optional] [default to undefined]
**head_commit** | [**GithubCommit**](GithubCommit.md) |  | [optional] [default to undefined]
**commits** | [**Array&lt;GithubCommit&gt;**](GithubCommit.md) |  | [optional] [default to undefined]
**forced** | **boolean** |  | [optional] [default to undefined]
**compare** | **string** |  | [optional] [default to undefined]
**review** | [**GithubReview**](GithubReview.md) |  | [optional] [default to undefined]
**check_run** | [**GithubCheckRun**](GithubCheckRun.md) |  | [optional] [default to undefined]
**check_suite** | [**GithubCheckSuite**](GithubCheckSuite.md) |  | [optional] [default to undefined]
**discussion** | [**GithubDiscussion**](GithubDiscussion.md) |  | [optional] [default to undefined]
**answer** | [**GithubComment**](GithubComment.md) |  | [optional] [default to undefined]

## Example

```typescript
import { GithubWebhook } from 'dc_rest';

const instance: GithubWebhook = {
    sender,
    action,
    ref,
    ref_type,
    comment,
    issue,
    pull_request,
    repository,
    forkee,
    member,
    release,
    head_commit,
    commits,
    forced,
    compare,
    review,
    check_run,
    check_suite,
    discussion,
    answer,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
