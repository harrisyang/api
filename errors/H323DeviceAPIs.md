### List H.323/SIP Devices.
https://devdocs.zoom.us/v1.0/reference#devicelist

| code | Message        |
|:---- |:-------------- |
| 200  | No permission. | 

### Create a H.323/SIP Device
https://devdocs.zoom.us/v1.0/reference#devicecreate

| code | Message                                                    |
|:---- |:---------------------------------------------------------- |
| 200  | No permission.                                             |
| 2020 | H.323 device display name:{displayName} is already in use. | 

### Update a H.323/SIP Device
https://devdocs.zoom.us/v1.0/reference#deviceupdate

| code | Message                                                    |
|:---- |:---------------------------------------------------------- |
| 200  | No permission.                                             |
| 300  | H.323 Device not exist: " + deviceId                       | 
| 2020 | H.323 device display name:{displayName} is already in use. |

### Delete a H.323/SIP Device
https://devdocs.zoom.us/v1.0/reference#devicedelete

| code | Message                              |
|:---- |:------------------------------------ |
| 200  | No permission.                       | 
| 300  | H.323 Device not exist: " + deviceId |

