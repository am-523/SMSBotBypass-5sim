# 5sim
5sim.net is a service, that offer you temp phonenumbers for otp verification. 
It include a lot of countries you can choose from. 
The cheapest option is russia. 1 verification for Discord cost only 1.3 Rubel!
The Project use the API to get numbers, check for verifycodes & more. It is added within a discordbot and uses slashcommands
Slashcommands working similar to usual ones but are more integraded within Discord so typing / will suggest possible avaible commands and shows what args are needed
Its more easy to use then using a custom prefix like ! and run a helpcommand to list all commands. It is secure and will only show the responses on your side in a hidden embed.
This embed will only be shown to you so its not possible for the owner to login into the bot and see the secret stuff. 
You can run these commands in Guilds or DMs with no risk of the data being leaked

**Commonly asked issues and their solutions:**
- __The Bot is not starting / throw a connection error:__
  - make sure to whitlelist your current public IP on MongoDB Website under Network Access

- __The Bot is online but i cant use any slashcommand__
  - reinvite the bot but this time make sure you selected application.commands in the devconsole at the subpage where you generate a invitelink
