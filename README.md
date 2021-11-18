# arras template+arras client with chat system and chat commands.
#### credits to attacker and MTS
## table of contents:
### 1) how to use this template
### 2) how to create a new chat user
### 3) how to create a new role and give color and value
### 4) how to edit your server room
### 5) which files to edit and which not to edit
### 6) how to authenticate and use commands ingame


## 1: how to use this template.
So, you´ve found this template, GG, you found the best template ever to be made!
But, how to use it for your own game?
Now first, you have to know the link.
so, go to `show` and click on the button, and see your app alive!
Second, edit `index.html` on the lines `14` and `67` to your own website name.
Third, go to `changelog.html` and remove all the patches, and make your own changelog there.

## 2: how to create a new chat user & give him/her a role.
First, go to `chat_user.json`, then add a new line like this ```"88FA0D759F845B47C044C2CD44E29082CF6FEA665C30C146374EC7C8F3D699E3": {"name": "attacker","role": "developer"},```
`88FA0D759F845B47C044C2CD44E29082CF6FEA665C30C146374EC7C8F3D699E3` is the password encrypted in sha256, use `https://convertstring.com/hash/sha256`
`{"name": "attacker"` this is the username that the server will change you into.
`"role": "developer"}` this is the role that the user will have.

## 3: how to add a new role and give value and color to it.
First, go to `chat_user_role.json`
add a new role just like the other role lines like ` "blacklist": -1,`
the int(number) is the role value.

## 4: how to edit your server room, and other config.
First, go to `gamemodes.js`, then add/edit a new/a existing room setup to what you want, basic arras-template skills.

## 5: which files to edit and which NOT to edit.
`server.js`:
``:
``:
``:
``:
``:
``:
``
``
``