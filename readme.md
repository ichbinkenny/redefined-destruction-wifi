# Wifi Module for Lego Battle Bots
---
## About
---
This is a submodule for the lego battle bots project. This module controls communication between the raspberry pi, and a server to share bot status. If you are wanting to clone the full project, it can be found [here](https://github.com/ichbinkenny/redefined-destruction.git).
---
## Communication Protocol
---
All Battle Bots communicate by using datagram packets. Each packet has an identifier and a value associated with it. Once a bot is deemed non-functional, its respective datagram will disconnect. For more information, please see [this diagram](todo).
