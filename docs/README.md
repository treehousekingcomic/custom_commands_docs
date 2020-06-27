![Python](https://img.shields.io/badge/Python-3.7%20%7C%203.8-blue)
![Discord](https://img.shields.io/badge/Discord-1.3.3-green)

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

\*\*approve \<command_name> - To approve a command\

\*\*unapprove \<command_name> - To unapprove a command

# Customization
Some simple customization

## Change prefix
`Syntax` \*\*prefix \<new_prefix>\
`Example` \*\*prefix +
> Now your server prefix will be `+`

> Cool feature
`**noprefix` After doing this if you have a command named `test` and to execute that command you dont need to type `**text` just type `test` and command will be executed. And if you again do `**noprefix` this will turn off. 