### List all the recordings
https://marketplace.zoom.us/docs/api-reference/zoom-api/cloud-recording/recordingslist

code | message
-----|-----
300  | The next page token is invalid or expired.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}

### Retrieve a meeting’s all recordings
https://marketplace.zoom.us/docs/api-reference/zoom-api/cloud-recording/recordingget

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting

### Delete a meeting’s recordings
https://marketplace.zoom.us/docs/api-reference/zoom-api/cloud-recording/recordingdelete

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting
3301 | Recording file does not exist

### Delete one meeting recording file
https://marketplace.zoom.us/docs/api-reference/zoom-api/cloud-recording/recordingdeleteone

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting
3303 | Can not delete a uncompleted recording
3301 | Recording file does not exist

### Recover a meeting’s recordings.
https://marketplace.zoom.us/docs/api-reference/zoom-api/cloud-recording/recordingstatusupdate

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting
3301 | Recording file does not exist

### Recover a single recording
https://marketplace.zoom.us/docs/api-reference/zoom-api/cloud-recording/recordingstatusupdateone

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting
3301 | Recording file does not exist