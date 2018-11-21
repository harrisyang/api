# IMGroup APIs
> Note: All the IMGroup APIs are only for Biz+ accounts or paid accounts.

### List IM Groups
https://marketplace.zoom.us/docs/api-reference/zoom-api/im-groups/imgroups

code | message
-----|-----
200  | Only available for Paid account,{accountId}
4130 | Group not exist:{groupId}

### Create an IM Group
https://marketplace.zoom.us/docs/api-reference/zoom-api/im-groups/imgroupcreate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
4130 | Group not exist:{groupId}
4132 | Group name {groupName} is already in use.

### Retrieve an IM Group
https://marketplace.zoom.us/docs/api-reference/zoom-api/im-groups/imgroup

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
4130 | IM Group not exist:{groupId}

### Update an IM Group
https://marketplace.zoom.us/docs/api-reference/zoom-api/im-groups/imgroupupdate

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
4130 | IM Group not exist:{groupId}

### Delete an IM Group
https://marketplace.zoom.us/docs/api-reference/zoom-api/im-groups/imgroupdelete

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
300  | Can not delete account default group,{groupId}
4130 | Group not exist:{groupId}

### List an IM Group’s members
https://marketplace.zoom.us/docs/api-reference/zoom-api/im-groups/imgroupmembers

code | message
-----|-----
300  | Missing field: name
200  | Only available for Paid account,{accountId}

### Add IM Group members
https://marketplace.zoom.us/docs/api-reference/zoom-api/im-groups/imgroupmemberscreate

code | message
-----|-----
300  | Missing field: name
200  | Only available for Paid account,{accountId}

### Delete an IM Group member
https://marketplace.zoom.us/docs/api-reference/zoom-api/im-groups/imgroupmembersdelete

code | message
-----|-----
200  | Only available for Paid account,{accountId}
300  | Missing field: name
300  | Can not delete account default group,{groupId}
4130 | Group not exist:{groupId}