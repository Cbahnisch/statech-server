# Notes on server setup

**Current as at 6/1/2024**


### Current Core Items

- Docker
- Tailscale
- MC Docker server (check this one)


[MC Docker Page](https://docker-minecraft-server.readthedocs.io/en/latest/)


## Server Admin Tools

**Accessing CLI**

```
Command looks like:
docker exec -i [container name] rcon-cli
```
[Sending Commands](https://docker-minecraft-server.readthedocs.io/en/latest/commands/)

[Server Commands](https://www.roxservers.com/knowledgebase.php?action=displayarticle&id=223&language=english)

[Server Commands 2](https://minecraft.fandom.com/wiki/Commands)



# Helpful Stuff for Formatting
[Github style guide](https://docs.github.com/en/contributing/writing-for-github-docs/using-markdown-and-liquid-in-github-docs)




## Voice Chat Whoopsies

1. Make sure port in voice chat config (in mc folder) is bound to 24454:24454/UDP
2. Check port in router is forwarded correctly [check here](https://github.com/itzg/docker-minecraft-server/discussions/1422)
3. 
