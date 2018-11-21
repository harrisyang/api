### List meetings
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meetings

code | message
-----|----- 
1001 | User not exist: {userId}  
1001 | Meeting host not exist: {userId}
1001 | User {email} not exist or not belong to this account.
1010 | User not belong to this account: {accountId}

### Create a meeting
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meetingcreate

code | message
-----|-----
300  | Invalid enforce_login_domains, please separate multiple domains by semicolon
1001 | User not exist: {userId}  
1001 | Meeting host not exist: {userId}
1010 | User not belong to this account:{accountId}

### Retrieve a meeting
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meeting

code | message
-----|-----
1001 | User not exist: {userId}  
1010 | User not belong to this account: {accountId}
3001 | Meeting {meetingId} is not found or has expired.
3000 | Cannot access webinar info.

### Update a meeting
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meetingupdate

code | message
-----|-----
300  | Invalid enforce_login_domains, please separate multiple domains by semicolon
1001 | User not exist: {userId}  
1010 | User not belong to this account:{accountId}
3000 | Cannot access webinar info.
3001 | Meeting {meetingId} is not found or has expired.
3003 | Not meeting host.

### Delete a meeting
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meetingdelete

code | message
-----|-----
300  | Meeting {meetingId} is not found or has expired.
1001 | User not exist: {userId}  
1010 | User not belong to this account: {accountId}
3000 | Cannot access webinar info.
3000 | Invalid occurrence_id.
3002 | Sorry, you cannot delete this meeting since it's in progress.
3003 | Not meeting host.
3007 | Sorry, you cannot delete this meeting since it's ended.
3018 | Not allow to delete PMI.
3037 | Not allow to delete PAC.

### Update a meeting’s status
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meetingstatus

code | message
-----|-----
300  | Meeting {meetingId} is not found or has expired.
1001 | User not exist: {userId}  
1010 | User not belong to this account:{accountId}
3003 | Not meeting host.
3000 | Cannot access webinar info.
3063 | Can not end on-premise user's meeting: {meetingId}


### List a meeting’s registrants
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meetingregistrants

code | message
-----|-----
300  | Meeting {meetingId} is not found or has expired.
300  | This meeting has not registration required: {meetingId}.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3000 | Cannot access webinar info.
3003 | Not meeting host.

### Add a meeting registrant
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meetingregistrantcreate

code | message
-----|-----
300  | Meeting {meetingId} is not found or has expired.
404  | This meeting has not registration required: {meetingId}.
1001 | User not exist: {userId}.
1001 | The email address has not been used as a Zoom account.
1010 | User not belong to this account:{accountId}.
200  | Only available for Paid user: {userId}.
3000 | Cannot access webinar info.
3003 | Not meeting host.
3051 | If you have been invited, please input your work email address

### Update a meeting registrant’s status
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/meetingregistrantstatus

code | message
-----|-----
300  | Meeting {meetingId} is not found or has expired.
300  | This meeting has not registration required:{meetingId}.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3000 | Cannot access webinar info.
3003 | Not meeting host.

### Retrieve past meeting details
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/pastmeetingdetails

code | message
-----|-----
200  | No permission.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3001 | Meeting ID is invalid or not end.
3001 | This meeting is not available or ID is not valid.
3000 | Cannot access webinar info.


### Retrieve past meeting participants
https://marketplace.zoom.us/docs/api-reference/zoom-api/meetings/pastmeetingparticipants

code | message
-----|-----
200  | No permission.
200  | Only available for Paid user: {userId}.
300  | The next page token is invalid or expired.
1001 | User not exist: {userId}.
1010 | User not belong to this account:{accountId}.
3000 | Cannot access webinar info.
3001 | Meeting ID is invalid or not end.
3001 | This meeting is not available or ID is not valid.
