# Servers for ByteBukkit
To add a server to the websites entry, you may do a pull request where you add your server icon and the entry in the json.
Alternatively you can also open a issue, and add your **1:1** ratio (Square) server-icon, and the required metadata for your server.

How to add a server entry into `servers.json`

You can paste this template snippet after the newest entry, make sure the last entry before yours ends with `},` and not only `}`, else there will be a Syntax error.
```json
    {
      "server_name": "Server Template",
      "server_type": "FourKit",
      "server_address": "play.template.lce",
      "server_owner": "Byte_HD",
      "server_homepage": "https://optional.website.com",
      "console_version": "neoLegacy",
      "server_icon": "/img/server_name-icon.png"
    }
```
Once pasted and modified correctly, the file may look a little something like this:

```json
{
  "servers": [
    // Imagine entries before this..
    {
      "server_name": "Cool Server",
      "server_type": "newKit",
      "server_address": "play.game.lce",
      "server_owner": "someguy123",
      "server_homepage": "https://website.com",
      "console_version": "Revelations",
      "server_icon": "/img/Cool_Server-icon.png"
    },
    {
      "server_name": "Server Template",
      "server_type": "FourKit",
      "server_address": "play.template.lce",
      "server_owner": "Byte_HD",
      "server_homepage": "https://optional.website.com",
      "console_version": "neoLegacy",
      "server_icon": "/img/server_name-icon.png"
    }
  ]
}
```

Once the PR is approved, your server will show up a little something like this on ByteBukkit:

<img width="920" height="247" alt="server" src="https://github.com/user-attachments/assets/6672dec5-34a7-4d30-a606-4e9bcacb4c0b" />
