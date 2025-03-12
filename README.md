# AWS Cost Anomaly Monitoring by teams

Apply CIS Benckmark on AWS

What this Template does:

     * Create a Lambda who send messages to MS Teams always that cost anomaly detection trigger a SNS;



Cis-Benchmark on AWS using Cloudformation.


## Requirements

1 - SNS ARN

2 - TEAMS Webhook


Create Incoming Webhooks
To add an Incoming Webhook to a Teams channel, follow these steps:

Open the channel in which you want to add the webhook and select ••• from the upper-right corner.
Select Connectors from the dropdown menu.

![image](https://github.com/user-attachments/assets/62ff47a4-2b2b-4568-b293-7f42e358da33)

 Search for Incoming Webhook and select Add.

4. Select Configure, provide a name, and upload an image for your webhook if necessary.

![image](https://github.com/user-attachments/assets/0cb22c5b-fb5f-4464-855e-368cf264604b)


5. Copy and save the unique webhook URL present in the dialog. The URL maps to the channel and you can use it to send information to Teams.

6. Select Done.

![image](https://github.com/user-attachments/assets/2677c20d-a8bc-47ed-8600-c505def309e8)

The webhook is now available in the Teams channel.

Now, we have a webhook url available and now the task is to create a lambda that will listen to sns and post on the webhook.

7. Deploy the Aclou Formation

8. Put the test and se the result bellow

Message example:

![image](https://github.com/user-attachments/assets/25dbed43-da40-4ec4-ac64-75cc512a362e)


By Doni
