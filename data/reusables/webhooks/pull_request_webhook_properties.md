Key | Type | Description
----|------|-------------
`action`|`string` | The action that was performed. Can be one of  `opened`, `edited`, `closed`, `assigned`, `unassigned`, `review_requested`, `review_request_removed`, `ready_for_review`, `converted_to_draft`, `labeled`, `unlabeled`, `synchronize`, `locked`, `unlocked`, or `reopened`. If the action is `closed` and the `merged` key is `false`, the pull request was closed with unmerged commits. If the action is `closed` and the `merged` key is `true`, the pull request was merged.
