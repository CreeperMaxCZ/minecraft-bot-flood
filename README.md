## PHP Minecraft bot flood stress tester

### Features
* Connect a lot of bots very fast
* [WIP] Use proxies
* [WIP] Other settings

This script is used for stress testing Minecraft servers,
it can connect a lot of bots very fast.
These bots will not respond to any server packets,
so they will time out after 30 seconds by default.

### Usage
`php minecraft-bot-flood.php <ip> <port> <count>`
