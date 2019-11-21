# Sprint 3

## Additions to be completed this sprint:
    * Organizational diversity metric is fully completed. 
        * changed this to timeseries data, each org has an entry for each timeframe
        * method documentation in the code and in the design doc have been updated to reflect this change 
        * more in line with the trend for most metrics to be timeseries
    * Issue response time metric will be added in augur/metrics/issues/issues.py
        * This function will find the average time from when a issue is first created to the first message posted on that issue. It will average this for all issues within a repository and for all repos in a repo group.
        * The python tests for this function will also be comepleted this sprint and they will test the endpoint with different variables to make sure that something is always returned.
    * Issue messages over time metric will also be added in augur/metrics/issues/issues.py
        * This will find the amount of messages on issues for every week since creation
        * The python tests will also be completed in this sprint to make sure a value is always returned whether given a group or id 
