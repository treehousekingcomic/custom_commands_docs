![Python](https://img.shields.io/badge/Python-3.7%20%7C%203.8-blue)
![Discord](https://img.shields.io/badge/Discord-1.3.3-green)[[!invite](_media/invite.png)](https://discord.com/oauth2/authorize?client_id=724847752449753140&permissions=268815424&scope=bot)

## Information
Some information need to know before inviting the bot. 

- Any member can make command. But they will remain unapproved. An admin or server manager can approve the those commands. See ho to approve a command [Here](?id=management)
- After gtting approved if command owner edit that command, the command will become unapproved if the editor dont have `Manage server` permission.
- If a command is unapproved server managers can still execute that command to see command content to decide wheather it should be approved or not.
- If a member have `Manage server` permission command made by him will be approved automatically after creation.
- If you are administrator you can delete any command made by anyone. But who dont have `Administrator` permission cant delete others command untill they own that command. 
- Server managers can unapprove any command including own and others commands.

So give server manager permission to trusted.

> Why restricted?

There are some people who will missuse this bot to make command with pornographic content or containing bad words etc. Thats why command making is restricted.

## Available type of commands
All the syntax is documented assuming prefix is `**`
### Embed
Send a embeded response when command executed

`Syntax` \**embed \<command_name>

After doing this you will be asked few questions
> 1. What will be the embed **title**?
> 2. Your embed **description**
> 3. **Thumbnail** image url
> 4. **Image** url

If you are not sure what are those [See this](?id=embed-components)

> Editing embed

`Syntax ` **edit embed \<command_name> \<component> \<new_value>

`Example` \**edit embed myfirstembed `title` This is a new awesome title.
> In place of title you can put what component you want to edit you want to edit

#### Embed components
> This image will describe the embed components

![Components](https://cdn.discordapp.com/attachments/726435336229617726/726436193394229278/Screenshot_1.png)
### Text
Send a normal text.

`Syntax ` \**text \<command_name> \<content>

`Example ` \**text myfirsttext This is a text response

> Editing an text command

`Syntax ` \**edit text \<command_name> \<new_content>

### Role
There are 3 type of role command

1. giverole
2. removerole
3. togglerole

`Syntax ` \**\<role_command_type> \<command_name> \<role>
> In place of **\<role_command_type>** put any of the 3 types

`Example ` \*\*giverole dev @Developers

> So when someone will execute this command like ****dev** he will get Develoeprs role is it exists.

Note : If after making the dev command you delete the developers role and remake you have to edit the dev command to make sure this work.

> Editing and role command

`Syntax ` \*\*edit role \<command_name> <role>

This will change role of a command related to role.

## Other usefull features
### Poll
Make poll in a channel so people can share their thoughts

`Syntax` \**poll "\<question>" choice1,choice2,choice3,choice4

In place of \<question> put your question. Remeber to put " " In both side of question. (Double quotes)

`Example ` \**poll "How is the day?" Cool, Bad, Average

### Vote
Make vote in a channel so people can vote

`Syntax ` \**vote "\<question>" \<duration> choice1,choice2,choice3,choice4

In place of \<question> put your question. Remeber to put " " In both side of question. (Double quotes). And \<duration> is the amount of seconds it will wait before publishing result

`Example ` \**vote "Who should be the next admin?" 60 John, Doe, Milli

# Management
Commands list, delete and see help

\*\*delete \<command_name> - Will delete a command\
\*\*list - Will show list of commands made on this server\
\*\*list unapproved - Show a list of unapproved commands on this server
> Unapproved commands are those commands made by normal server members who don't have `Manage server` permission. An Admin or server manager need to approve the command made by normal members before they can be used. Ho to approve or unapprove a command is explained below

\*\*approve \<command_name> - To approve a command

\*\*unapprove \<command_name> - To unapprove a command

## Editing command
You can also edit command name, custom help for command and command owner.

> Editing command name

`Syntax` \*\*edit command name \<command_previous_name> \<new_name>


> Editing command custom help

`Syntax` \*\*edit command help \<command_name> Your help text


> Changing command owner

`Syntax` \*\*edit command owner \<command_name> \<new_owner>

**Note :** By changing owner to someone else you will loose ability to edit/delete the command.

# Customization
Some simple customization

## Change prefix
`Syntax` \*\*prefix \<new_prefix>\
`Example` \*\*prefix +
> Now your server prefix will be `+`

## Cool feature
`**noprefix toggle` After doing this if you have a command named `test` and to execute that command you dont need to type `**test` just type `test` and command will be executed. And if you again do `**noprefix toggle` this will turn off. 
