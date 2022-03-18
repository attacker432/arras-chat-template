# arras template+arras client with chat system and chat commands.
## table of contents:
### 1) how to use this template
### 2) how to create a new chat user
### 3) how to create a new role and give color and value
### 4) how to edit your server room
### 5) which files to edit and which not to edit
### 6) how to authenticate and use commands ingame
### 7) credits


## 1: how to use this template.
So, you´ve found this template, GG, you found the best template ever to be made!
But, how to use it for your own game?
Now first, you have to know the link.
so, go to `show` and click on the button, and see your app alive!
Second, edit `index.html` on the lines `14` and `67` to your own website name.
Third, go to `changelog.html` and remove all the patches, and make your own changelog there.

## 2: how to create a new chat user & give him/her a role.
First, go to `chat_user.json`, then add a new line like this ```"88FA0D759F845B47C044C2CD44E29082CF6FEA665C30C146374EC7C8F3D699E3": {"name": "attacker","role": "developer"},```
`88FA0D759F845B47C044C2CD44E29082CF6FEA665C30C146374EC7C8F3D699E3` is the password encrypted in sha256, use `https://convertstring.com/hash/sha256` and put your password to generate the sha256 string, put the hash in.
`{"name": "attacker"` this is the username that the server will change you into.
`"role": "developer"}` this is the role that the user will have.

## 3: how to add a new role and give value and color to it.
First, go to `chat_user_role.json`
add a new role just like the other role lines like ` "blacklist": -1,`
the int(number) is the role value.
Then go to `chat_user_role_color.json` and add the new role and the number(color codes defined in app.js) to color the role.
Then after all go to `chat_user.json` and add a user account with the role if you want.

## 4: how to edit your server room, and other config.
First, go to `gamemodes.js`, then add/edit a new/existing room setup to what you want, basic arras-template skills.

## 5: which files to edit and which NOT to edit.
`server.js`: This file contains all the calculations and stuff to let your game run, feel free to edit.
`chat_user.json`: This file contains the user info, feel free to edit.
`chat_user_role.json`: This file contains the role value info, feel free to edit.
`chat_user_role_color.json`: This file contains the role colors info, feel free to edit.
`chat_filter_regex.txt`: This file contains the chat filter to filter the swear words out(bugged), Dont edit.
`package.json`: This file contains the packages the server uses to operate, only edit if you know what youre doing.
`definitions.js`: This file contains the tank data, feel free to edit.
`fasttalk.js`: This file contains the server websocket protocol encryption/decryptions, Dont edit.
`hshg.js`: This file contains the hash grid, Dont edit.
`util.js`: This file contains some calculation codes, only edit if you know what youre doing.
`random.js`: This file contains some random calculation and the bot/boss names, feel free to edit the names.
`app.js`: This file contains client side stuff, feel free to edit if you know what you're doing.
`index.html`: This file contains the website build, feel free to edit.
`main.css`: This file contains the styling of your webpage, feel free to edit.
`namegenerator.js`: This file contains the random name generator for if you have no name ingame, feel free to edit.
`mockups.json`: This file contains tank data, auto-rebuild, dont edit.

## 6: how to use chat and chat commands ingame
go join and press `h` key, and type and press `enter`, to use a command, type /[command name], to auth, type /pwd [password].

## 7: credits
to attacker - for building this in one and making the template.
to MTS - chat system codes
to Lagbreaker-II - this basic server

## 8: accounts
owner: /pwd owner
developer: /pwd developer
etc.
