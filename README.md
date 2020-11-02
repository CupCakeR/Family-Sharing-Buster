# Family Sharing Buster
A simple, yet effective little add-on to prevent people from abusing the Steam family sharing feature. Neither an API key, nor setup is required.

## Edit / Contribute
The source code requires to be [transpiled](https://gitlab.com/sleeppyy/laux).

## Installation
Simply add the [workshop addon](https://steamcommunity.com/sharedfiles/filedetails/?id=2274778015) to your server's workshop collection.

## Configuration (ConVars)
| name | default | values |
| --- | --- | --- |
| fsbuster_enable | 1 | **0** = Disable <br/> **1** = Enable |
| fsbuster_mode | 2 | **1** = Block family sharing <br/>**2** = Block if the license's owner is banned |
| fsbuster_action | 3 | **1** = Kick the player <br/>**2** = Ban the player <br/> **3** = Ban the player and the license's owner |
| fsbuster_banlength | 0 | **-1** = Existing ban's remaining time <br/>**0** = Permanent <br/> or **any** number in minutes |