===========
# EternalVoid

An anarchy server with some high quality anarchy

## How to propose changes

Please use the below approach to keep changes visible and easy to understand.

1. Make your change in a new branch - Direct commits to master are disallowed.
2. Create a pull request.
3. Message in the Mod chat in Discord to discuss / discuss here in the pull request.
4. Commit pull request either by:
   A committee of three approvals.
   Or by getting Daenningas to use admin override permissions.
5. Delete your committed branch.

After that the following needs to happen for your change to be active:
1. Every 15 minutes the EVA backend server does a git pull from this repro. It then copies *.yml files into /opt/minecraft/server
2. The server needs to restart. This happens twice a day at 6AM and 6PM Eastern time.

## Resources server is tuned with

### SpigotMC Optimisation Guide

https://www.spigotmc.org/threads/guide-server-optimization%E2%9A%A1.283181/

### Aikar's recommended Minecraft Service flags

https://www.spigotmc.org/threads/guide-optimizing-spigot-remove-lag-fix-tps-improve-performance.21726/page-10#post-1055873

https://aikar.co/2018/07/02/tuning-the-jvm-g1gc-garbage-collector-flags-for-minecraft/

### Additional Minecraft Server Optimization Info

https://github.com/YouHaveTrouble/minecraft-optimization
