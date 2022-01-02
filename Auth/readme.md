# Auth
There will be an Auth Server and a Game Server The Auth Server contains the account functions likes login/register/profile. The server will be an oAuth Provider to the game clients.

This way we can create multiple games or servers and use the same login.

If a player open the URL of the gameserver directly he will be redirected to the auth server to get the cridentials and will be redirected back to the oAuth Consumer.

Accounts can be also created with other oAuth provider like Google etc
