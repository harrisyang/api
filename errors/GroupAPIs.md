### List groups
https://devdocs.zoom.us/v1.0/reference#groups-1

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}

### Create a group
https://devdocs.zoom.us/v1.0/reference#groupcreate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
4130 | Group not exist:{groupId}
4132 | Group name {groupName} is already in use.

### Retrieve a group
https://devdocs.zoom.us/v1.0/reference#group

code | message
-----|-----
200  | Only available for Paid account,{accountId}
1010 | Group not belong to the account:{0}
4130 | Group not exist:{groupId}

### Update a group
https://devdocs.zoom.us/v1.0/reference#groupupdate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
1010 | Group not belong to the account:{accountId}
4130 | Group not exist:{groupId}
4132 | Group name {groupName} is already in use.

### Delete a group
https://devdocs.zoom.us/v1.0/reference#groupdelete

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}

### List a group’s members
https://devdocs.zoom.us/v1.0/reference#groupmembers

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}

### Add group members
https://devdocs.zoom.us/v1.0/reference#groupmemberscreate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}


### Delete a group member
https://devdocs.zoom.us/v1.0/reference#groupmembersdelete

code | message
-----|-----
200  | Only available for Paid account,{accountId}
1010 | Group not belong to the account:{accountId}
4130 | Group not exist:{groupId}
