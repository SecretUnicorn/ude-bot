# ude-bot
## About this bot
This bot has at the moment to uses. First to update all user roles to the next semester and second to provide a message in a specific channel where new users can react to in order to get their new roles.
## Usage


## Documentation
`./index.js` - Main file and entrypoint\
`./commands/` - Holds all commands available\
`./commands/all.js` - Updates all user roles to the next semester\
`./commands/ping.js` - Pong!\
`./commands/react.js` - Reacts to the last message - for testing\
`./roles/` - holds all files for the role claim message\
`./roles/first-msg.js` - sends a message to an empty channel or edits the first message\
`./roles/roleClaim,js` - if user reacts to specific reaction he get a role assigned and the reaction is removed\
