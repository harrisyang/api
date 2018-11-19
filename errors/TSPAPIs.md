# TSP APIs
> Note: All the TSP APIs requires the account to be TSP enabled by Zoom admin. All the user level TSP APIs needs TSP to be enabled on account level.

### Retrieve account's TSP information
https://marketplace.zoom.us/docs/api-reference/zoom-api/tsp/tsp

| code | message                 | 
|:---- |:----------------------- |
| 2024 | Account not enable TSP. |

### Update account's TSP information
https://marketplace.zoom.us/docs/api-reference/zoom-api/tsp/tspupdate

| code | message                 | 
|:---- |:----------------------- |
| 2024 | Account not enable TSP. |

### List user's TSP accounts
https://marketplace.zoom.us/docs/api-reference/zoom-api/tsp/usertsps

| code | message                          |
|:---- |:-------------------------------- |
| 1000 | Invite not exist.                |
| 1001 | User not exist.                  | 
| 1010 | User not belong to this account. |
| 2024 | Account not enable TSP.          |

### Add a user's TSP account
https://marketplace.zoom.us/docs/api-reference/zoom-api/tsp/usertspcreate

| code | message                          |
|:---- |:-------------------------------- |
| 1000 | Invite not exist.                |
| 1001 | User not exist.                  | 
| 1010 | User not belong to this account. |
| 2024 | Account not enable TSP.          |

### Retrieve a user's TSP account
https://marketplace.zoom.us/docs/api-reference/zoom-api/tsp/usertsp

| code | message                          |
|:---- |:-------------------------------- |
| 1000 | Invite not exist.                |
| 1001 | User not exist.                  | 
| 1010 | User not belong to this account. |
| 2024 | Account not enable TSP.          |

### Update a TSP account
https://marketplace.zoom.us/docs/api-reference/zoom-api/tsp/usertspupdate

| code | message                          |
|:---- |:-------------------------------- |
| 1000 | Invite not exist.                |
| 1001 | User not exist.                  | 
| 1010 | User not belong to this account. |
| 2024 | Account not enable TSP.          |


### Delete a user's TSP account
https://marketplace.zoom.us/docs/api-reference/zoom-api/tsp/usertspdelete

| code | message                          |
|:---- |:-------------------------------- |
| 1000 | Invite not exist.                |
| 1001 | User not exist.                  | 
| 1010 | User not belong to this account. |
| 2024 | Account not enable TSP.          |