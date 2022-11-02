# gh-actions-execution-flow

Notes: if one action fails, whole job and further dependent jobs aren't even executed

Special Conditional Functions :
1> failure() - if any previous job or step fail

2> success() - if none of previous steps fail

3> always()

4> cancelled() - returns true if workflow has been cancelled
