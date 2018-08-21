### List IM Groups
https://devdocs.zoom.us/v1.0/reference#imgroups

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}

### Create an IM Group
https://devdocs.zoom.us/v1.0/reference#imgroupcreate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
4130 | Group not exist:{groupId}
4132 | Group name {groupName} is already in use.

### Retrieve an IM Group
https://devdocs.zoom.us/v1.0/reference#imgroup

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
4130 | IM Group not exist:{groupId}

### Update an IM Group
https://devdocs.zoom.us/v1.0/reference#imgroupupdate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
4130 | IM Group not exist:{groupId}

### Delete an IM Group
https://devdocs.zoom.us/v1.0/reference#imgroupdelete

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
300  | Can not delete account default group,{groupId}
4130 | Group not exist:{groupId}

### List an IM Group’s members
https://devdocs.zoom.us/v1.0/reference#imgroupmembers

code | message
-----|-----
300  | Missing field: name
200  | Only available for Paid account,{accountId}

### Add IM Group members
https://devdocs.zoom.us/v1.0/reference#imgroupmemberscreate

code | message
-----|-----
300  | Missing field: name
200  | Only available for Paid account,{accountId}

### Delete an IM Group member
https://devdocs.zoom.us/v1.0/reference#imgroupmembersdelete

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
300  | Can not delete account default group,{groupId}
4130 | Group not exist:{groupId}