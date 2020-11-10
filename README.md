# Discord.js Bot Template

## This template includes the essentials:
- A `yarn start` shortcut
- Proper bot shutdown on `SIGINT`
- The bot ignores messages from itself
- ESLint set to Airbnb syntax
- A properly configurated GPLv3 license
- Proper .gitignore config
    - Set to ignore the config file `src/config.json`
- An editorconfig file

### To make a new bot:
1. Clone/fork this template.
2. Delete `/.git` folder, and run `git init` again in the top directory.
3. Run `yarn install` or `npm install` and don't remove the generated lockfile
4. Change username and repo link in `package.json`
5. Create file src/config.json and add a "token" key/value to store your bot's token
6. Delete or wipe this README file
