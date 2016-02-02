# cluster-management
set environment variables in setEnvironment.sh
call ./showUsage.sh to see usage


# configs
# notification configs
You have 3 options for the notification service. They are email, hipChat, and console. See the example configurations below for details. 
"notification":
{
  "email": {
    "host": "host.com",
    "port": 587,
    "sender": "sender@company.com",
    "senderPassword": "password",
    "recipients": [
      "recipient@company.com"
    ],
    "authentication": "true",
    "starttls": "true"
  },
  "hipChat": {
    "restURI": "https://noetl.hipchat.com/v2/room/2398612/notification?auth_token=jfckaBNVM14j8gkiItWZBdUJceat6ODGaNnvwFjp",
    "notify": true,
    "messageColor": "green"
  },
  "console": {}
}

