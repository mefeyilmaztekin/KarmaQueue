# LeeesBungeeQueue
[![discord](https://discord.com/api/guilds/683053832694923319/embed.png)](https://discord.gg/WWm35Tc)

LeeesBungeeQueue is a 2b2t like queue plugin for Bungeecord
very easy to configure just make sure you have these things on bungeecord
or waterfall set properly below

NOTE: it is recommended to use Waterfall and not bone stock bungeecord with this plugin (waterfall forks work fine) if you have an issue with a specific waterfall fork please let me know and ill see whats going on otherwise please use regular waterfall https://papermc.io/downloads#Waterfall

```

Waterfall / Bungeecord config.yml ->

please note only use the plugin
with main or auth in priorities if
you have alwaysqueue set to false otherwise
make the only server in priorities the queue server
EXAMPLE PREMIUM SERVERS:
priorities:
  - Main

EXAMPLE CRACKED SERVERS:
 priorities:
  - auth
  
  
 If you have alwaysqueue set to true
 which it is set to by default then make
 sure you have this set like this
 priorities:
 - queue

also make sure this is set to true
force_default_server: true

at the bottom of your bungeecord / waterfall config
add the queue main and auth(only if your server is offline mode / cracked)
like this example below:
servers:
  7b7t:
    motd: '&b7b&37t &6Main Server'
    address: localhost:8401
    restricted: true
  queue:
    motd: '&&b7b&37t &6Queue Server'
    address: localhost:8402
    restricted: true
  auth:
    motd: '&b7b&37t &6Auth Server'
    address: localhost:8403
    restricted: true




LeeesBungeeQueue config.yml ->

How to configure LBQ's config properly
make sure you set the names of the servers
in lbq to the exact name of the ones you set
in the bungeecord config

QUEUESERVER: "queue"
MAINSERVER: "7b7t"
#set this to false if your a premium server
ENABLEAUTHSERVER: "true"
AUTHSERVER: "auth"    

```
need extra help ? join our support discord: https://discord.gg/QFkeH5qaKQ
