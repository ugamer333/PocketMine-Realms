# Realms _for PocketMine-MP_

This plugins registers and sends updates about the server to the [PocketMine Realms](http://realms.pocketmine.net/) service.
If you set it properly, you can manage the soft-whitelist in-game, adding players so they can see your server in their list.
You can also open/close the server from there.


## Configuration
| Name | Type | Description |
| :---: | :---: | :--- |
| __ownerName__ | string | This should be your in-game name on Realms, case-sensitive. |
| __externalAddress__ | string | The server external IP or domain. [Get your IP](http://www.whatismyip.com/) |
| __externalPort__ | integer | __The port to access the server. It must be forwarded, if not, players won't be able to join the server.__ [Port Forwarding](http://portforward.com/) |
