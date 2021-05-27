# Summary

Compose file for a two container Minecraft stack:
  1. Minecraft server (assumes you're using dynmap plugin which you should be imvho)
  2. MySQL server to store the dynmap data

# Usage

There is a ton of cusomization available from both container providers, but generally you can just:
  1. Get the Minecraft server/plugin/etc files 
  2. Confirm the `volumes` definitions in the compose file are pointing to those files
  3. Make it so `docker-compose up -d`

# References

This repo was heavily influenced by these awesome projects:
  - https://github.com/itzg/docker-minecraft-server 
  - https://github.com/webbukkit/dynmap
  - https://hub.docker.com/_/mysql
