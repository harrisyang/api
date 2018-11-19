# Group APIs
> Note: All the Group APIs are only for Biz+ accounts or paid accounts.

### List groups
https://marketplace.zoom.us/docs/api-reference/zoom-api/groups/groups

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}

### Create a group
https://marketplace.zoom.us/docs/api-reference/zoom-api/groups/groupcreate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
4130 | Group not exist:{groupId}
4132 | Group name {groupName} is already in use.

### Retrieve a group
https://marketplace.zoom.us/docs/api-reference/zoom-api/groups/group

code | message
-----|-----
200  | Only available for Paid account,{accountId}
1010 | Group not belong to the account:{0}
4130 | Group not exist:{groupId}

### Update a group
https://marketplace.zoom.us/docs/api-reference/zoom-api/groups/groupupdate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
1010 | Group not belong to the account:{accountId}
4130 | Group not exist:{groupId}
4132 | Group name {groupName} is already in use.

### Delete a group
https://marketplace.zoom.us/docs/api-reference/zoom-api/groups/groupdelete

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}

### List a group’s members
https://marketplace.zoom.us/docs/api-reference/zoom-api/groups/groupmembers

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}

### Add group members
https://marketplace.zoom.us/docs/api-reference/zoom-api/groups/groupmemberscreate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}


### Delete a group member
https://marketplace.zoom.us/docs/api-reference/zoom-api/groups/groupmembersdelete

code | message
-----|-----
200  | Only available for Paid account,{accountId}
1010 | Group not belong to the account:{accountId}
4130 | Group not exist:{groupId}
