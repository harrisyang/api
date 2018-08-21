### Retrieve daily report
https://devdocs.zoom.us/v1.0/reference#reportdaily

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. | 

### Retrieve hosts report
https://devdocs.zoom.us/v1.0/reference#reportusers

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. | 

### Retrieve meetings report
https://devdocs.zoom.us/v1.0/reference#reportmeetings

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. | 
| 300  | The next page token is invalid or expired.    |

### Retrieve meeting details report
https://devdocs.zoom.us/v1.0/reference#reportmeetingdetails

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 300  | Can not access webinar info, {meetingId}.         | 
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | Meeting ID is invalid or not end.                 |
| 3001 | This meeting is not available or ID is not valid. |

### Retrieve meeting participants report
https://devdocs.zoom.us/v1.0/reference#reportmeetingparticipants

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 300  | Can not access webinar info, {meetingId}.         | 
| 300  | The next page token is invalid or expired.        |
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | Meeting ID is invalid or not end.                 |
| 3001 | This meeting is not available or ID is not valid. |


### Retrieve meeting polls report
https://devdocs.zoom.us/v1.0/reference#reportmeetingpolls

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | This meeting is not available or ID is not valid. |


### Retrieve webinar details report
https://devdocs.zoom.us/v1.0/reference#reportwebinardetails

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 300  | Can not access meeting info, {webinarId}.         | 
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | Webinar ID is invalid or not end.                 |
| 3001 | This meeting is not available or ID is not valid. |


### Retrieve webinar participants report
https://devdocs.zoom.us/v1.0/reference#reportwebinarparticipants

| code | message                                           |
|:---- |:------------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.     |
| 300  | Can not access meeting info, {webinarId}.         | 
| 300  | The next page token is invalid or expired.        |
| 1010 | User not belong to this account: {accountId}.     |
| 3001 | Webinar ID is invalid or not end.                 |
| 3001 | This meeting is not available or ID is not valid. |


### Retrieve webinar polls report
https://devdocs.zoom.us/v1.0/reference#reportwebinarpolls

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. |
| 200  | Not subscribe webinar plan.                   | 
| 1010 | User not belong to this account: {accountId}. |
| 3001 | Webinar ID is invalid or not end.             |

### Retrieve webinar Q&A report
https://devdocs.zoom.us/v1.0/reference#reportwebinarqa

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for Paid account: {accountId}. |
| 200  | Not subscribe webinar plan.                   | 
| 1010 | User not belong to this account: {accountId}. |
| 3001 | Webinar ID is invalid or not end.             |

### Retrieve telephone report
https://devdocs.zoom.us/v1.0/reference#reporttelephone

| code | message                                        |
|:---- |:---------------------------------------------- |
| 200  | Only available for Paid account: {accountId}.  |
| 200  | Not subscribe toll-free audio conference plan. | 
