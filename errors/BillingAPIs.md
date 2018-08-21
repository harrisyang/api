### Retrieve billing information for a sub account
https://devdocs.zoom.us/v1.0/reference#billing

| code | message                                                                | 
|:---- |:---------------------------------------------------------------------  |
| 200  | Master need to create a billing account.                               |
| 2001 | This account does not exist or does not belong to you: {subAccountId}. |
| 2100 | This sub account is paid by self.                                      |
| 3201 | Cannot find billing account info. Zoom account number:{accountNumber}. |
| 3211 | There is no contact for contact id: {contactId}.                       |

### Update billing information for a sub account
https://devdocs.zoom.us/v1.0/reference#accountbillingupdate

| code | message                                                                |
|:---- |:---------------------------------------------------------------------- |
| 200  | Please subscribe a plan for this sub account firstly.                  |
| 2001 | This account does not exist or does not belong to you: {subAccountId}. |
| 2100 | This sub account is paid by self.                                      |
| 2100 | Invalid country parameter: {country}.                                |
| 2100 | Invalid state parameter: {state}.                                    |
| 3201 | Cannot find the billing account with the accountID: {accountId}.       | 
| 3211 | Cannot find the soldToContact with the accountID: {accountId}.         |

### Retrieve plan information for a sub account
https://devdocs.zoom.us/v1.0/reference#accountplans

| code | message                                                                | 
|:---- |:---------------------------------------------------------------------  | 
| 200  | Master need to create a billing account.                               |  
| 2001 | This account does not exist or does not belong to you: {subAccountId}. |    
| 2100 | This sub account is paid by self.                                      |    

### Subscribe plans for a sub account
https://devdocs.zoom.us/v1.0/reference#accountplancreate

| code | message                                                                                                                               |
|:---- |:------------------------------------------------------------------------------------------------------------------------------------- |
| 300  | Invalid free trial start/end time.                                                                                                    |
| 300  | Too less hosts for business plan type.                                                                                                |
| 300  | Too less hosts for education plan type.                                                                                               |
| 2001 | This account does not exist or does not belong to you: {subAccountId}                                                                 |
| 2010 | Plan Not Exist: {planCode}.                                                                                                           |
| 2100 | Invalid Sold To Contact Info: {subAccountId}.                                                                                         |
| 2100 | Invalid parameter: first_name                                                                                                         |
| 2100 | Invalid parameter: last_name                                                                                                          |
| 2100 | Invalid parameter: email                                                                                                              |
| 2100 | Invalid parameter: country                                                                                                            |
| 2100 | Invalid parameter: city                                                                                                               |
| 2100 | Invalid parameter: phone_number                                                                                                       |
| 2100 | Invalid parameter: state                                                                                                              |
| 2100 | Invalid parameter: zip                                                                                                                |
| 2100 | Invalid Base Plan: {subAccountId}                                                                                                     |
| 2100 | Invalid Base Plan: {basePlanCode}                                                                                                     | 
| 2100 | Cannot add plan for sub account which is paid by self.                                                                                |
| 2100 | Cannot enable free trial again for sub account.                                                                                       |
| 2100 | You cannot add a sub account because your master account owner prevented you from adding one.                                         |
| 2100 | Cannot add plan for sub account which is not free plan.                                                                               |
| 2100 | Invalid country parameter: {country}                                                                                                  |
| 2100 | Invalid state parameter: {state}                                                                                                      |
| 2100 | Invalid Zoom Rooms Plan: {planCode}                                                                                                   |
| 2100 | Invalid Room Connector Plan: {planCode}                                                                                               |
| 2100 | Duplicate Webinar Plan: {planType}                                                                                                    |
| 2100 | Invalid Webinar Plan: {planType}                                                                                                      |
| 2100 | Invalid Cloud Recording Plan: {plan_recording}                                                                                        |
| 2100 | Invalid Audio Conferencing Plan: {planCode}                                                                                           |
| 2100 | Can not subscribe/update Additional Audio Conferencing Pay As You Go Plan for a sub account which base plan is not Business/Education |
| 2100 | Need at least one option from among the Toll-free, Premium and Call-out.                                                              |
| 2100 | Cannot support this plan type: {planType}                                                                                             |
| 3261 | Must subscribe to a major plan first.                                                                                                 |

### Update a base plan for a sub account
https://devdocs.zoom.us/v1.0/reference#accountplanbaseupdate

| code | message                                                                                                                               |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 200  | Free trial and VIP account can't update sub plan.                                                                                     |
| 300  | Too less hosts for business plan type.                                                                                                |
| 300  | Too less hosts for education plan type.                                                                                               |
| 200  | You don't have subscription yet.                                                                                                      |
| 300  | Plan type not match, oldPlanType: {oldPlanType} newPlanType: {newPlanType}                                                            |
| 2001 | This account does not exist or does not belong to you: {subAccountId}                                                                 |
| 2001 | This account does not exist or does not belong to this master account: {subAccountId}                                                 |
| 2010 | Plan Not Exist: {planCode}                                                                                                            |
| 2100 | Invalid Zoom Rooms Plan: {planCode}                                                                                                   |
| 2100 | Invalid Room Connector Plan: {planCode}                                                                                               | 
| 2100 | This sub account is paid by self                                                                                                      |
| 2100 | Invalid Additional Plan Type: {newPlanCode}                                                                                           |
| 2100 | Duplicate Large Meeting Plan: {planType}                                                                                              |
| 2100 | Invalid Large Meeting Plan: {planType}                                                                                                |
| 2100 | Duplicate Webinar Plan: {planType}                                                                                                    |
| 2100 | Invalid Webinar Plan: {planType}                                                                                                      |
| 2100 | Invalid Cloud Recording Plan: {plan_recording}                                                                                        |
| 2100 | Invalid Audio Conferencing Plan: {planCode}                                                                                           |
| 2100 | Can not subscribe/update Additional Audio Conferencing Pay As You Go Plan for a sub account which base plan is not Business/Education |
| 2100 | Need at least one option from among the Toll-free, Premium and Call-out.                                                              |
| 2100 | You Major plan host count should be larger than Webinar host count.                                                                   |
| 2100 | You Major plan host count should be larger than Large100 host count.                                                                  |
| 2100 | Cannot support this plan type: {planType}                                                                                             |
| 2100 | Invalid Base Plan Type: {newPlanCode}                                                                                                 |
| 2100 | Account type is not free trial.                                                                                                       |
| 2100 | The account currently have %d Paid users, you should reduce this number firstly.                                                      |
| 2100 | Cannot update plan for sub account which is free plan.                                                                                |
| 2100 | Cannot update Pro plan for sub account which is not Pro/Business/Zoom Rooms Plan.                                                     |
| 2100 | Cannot update Business plan for sub account which is not Pro or Business Plan.                                                        |
| 2100 | Cannot update Education plan for sub account which is not Education Plan.                                                             |
| 2100 | Cannot update Zoom Rooms plan for sub account which is not Zoom Rooms Plan.                                                           |
| 3261 | Failed to change sub plan of account:{accountId}                                                                                      |

### Add an additional plan for sub account
https://devdocs.zoom.us/v1.0/reference#accountplanaddoncreate

| code | message                                                                                                                               |     |
|:---- |:------------------------------------------------------------------------------------------------------------------------------------- | --- |
| 200  | You don't have subscription  yet.                                                                                                     |     |
| 200  | Free trial and VIP account can't update sub plan.                                                                                     |     |
| 200  | You can't buy additional plan by yourself, as your major plan is charged by check, please contact sales@zoom.us.                      |     |
| 2001 | This account does not exist or does not belong to you: {subAccountId}                                                                 |     |
| 2100 | Invalid Additional Plan Type: {newPlanCode}                                                                                           |     |
| 2100 | This sub account is paid by self.                                                                                                     |     |
| 2100 | Cannot update Additional plan for sub account which is free plan.                                                                     |     |
| 2100 | Cannot Add Additional Zoom Rooms plan for sub account which Base Plan is Zoom Rooms Plan.                                             |     |
| 2100 | This sub account already has the additional plan: {oldAddonPlanCode}                                                                  |     |
| 2100 | Can not subscribe/update Additional Audio Conferencing Pay As You Go Plan for a sub account which base plan is not Business/Education |     |
| 2100 | Need at least one option from among the Toll-free, Premium and Call-out.                                                              |     |
| 3261 | Must subscribe to a major plan first.                                                                                                 |     |
| 3261 | Failed to change sub plan of account: {accountId}                                                                                     |     |

### Update an additional plan for sub account
https://devdocs.zoom.us/v1.0/reference#accountplanaddonupdate

| code | message                                                                                                                               |     |
|:---- |:------------------------------------------------------------------------------------------------------------------------------------- | --- |
| 200  | Free trial and VIP account can't update sub plan.                                                                                     |     |
| 300  | Plan type not match, oldPlanType: {oldPlanType} newPlanType: {newPlanType}                                                            |     |
| 2001 | This account does not exist or does not belong to you: {subAccountId}                                                                 |     |
| 2100 | This sub account is paid by self.                                                                                                     |     |
| 2100 | Invalid Additional Plan Type: {newPlanCode}                                                                                           |     |
| 2100 | Can not subscribe/update Additional Audio Conferencing Pay As You Go Plan for a sub account which base plan is not Business/Education |     |
| 2100 | Need at least one option from among the Toll-free, Premium and Call-out.                                                              |     |
| 2100 | Cannot update Additional plan for sub account which is free plan.                                                                     |     |
| 2100 | Cannot update Additional Zoom Rooms plan for sub account which Base Plan is Zoom Rooms Plan.                                          |     |
| 2100 | This sub account don't have the additional plan: {newPlanCode}                                                                        |     |
| 3261 | Failed to change sub plan of account: {accountId}                                                                                     |     |
| 3261 | Must subscribe to a major plan first.                                                                                                 |     |