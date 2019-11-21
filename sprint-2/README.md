# Sprint 2

## Additions to be completed this sprint:
1. Top external orgs group endpoint stub in augur/metrics/contributor/routes
2. Entrance difficulty repo endpoint stub in augur/metrics/contributor/routes
3. Organizational diversity group endpoint stub in augur/metrics/contributor/routes
4. Organizational diversity metric function first try in augur/metrics/contributor/contributor.py
   1. will function basically the same as the committers metric but will select and group the results by cntrb_company
   2. will measure all contributions, not just commits

## Additions to be completed in the future:
1. Top external organizations metric function in augur/metrics/contributor/contributor.py
    1. This function will return groups of organizaiton that do not own the repositories ordered by total commits they have contributed.
    2. The metric functionality will be added at a later date but the endpoint stub will be added in this sprint.

2. Entrance difficulty metric function in augur/metrics/contributor/contributor.py
    1. This function will return the average time between a fork of a repository and a contributor's first commit only for contributors who have made a commit in the repo for all repositories in a repo group.
    2. The metric functionality will be added at a later date but the endpoint stub will be added in this sprint.