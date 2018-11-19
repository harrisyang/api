# Webhook APIs

### Switch webhook version
https://marketplace.zoom.us/docs/api-reference/zoom-api/webhooks/webhookswitch

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | No permission.                                | 

### List webhooks
https://marketplace.zoom.us/docs/api-reference/zoom-api/webhooks/webhooks

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | Only available for enabled v2 webhooks.       |
| 200  | No permission.                                |

### Create a webhook
https://marketplace.zoom.us/docs/api-reference/zoom-api/webhooks/webhookcreate

| code | message                                        |
|:---- |:---------------------------------------------- |
| 200  | Only available for enabled developer feature.  |
| 200  | Only available for enabled v2 webhooks.        |
| 200  | No permission.                                 |
| 2202 | Can only add max one webhook under an account. | 

### Retrieve a webhook
https://marketplace.zoom.us/docs/api-reference/zoom-api/webhooks/webhook

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | Only available for enabled v2 webhooks.       |
| 200  | No permission.                                |
| 2201 | Webhook not exist: {webhookId}.               | 

### Update a webhook
https://marketplace.zoom.us/docs/api-reference/zoom-api/webhooks/webhookupdate

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | Only available for enabled v2 webhooks.       |
| 200  | No permission.                                |
| 2201 | Webhook not exist: {webhookId}.               | 

### Delete a webhook
https://marketplace.zoom.us/docs/api-reference/zoom-api/webhooks/webhookdelete

| code | message                                       |
|:---- |:--------------------------------------------- |
| 200  | Only available for enabled developer feature. |
| 200  | Only available for enabled v2 webhooks.       |
| 200  | No permission.                                |
| 2201 | Webhook not exist: {webhookId}.               | 