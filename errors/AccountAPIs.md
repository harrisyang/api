# Account APIs
> Note: All the Account APIs are only for master accounts.

### Create a sub account 
https://marketplace.zoom.us/docs/api-reference/zoom-api/accounts/accountcreate

| code | message                               |
|:---- |:------------------------------------- |
| 1005 | Email {email} has already been used.  |
| 1111 | Password can't use the same character | 


### Update a sub account's options 
https://marketplace.zoom.us/docs/api-reference/zoom-api/accounts/accountoptionsupdate

| code | message                                                                 |
|:---- |:----------------------------------------------------------------------- |
| 200  | Sub account has plan already, you can't change pay mode.                |
| 2001 | This account does not exist or does not belong to you: {subAccountId}   |
| 2100 | The collection method cannot be changed after the purchase is complete. | 

### Retrieve a sub account
https://marketplace.zoom.us/docs/api-reference/zoom-api/accounts/account

| code | message                                                                |
|:---- |:---------------------------------------------------------------------  |
| 2001 | This account does not exist or does not belong to you: {subAccountId}. | 


### Disassociate an account 
https://marketplace.zoom.us/docs/api-reference/zoom-api/accounts/accountdisassociate

| code | message                             |
|:---- |:----------------------------------- |
| 2000 | Cannot disassociate a paid account. | 

### Retrieve a sub account's settings
> Note: Only available for Paid account.

https://marketplace.zoom.us/docs/api-reference/zoom-api/accounts/accountsettings

| code | message                                                                |
|:---- |:---------------------------------------------------------------------  |
| 200  | Only available for Paid account.                                       |
| 2001 | This account does not exist or does not belong to you: {subAccountId}. | 



### Update a sub account's settings
> Note: Only available for Paid account.

https://marketplace.zoom.us/docs/api-reference/zoom-api/accounts/accountsettingsupdate

| code | message                                                                |
|:---- |:---------------------------------------------------------------------  |
| 200  | Only available for Paid account.                                       |
| 300  | Invalid domains, please separate multiple domains by semicolon.        |
| 2001 | This account does not exist or does not belong to you: {subAccountId}. | 


