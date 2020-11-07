# Unwindia

![Compile Mermaid in Markdown](https://github.com/GSH-LAN/Unwindia/workflows/Compile%20Mermaid%20in%20Markdown/badge.svg?branch=master)

### what is it?
> Unwindia is the on demand game server creation service for [pterodactyl](https://pterodactyl.io/) (as game server management panel) combined with the lan party management system [DOTLAN Intranet](http://intranet.dotlan.net/news/) which [we / Gamesession Hannover](https://xxl.gsh-lan.com/news/) are using at our lan parties.

### what it does?
> every time a tourney match has been scheduled and both teams are ready to play, [Unwindia](https://github.com/GSH-LAN/Unwindia) will created a new game server or update a suspended game server at [pterodactyl](https://pterodactyl.io/) and update the tourney match information with the connection details for the game server
> after the match has finished [Unwindia](https://github.com/GSH-LAN/Unwindia) will suspend the game server and sent it back into the pool if a new game server is needed

### current supported games
> [x] CSGO
>
> [ ] to be continued / extended

### current supported lan party management systems
> [x] [DOTLAN Intranet](http://intranet.dotlan.net/news/)
>
> [ ] to be continued / extended

### how is it structured?

![~mermaid diagram 1~](/.resources/structure-mermaid-md-1.png)

### service repositories
| Name | Repo | Build status |
|:---:|:---:|:---:|
| Configuration | <https://github.com/GSH-LAN/Unwindia_config> | ... |