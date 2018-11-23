# User APIs
> Note: All the User APIs are only for paid accounts.

### List Users
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/users

### Create a user
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/usercreate

| code | Message                                                                                                    |
|:---- |:---------------------------------------------------------------------------------------------------------- |
| 200  | No privilege.                                                                                              |
| 200  | You can add max {maxNumber} free users.                                                                    |
| 200  | You can't add paid users.                                                                                  |
| 200  | You can add max {maxNumber} paid users.                                                                    |
| 200  | No permission, please contact Zoom customer support.                                                       |
| 300  | Invalid parameter: password                                                                                |
| 1000 | The user cannot be changed because s/he is a Call-queue manager or Auto-receptionist operator.             |
| 1005 | Email {email} has already been used.                                                                       |
| 1107 | Email domain is blocked                                                                                    |
| 1116 | Email address {email} doesn't match limited domains: {domains}                                             |
| 1108 | User type permission check failed.                                                                         |
| 1009 | The user {email} already holds an active account.                                                          | 
| 1135 | New User already exists in another cluster, current don't support add another cluster user, email: {email} |
| 2002 | Only available for Enabled Pre-provisioning SSO Partners                                                   |
| 4130 | Group not exist: {groupId}                                                                                 |
| 4130 | IM Group not exist: {imGroupId}                                                                            |

### Retrieve a user
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/user

| code | Message                                       |
|:---- |:--------------------------------------------- |
| 1001 | User not exist or not belong to this account. | 
| 1120 | Invite not exist                              |

### Update a user
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userupdate

| code | Message                                                                                             |
|:---- |:--------------------------------------------------------------------------------------------------- |
| 200  | You can't add paid users.                                                                           |
| 200  | You can add max {maxNumber} paid users.                                                             |
| 200  | Cannot update Room user to free: {userId}                                                           |
| 300  | User cannot update host key. There is a started meeting.                                            |
| 300  | Host key cannot be same as personal audio conference password.                                      |
| 1010 | User not exist or not belong to this account                                                        |
| 1108 | User type permission check failed: {userId}                                                         |
| 1108 | Only paid user can own host key.                                                                    |
| 1109 | Host is not Paid user.                                                                              |
| 1120 | Invite not exist                                                                                    |
| 4100 | User is already taken by a user from your account. Choose another Personal Link Name and try again. |
| 4100 | User is already taken. Choose another Personal Link Name and try again.                             | 

### Delete a user
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userdelete

| code | Message                                                                                           |
|:---- |:------------------------------------------------------------------------------------------------- |
| 200  | Cannot delete a user out of your account                                                          | 
| 200  | Cannot delete a Zoom Rooms user.                                                                  |
| 200  | Can not transfer to a Zoom Rooms user.                                                            |
| 300  | The transfer-to email address cannot be the same as the unlinked or deleted user's email address. |
| 1000 | The user cannot be deleted because s/he is a Call-queue manager or Auto-receptionist operator.    |
| 1001 | Destination user is not belongs to the same account.                                              |
| 1010 | User not exist or not belong to this account                                                      |
| 1107 | Can not disassociate the user with managed domain                                                 |
| 1117 | Can not disassociate Admin user                                                                   |
| 1120 | Invite not exist                                                                                  |

### List a user's assistants
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userassistants

| code | Message                         |
|:---- |:------------------------------- |
| 1001 | User not exist.                 |
| 1010 | User not belong to this account | 

### Add assistants
> Note: User must be a Pro or Corp user

https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userassistantcreate

| code | Message                                                    |
|:---- |:---------------------------------------------------------- |
| 200  | Current account must be paid account: {userId}             |
| 200  | User must be a Pro or Corp user: {userId}                  |
| 200  | Can't assign scheduling privilege to yourself.             |
| 200  | Can't find user {email}.                                   |
| 200  | User {email} already has the scheduling privilege for you. |
| 200  | User {email} doesn't belong to current account.            |
| 200  | User {email} must be a Pro or Corp user.                   | 
| 1001 | User not exist.                                            |
| 1010 | User not belong to this account                            |

### Delete a user's assistants
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userassistantsdelete

| code | Message                         |
|:---- |:------------------------------- |
| 1001 | User not exist.                 |
| 1010 | User not belong to this account | 

### Delete a user's assistant
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userassistantdelete

| code | Message                         |
|:---- |:------------------------------- |
| 1001 | User not exist.                 |
| 1010 | User not belong to this account | 

### List a user's schedulers
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userschedulers

| code | Message                         |
|:---- |:------------------------------- |
| 1001 | User not exist.                 |
| 1010 | User not belong to this account | 

### Delete a user's schedulers
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userschedulersdelete

| code | Message                         |
|:---- |:------------------------------- |
| 1001 | User not exist.                 |
| 1010 | User not belong to this account | 


### Delete a user's scheduler
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userschedulerdelete

| code | Message                         |
|:---- |:------------------------------- |
| 1001 | User not exist.                 |
| 1010 | User not belong to this account | 

### Upload a user's picture
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userpicture

| code | Message                                               |
|:---- |:----------------------------------------------------- |
| 120  | File is empty                                         |
| 120  | File size cannot exceed 2M                            | 
| 120  | Only jpg/jpeg, gif or png image file can be uploaded. |
| 1001 | User not exist.                                       |
| 1010 | User not belong to this account                       |

### Retrieve a user's settings
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/usersettings

| code | Message                                       |
|:---- |:--------------------------------------------- |
| 1001 | User not exist or not belong to this account. |
| 1010 | User not belong to this account               |
| 1120 | Invite not exist                              |
| 1000 | Can not access pending user settings.         | 

### Update a user's settings
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/usersettingsupdate

| code | Message                                           |
|:---- |:------------------------------------------------- |
| 200  | You can add max {maxNumber} free users.           |
| 200  | You can add max {maxNumber} Webinar 100 users.    |
| 200  | You can add max {maxNumber} Webinar 500 users.    |
| 200  | You can add max {maxNumber} Webinar 1000 users.   |
| 200  | You can add max {maxNumber} Webinar 3000 users.   |
| 200  | You can add max {maxNumber} Webinar 5000 users.   |
| 200  | You can add max {maxNumber} Webinar 10000 users. | 
| 200  | You can add max {maxNumber} Large 200 users.      |
| 200  | You can add max {maxNumber} Large 100 users.      |
| 200  | You can add max {maxNumber} Large 300 users.      |
| 200  | You can add max {maxNumber} Large 500 users.      |
| 200  | You can add max {maxNumber} Large 1000 users.     |
| 200  | You can't add paid users.                         |
| 200  | You can add max {0} paid users.                   |
| 1010 | User not exist or not belong to this account      |
| 1120 | Invite not exist                                  |
| 1122 | Only Pro or Corp user can enable Webinar feature. |

### Update a user's status
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userstatus

| code | Message                                                           |
|:---- |:----------------------------------------------------------------- |
| 200  | Zoom Room and Admin users can not be activated or deactivated.    |
| 1000 | This user is force locked. Contact the Zoom Support Team for help |
| 1010 | User not exist or not belong to this account: {userId}            | 

### Update a user's password
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userpassword

| code | Message                                                              |
|:---- |:-------------------------------------------------------------------- |
| 300  | Your new password can not match the old password.                    |
| 1010 | User not exist or not belong to this account                         |
| 1117 | Can not update Admin's password                                      |
| 1123 | Can only update password of Zoom work email account                  |
| 1124 | Minimum of 6 characters.                                             | 
| 1124 | Have at least {number} characters                                    |
| 1125 | Have at least 1 letter (a, b, c...)                                  |
| 1126 | Have at least 1 number (1, 2, 3...)                                  |
| 1127 | Have at least 1 special character (!, @, #...)                       |
| 1128 | Include both Upper case and Lower case characters                    |
| 1130 | Password can't use the same character.                               |
| 1131 | Password can't use continuation character.Such as 'abcdef','123456'. |
| 1136 | Your password is too easy to guess. Try another one.                 |

### Retrieve a user's permissions
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userpermission

| code | Message                         |
|:---- |:------------------------------- |
| 1001 | User not exist.                 |
| 1010 | User not belong to this account | 

### Retrieve a user's token
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/usertoken

| code | Message                         |
|:---- |:------------------------------- |
| 1001 | User not exist.                 |
| 1010 | User not belong to this account | 

### Revoke a user's SSO token
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/userssotokendelete


### Check a user's email
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/useremail

| code | Message            |
|:---- |:------------------ |
| 300  | Email is required. | 

### Check a user's personal meeting room name
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/uservanityname

| code | Message                  |
|:---- |:------------------------ |
| 300  | Vanity name is required. | 

### Change a user's email
https://marketplace.zoom.us/docs/api-reference/zoom-api/users/useremailupdate

| code | Message                                                                                                                 |
|:---- |:----------------------------------------------------------------------------------------------------------------------- |
| 1000 | Pending user can not change email.                                                                                      |
| 1000 | Can not change email of account owner.                                                                                  |
| 1000 | This user is force locked. Contact the Zoom Support Team for help                                                       |
| 1000 | This user is locked or inactive.                                                                                        | 
| 1107 | Email domain is blocked                                                                                                 |
| 1010 | User not exist or not belong to this account                                                                            |
| 1116 | Domain name doesn't match, please contact Zoom customer support to set managed domains for your account                 |
