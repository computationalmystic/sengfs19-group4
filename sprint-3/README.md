# Sprint 2

## Additions to be completed this sprint:
* Issue response time metric will be added in augur/metrics/issues/issues.py
    1. This function will find the average time from when a issue is first created to the first message posted on that issue. It will average this for all issues within a repository and for all repos in a repo group.
    2. The python tests for this function will also be comepleted this sprint and they will test the endpoint with different variables to make sure that something is always returned.