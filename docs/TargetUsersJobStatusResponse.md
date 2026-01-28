# TargetUsersJobStatusResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **number** | The status of the job processing the target users. | [default to undefined]
**total_users** | **number** | The total number of users in the provided list. | [default to undefined]
**processed_users** | **number** | The number of users processed so far. | [default to undefined]
**created_at** | **string** | The timestamp when the job was created. | [optional] [default to undefined]
**completed_at** | **string** | The timestamp when the job was successfully completed. | [optional] [default to undefined]
**error_message** | **string** | The error message if the job failed. | [optional] [default to undefined]

## Example

```typescript
import { TargetUsersJobStatusResponse } from 'dc_rest';

const instance: TargetUsersJobStatusResponse = {
    status,
    total_users,
    processed_users,
    created_at,
    completed_at,
    error_message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
