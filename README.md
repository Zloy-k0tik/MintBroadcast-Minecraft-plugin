# MintBroadcast-Minecraft-plugin
**Plugin for spigot/paper/purple. He adds: new command such as /broadcast.**

**You can change configuration for file «config.yml».**

**Installing: Place the plugin in the «plugins» folder. Then start the server. The plugin will load automatically.**

**Minecraft tested versions: 1.16 - 1.20.6**

**Required Java: 11+**
___
**Plugin added commands:**
* /mintbroadcast - main plugin command
* /broadcast - broadcast command
---
* /mb help - show help text
* /mb reload - reloaded configuration
---
**Permissions:**

Admin permission:

* mintbroadcast.admin

Player permission:

* mintbroadcast.spawnuse

---

**Example configuration:**

```
###########################################
#
#   MintBroadcast
#   VERSION: 1.1
#   AUTHOR: Zloy_k0tik
#   REQUIRED JAVA: 11+
#
# PERMISSION FOR ADMIN COMMANDS:
# mintbroadcast.admin
#
# PERMISSION FOR PLAYER COMMANDS:
# mintbroadcast.spawnuse
#
# Use legacy color code>>> &x&3&0&C&D&1&8
#
# Placeholders:
# {msg} - broadcast message
# {playername} - nickname who send message
# {time} - time when send message
# [prefix] - broadcast prefix
# [pluginPrefix] - plugin prefix
#
###########################################
config:
  timeFormatter: "HH:mm:ss"

messages:
  pluginPrefix: "&x&3&0&C&D&1&8&lM&x&2&B&B&1&1&7&li&x&2&6&9&6&1&5&ln&x&2&1&7&A&1&4&lt&x&2&D&2&D&2&D&lBroadcast&7>&f"
  prefix: "&x&3&0&C&D&1&8&lB&x&2&D&A&A&1&9&lr&x&2&9&8&7&1&B&lo&x&2&6&6&5&1&C&la&x&2&2&4&2&1&E&ld&x&1&F&1&F&1&F&lc&x&1&F&1&F&1&F&la&x&1&F&1&F&1&F&ls&x&1&F&1&F&1&F&lt&7>&f"
  message: "[prefix] &r{msg} &7(by &6{playername}&7) &8(&6{time}&8)"
  pluginReloaded: "[pluginPrefix] &aConfiguration reloaded"
  usage: "[pluginPrefix] &4Usage: /bc <message>"
  notPermission: "[pluginPrefix] &cYou do not have permission"
  unknownCommand: "[pluginPrefix] &cUnknown command"
  ```
