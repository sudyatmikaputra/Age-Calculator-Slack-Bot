# Age-Calculator-Slack-Bot
Age Calculator Slack Bot using Golang

How to use it :
1. Create new slack apps first in slack API : api.slack.com/apps
2. click from scratch and enter the app name and select the workspace
3. go to Socket Mode and enable the socket mode and fill the token name and generate the token
4. go to event subscription and enable events on the menu
5. on the subscribe to bot events section, click add bot user event : app_mention, im_history_change, message.im, message.channels, message.mpim
6. go to OAuth & Permissions, in the bot token scopes section, click add an OAuth space and select : chat:write, chat:write.public, channels:read, im:read, im:write, mpim:read, mpim:write
7. click "Install to Workspace" and allow the permission.
8. In main.go, change the token to with your own Slack Token that have been created before
