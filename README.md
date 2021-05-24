# Setup info

[.env_example](./.env_example) shows 3 values required for this bot to work.
Discord token can be retrieved here https://discord.com/developers/applications.
Spread sheet id is just from the url of your spread sheet.
Channel id is the channel id from discord that suggestions will be sent in.

A google service account is required for this. You can set that up here https://console.cloud.google.com/iam-admin/serviceaccounts.
The service account you create (like it gives you an email) needs to be given editor permissions in the share tab of the spreadsheet.
Create a key on service account and download it as json to `credentials.json` in this folder.

`npm install`

`node index.js`

