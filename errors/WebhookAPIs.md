### Switch webhook version
https://devdocs.zoom.us/v1.0/reference#webhookswitch

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | No permission.                                | 

### List webhooks
https://devdocs.zoom.us/v1.0/reference#webhooks-2

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | Only available for enabled v2 webhooks.       |
| 200  | No permission.                                |

### Create a webhook
https://devdocs.zoom.us/v1.0/reference#webhookcreate

| code | message                                        |
|:---- |:---------------------------------------------- |
| 200  | Only available for enabled developer feature.  |
| 200  | Only available for enabled v2 webhooks.        |
| 200  | No permission.                                 |
| 2202 | Can only add max one webhook under an account. | 

### Retrieve a webhook
https://devdocs.zoom.us/v1.0/reference#webhook

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | Only available for enabled v2 webhooks.       |
| 200  | No permission.                                |
| 2201 | Webhook not exist: {webhookId}.               | 

### Update a webhook
https://devdocs.zoom.us/v1.0/reference#webhookupdate

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | Only available for enabled v2 webhooks.       |
| 200  | No permission.                                |
| 2201 | Webhook not exist: {webhookId}.               | 

### Delete a webhook
https://devdocs.zoom.us/v1.0/reference#webhookdelete

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | Only available for enabled v2 webhooks.       |
| 200  | No permission.                                |
| 2201 | Webhook not exist: {webhookId}.               | 