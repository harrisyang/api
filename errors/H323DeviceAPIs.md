# H323Device APIs
> Note: All the H323Device APIs requires the account to be subscribed to H.323/SIP Room Connector plans.

### List H.323/SIP Devices.
https://marketplace.zoom.us/docs/api-reference/zoom-api/devices/devicelist

| code | Message        |
|:---- |:-------------- |
| 200  | No permission. | 

### Create a H.323/SIP Device
https://marketplace.zoom.us/docs/api-reference/zoom-api/devices/devicecreate

| code | Message                                                    |
|:---- |:---------------------------------------------------------- |
| 200  | No permission.                                             |
| 2020 | H.323 device display name:{displayName} is already in use. | 

### Update a H.323/SIP Device
https://marketplace.zoom.us/docs/api-reference/zoom-api/devices/deviceupdate

| code | Message                                                    |
|:---- |:---------------------------------------------------------- |
| 200  | No permission.                                             |
| 300  | H.323 Device not exist: " + deviceId                       | 
| 2020 | H.323 device display name:{displayName} is already in use. |

### Delete a H.323/SIP Device
https://marketplace.zoom.us/docs/api-reference/zoom-api/devices/devicedelete

| code | Message                              |
|:---- |:------------------------------------ |
| 200  | No permission.                       | 
| 300  | H.323 Device not exist: " + deviceId |

