### List all the recordings
https://devdocs.zoom.us/v1.0/reference#recordingslist

code | message
-----|-----
300  | The next page token is invalid or expired.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}

### Retrieve a meeting’s all recordings
https://devdocs.zoom.us/v1.0/reference#recordingget

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting

### Delete a meeting’s recordings
https://devdocs.zoom.us/v1.0/reference#recordingdelete

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting
3301 | Recording file does not exist

### Delete one meeting recording file
https://devdocs.zoom.us/v1.0/reference#recordingdeleteone

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting
3303 | Can not delete a uncompleted recording
3301 | Recording file does not exist

### Recover a meeting’s recordings.
https://devdocs.zoom.us/v1.0/reference#recordingstatusupdate

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting
3301 | Recording file does not exist

### Recover a single recording
https://devdocs.zoom.us/v1.0/reference#recordingstatusupdateone

code | message
-----|-----
200  | No permission.
1001 | User not exist:{userId}
1010 | User not belong to this account:{accountId}
3301 | There is no recording for this meeting
3301 | Recording file does not exist