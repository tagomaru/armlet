v1.2.1 - 2019-02-06
-----------------------

- Better MythX API error reporting, esp HTTP 400, 401, 502, 504
- example analysis mode is "quick"

v1.2.0 - 2019-02-03
-----------------------

- tool status tracking via clientToolName
- Simplify example in README
- Adjust to accomodate looser required data fields
- If no registration set, run as a trial user
- More useful messages around common situations with remedial suggestions:
  * timeout
  * authentication problems
  * UUID not found
  * Sending JSON data which is too large
- Add interfaces to list previous analyses results and the status of each
- Add corresponding example programs for the above
- Numerous doc tweaks and code tweaks
