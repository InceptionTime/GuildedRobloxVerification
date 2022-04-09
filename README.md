Public tracker for feature requests & bug reports for the Guilded Roblox Verification bot
Please submit any [bug or feature requests here](https://github.com/InceptionTime/GuildedRobloxVerification/issues)


Currently in closed testing. 
After closed testing, I will potentially release the invite link to the public

Code for the bot will remain private.

## How does the bot work?
* The bot checks to see if the user has linked their Roblox account to their Guilded account through Guilded connections.
* If it finds a connected account it'll update the users nickname and provide the user with the verified role

If you want to gatekeep your Guilded server my recommendation is:
* Give the verified role all the default permissions you'd want users to have.
* Restrict the member role to only be able to view and send messages.
* Create a new channel called "Lobby" (or whatever you'd like it to be called) 
  * Set member permissions so the role can only see & send messages
  * Set verified permissions so the role has all permissions denied
* Set all other channels to deny all permissions for the member role
* Set all other channels to the same default permissions for the verified role


## What permissions does the bot need?
* Read messages
* Send messages
* Send private messages
* Manage messages (Deletes the users !verify message)
* Update nicknames

You can limit the read and write permissions to certain channel permissions or to the role permissions

## What roles does the bot need?
* 1 role named "Verified"

## Commands
* !verify
