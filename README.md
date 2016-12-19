## Work in progress... this isn't functional yet!

# ppbot

Slack bot for recording ping pong matches and rank players based on the [Elo rating system](https://en.wikipedia.org/wiki/Elo_rating_system). It uses [slack-terminalize](https://www.npmjs.com/package/slack-terminalize "slack terminalize at npm").

# Setup

- Run `npm install` to install the dependencies
- Paste the `xoxb-token` of your bot integration in `init` function inside `index.js` file
- Run `node .` to start the app. Now the bot should be listening to the slack team you integrated it with
- Invite the bot to desired channels with `/invite @<your-bot-name>` and try the sample commands
- Start with `help` in the channel the bot is listening to
