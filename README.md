# 👶 MartheBot

This is my personal assistant Slack bot.

# Testing
To complete the configuration of this bot, make sure to make a copy of the included `.env.example` file. Name it `.env` and update it with your platform tokens and credentials.

1. Create a bot app in Slack [by following these instructions](https://botkit.ai/docs/v4/provisioning/slack-events-api.html)
2. Run `npm install`and `npm run`
3. Use a service like [ngrok.com](https://ngrok.com/) to forward your local bot port (`Webhook endpoint online:  http://localhost:3000/api/messages`)


# 🔧 Adding features
Adding features can be done in the [features/](features/) folder.

# 🤖 Botkit.ai
MartheBot has been created with Botkit.ai: [Botkit Docs](https://botkit.ai/docs/v4)

It's powered by [a folder full of modules](https://botkit.ai/docs/v4/core.html#organize-your-bot-code). 
