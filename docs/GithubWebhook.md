# GithubWebhook


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sender** | [**GithubUser**](GithubUser.md) |  | [default to undefined]
**action** | **string** |  | [optional] [default to undefined]
**ref** | **string** |  | [optional] [default to undefined]
**ref_type** | **string** |  | [optional] [default to undefined]
**comment** | [**GithubWebhookComment**](GithubWebhookComment.md) |  | [optional] [default to undefined]
**issue** | [**GithubWebhookIssue**](GithubWebhookIssue.md) |  | [optional] [default to undefined]
**pull_request** | [**GithubWebhookIssue**](GithubWebhookIssue.md) |  | [optional] [default to undefined]
**repository** | [**GithubWebhookRepository**](GithubWebhookRepository.md) |  | [optional] [default to undefined]
**forkee** | [**GithubWebhookRepository**](GithubWebhookRepository.md) |  | [optional] [default to undefined]
**member** | [**GithubWebhookMember**](GithubWebhookMember.md) |  | [optional] [default to undefined]
**release** | [**GithubWebhookRelease**](GithubWebhookRelease.md) |  | [optional] [default to undefined]
**head_commit** | [**GithubWebhookHeadCommit**](GithubWebhookHeadCommit.md) |  | [optional] [default to undefined]
**commits** | [**Array&lt;GithubCommit&gt;**](GithubCommit.md) |  | [optional] [default to undefined]
**forced** | **boolean** |  | [optional] [default to undefined]
**compare** | **string** |  | [optional] [default to undefined]
**review** | [**GithubWebhookReview**](GithubWebhookReview.md) |  | [optional] [default to undefined]
**check_run** | [**GithubWebhookCheckRun**](GithubWebhookCheckRun.md) |  | [optional] [default to undefined]
**check_suite** | [**GithubWebhookCheckSuite**](GithubWebhookCheckSuite.md) |  | [optional] [default to undefined]
**discussion** | [**GithubWebhookDiscussion**](GithubWebhookDiscussion.md) |  | [optional] [default to undefined]
**answer** | [**GithubWebhookComment**](GithubWebhookComment.md) |  | [optional] [default to undefined]

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
