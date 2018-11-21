# Report APIs

> Note: All the Report APIs are only for paid accounts.

### Retrieve daily report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportdaily

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. | 

### Retrieve hosts report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportusers

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. | 

### Retrieve meetings report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportmeetings

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. | 
| 300  | The next page token is invalid or expired.    |

### Retrieve meeting details report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportmeetingdetails

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 300  | Can not access webinar info, {meetingId}.         | 
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | Meeting ID is invalid or not end.                 |
| 3001 | This meeting is not available or ID is not valid. |

### Retrieve meeting participants report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportmeetingparticipants

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 300  | Can not access webinar info, {meetingId}.         | 
| 300  | The next page token is invalid or expired.        |
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | Meeting ID is invalid or not end.                 |
| 3001 | This meeting is not available or ID is not valid. |


### Retrieve meeting polls report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportmeetingpolls

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | This meeting is not available or ID is not valid. |


### Retrieve webinar details report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportwebinardetails

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 300  | Can not access meeting info, {webinarId}.         | 
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | Webinar ID is invalid or not end.                 |
| 3001 | This meeting is not available or ID is not valid. |


### Retrieve webinar participants report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportwebinarparticipants

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 300  | Can not access meeting info, {webinarId}.         | 
| 300  | The next page token is invalid or expired.        |
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | Webinar ID is invalid or not end.                 |
| 3001 | This meeting is not available or ID is not valid. |


### Retrieve webinar polls report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportwebinarpolls

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. |
| 200  | Not subscribe webinar plan.                   | 
| 1010 | User not belong to this account: {accountId}. |
| 3001 | Webinar ID is invalid or not end.             |

### Retrieve webinar Q&A report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reportwebinarqa

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. |
| 200  | Not subscribe webinar plan.                   | 
| 1010 | User not belong to this account: {accountId}. |
| 3001 | Webinar ID is invalid or not end.             |

### Retrieve telephone report
https://marketplace.zoom.us/docs/api-reference/zoom-api/reports/reporttelephone

| code | message                                        |
|:---- |:---------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.  |
| 200  | Not subscribe toll-free audio conference plan. | 
