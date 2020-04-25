## Welcome to nickiscool.ml here you can learn how to make discord bots

You can use the [editor on GitHub](https://github.com/nickdebesten/nickiscool.ml/edit/master/README.md) to maintain and preview the content for your website in Markdown files.


### Lets start
First of all make sure you downloaded [node.js](https://nodejs.org/en/download/).
Then make a directory. This is where you can store all the files of the bot.
Then open CMD and run `npm init` it will make a package.json file. You need this in order to run the discord bot later.
then make a file called `index.js` leave it as it is now. Go to [discord developer page] (https://discordapp.com/developers/applications) and make a application and a bot user. Copy the token you will need it in order to run the bot.


```markdown
const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});

client.on('message', message => {
  if (message.content === 'ping') {
    message.reply('pong');
  }
});

client.login('token');// replace token with the token from the dev page
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nickdebesten/nickiscool.ml/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
