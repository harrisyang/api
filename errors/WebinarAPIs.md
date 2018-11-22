# Webinar APIs
> Note: All the Webinar APIs are only for Biz+ accounts or paid accounts and subscribe webinar plan.

### List webinars
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinars

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.

### Create a webinar
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarcreate

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid recurrence settings.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.

### Retrieve a webinar
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinar

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
3001 | Webinar {webinarId} not found or expired.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.

### Update a webinar
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarupdate

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
300  | Invalid recurrence settings.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.
3003 | Not meeting host.

### Delete a webinar
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinardelete

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3000 | Invalid occurrence_id:{meetingId}.
3001 | Webinar {webinarId} not found or expired.
3002 | Sorry, you cannot delete this meeting since it's in progress.
3003 | Not meeting host.
3007 | Sorry, you cannot delete this meeting since it's ended.
3018 | Not allow to delete PMI.
3037 | Not allow to delete PAC.

### Update a webinar’s status
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarstatus

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.
3003 | Not meeting host.
3063 | Can not end on-premise user's meeting:{meetingId}.

### List a webinar’s panelists
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarpanelists

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.

### Add a webinar panelist
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarpanelistcreate

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.

### Remove a webinar’s panelists
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarpanelistsdelete

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.


### Remove a webinar panelist
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarpanelistdelete

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.

### List a webinar’s registrants
> Note: Should set registration required.

https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarregistrants

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.

### Add a webinar registrant
> Note: Should set registration required.

https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarregistrantcreate

code | message
-----|-----
300  | Invalid webinarId.
300  | Invalid parameter: occurrence_ids
300  | Invalid user name.
1001 | The email address has not been used as a Zoom account
3000 | This Webinar has not registration required:{meetingId}.
3001 | Webinar {webinarId} not found or expired.
3027 | Host can not register
3034 | If you have been invited, please input your work email address
3038 | Webinar is over, you can not register now. If you have any questions, please contact Webinar host.

### Update a webinar registrant’s status
> Note: Should set registration required.

https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/webinarregistrantstatus

code | message
-----|-----
200  | Cannot use webinar API, You need to subscribe webinar plan and then enable webinar for this user:{userId}.
300  | Invalid webinarId.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Webinar {webinarId} not found or expired.
3035 | Webinar has reached maximum attendee capacity.

### List of ended webinar instances
https://marketplace.zoom.us/docs/api-reference/zoom-api/webinars/pastwebinars

code | message
-----|-----
300  | Invalid webinarId.