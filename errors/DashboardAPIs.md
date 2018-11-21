# Dashboard APIs
> Note: All the Dashboard APIs are only for Biz+ accounts or paid accounts with Dashboard feature.

### List meetings
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardmeetings

| code | message                                                        |
|:---- |:-------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature. |
| 300  | The next page token is invalid or expired.                     | 

### Retrieve meeting detail
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardmeetingdetail

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | Can not access webinar info, {meetingId}.                        | 
| 3001 | Meeting ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### Retrieve meeting participants
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardmeetingparticipants

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | The next page token is invalid or expired.                       |
| 300  | Can not access webinar info, {meetingId}.                        | 
| 3001 | Meeting ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### Retrieve meeting participant QOS
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardmeetingparticipantqos

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | Can not access webinar info, {meetingId}.                        | 
| 3001 | Meeting ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |


### List meeting participants QOS
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardmeetingparticipantsqos

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | Can not access webinar info, {meetingId}.                        |
| 300  | The next page token is invalid or expired.                       |
| 3001 | Meeting ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### Retrieve sharing/recording details of meeting participant
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardmeetingparticipantshare

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | Can not access webinar info, {meetingId}.                        |
| 300  | The next page token is invalid or expired.                       |
| 3001 | Meeting ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### List webinars
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardwebinars

| code | message                                                        |
|:---- |:-------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature. |
| 300  | The next page token is invalid or expired.                     | 

### Retrieve webinar detail
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardwebinardetail

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | Can not access meeting info, {webinarId}.                        | 
| 3001 | Webinar ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### Retrieve webinar participants
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardwebinarparticipants

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | The next page token is invalid or expired.                       |
| 300  | Can not access meeting info, {webinarId}.                        | 
| 3001 | Webinar ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### Retrieve webinar participant QOS
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardwebinarparticipantqos

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | Can not access meeting info, {webinarId}.                        | 
| 3001 | Webinar ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### List webinar participant QOS
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardwebinarparticipantsqos

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | Can not access meeting info, {webinarId}.                        | 
| 300  | The next page token is invalid or expired.                       |
| 3001 | Webinar ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### Retrieve sharing/recording details of webinar participant
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardwebinarparticipantshare

| code | message                                                          |
|:---- |:---------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature.   |
| 300  | Can not access meeting info, {webinarId}.                        | 
| 300  | The next page token is invalid or expired.                       |
| 3001 | Webinar ID is invalid or not end.                                |
| 3001 | This meeting's details info is not available or ID is not valid. |

### List Zoom Rooms
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardzoomrooms

| code | message                                                        |
|:---- |:-------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature. |

### Retrieve Zoom Room
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardzoomroom

| code | message                                                        |
|:---- |:-------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature. |
| 300  | The next page token is invalid or expired.                     | 

### Retrieve CRC Port Usage
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardcrc

| code | message                                                        |
|:---- |:-------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature. |

### Retrieve IM
https://marketplace.zoom.us/docs/api-reference/zoom-api/dashboards/dashboardim

| code | message                                                        |
|:---- |:-------------------------------------------------------------- |
| 200  | Only available for paid account and enabled Dashboard feature. |