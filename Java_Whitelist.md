## Using the whitelist feature: Minecraft Java
In this article, you will be shown how to put a whitelist on your server, and add people to the whitelist so that only they can join the server!

### Whitelist Explained
The whitelist is a feature built into vanilla minecraft in order to allow you to create servers such a private ones, for you and your friends - without the worry that others can get in and grief you!

### Pre-requisites
- A minecraft service
- Basic Minecraft Command Knowledge

### Whitelist Commands

| Command | Description |
| --- | --- |
| /whitelist add \<player\>| Adds a player to the whitelist. |
| /whitelist remove \<player\> | Removes a player from the whitelist. |
| /whitelist list | Lists all the players on the whitelist. |
| /whitelist reload | Reloads the whilelist to save changes. |
| /whitelist on | Turns on the whitelist.|
| /whitelist off | Turns off the whitelist.|

### How to add / remove someone from the Whitelist using commands:
In this example, we'll be __adding__ the player `JackGoBrr` to the whitelist on our server, using commands.
- Step 1: Log into your server
- Step 2: Ensure that you OP yourself from Console. OPs are the only ones that are able to use the whitelist commands.
- Step 3: Type this command in chat: `/whitelist add JackGoBrr`, replacing "JackGoBrr" with a player name of your choice
- Step 4: The server will return a message telling you it was successful, as shown in the screenshot below

![Adding to whitelist with cmds](https://versatilenode-kb.kawaiicdn.com/assets/images/whitelist-command-adding.png?_t=1614937614)

To remove someone using commands, it's exactly the same, but instead of typing "`/whitelist add`", replace `add` with `remove`!

![Removing from whitelist with cmds](https://versatilenode-kb.kawaiicdn.com/assets/images/whitelist-command-removing.png?_t=1614937610)

```Remember: Never put a / before commands if you are executing them from console!```

### How to add / remove someone from he Whitelist using the Whitelist.json file
In this example, we'll be __adding__ the player `JackGoBrr` to the whitelist on our server, using the **whitelist.json** file.
- Step 1: Log into your server's sFTP, using a program like FileZilla
- Step 2: Locate the file named `whitelist.json` in the __root directory__ of your server files
- Step 3: Open the `whitelist.json` file using an editor such as **Notepad++**
- Step 4: Head to [This site](https://mctools.org/whitelist-creator) to generate your whitelist file
- Step 5: Once on MCTools, type in each username that you want to whitelist, seperated by commas, as shown in the screenshot below
- Step 6: Once your file has been generated, click the ![CopyContentsButton](https://versatilenode-kb.kawaiicdn.com/assets/images/copy-whitelist-button.png?_t=1614938128) and overwrite ALL data that is currently in the `whitelist.json` file.
- Step 7: Your `whitelist.json` file must now look something like this:

![Whitelist.json example](https://versatilenode-kb.kawaiicdn.com/assets/images/whitelist-file-example.png?_t=1614938132)

- Step 8: Save the file, and run `/whitelist reload` on your server!

```Remember: Never put a / before commands if you are executing them from console!```
