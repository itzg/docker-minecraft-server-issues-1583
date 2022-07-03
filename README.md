# Sumary

| Tag name      | Working |
|---------------|---------|
| java8         | ✔️       |
| java11        | ❌       |
| java11-openj  | ❌       |
| java17        | ❌       |
| java17-alpine | ✔️       |
| java17-openj  | ❌       |

## java8 ✔️

```
mc_1  | [init] Changing ownership of /data to 1000 ...
mc_1  | [init] Running as uid=1000 gid=1000 with /data as 'drwxrwxr-x 3 1000 1000 4096 Jul  4 01:23 /data'
mc_1  | [init] Resolved version given 1.12.2 into 1.12.2 and major version 1.12
mc_1  | [init] Resolving type given PAPER
mc_1  | [init] Removing old PaperMC versions ...
mc_1  | [init] Downloading PaperMC 1.12.2 (build 1620) ...
mc_1  | [init] Copying plugins over...
mc_1  | [mc-image-helper] 01:23:29.151 INFO  : Copying /plugins/ViaVersion-4.3.1.jar -> /data/plugins/ViaVersion-4.3.1.jar
mc_1  | [init] Creating server.properties in /data/server.properties
mc_1  | [init] Disabling whitelist functionality
mc_1  | [init] Setting white-list to 'false' in /data/server.properties
mc_1  | [init] WARNING: whitelist enabled but not enforced. Set ENFORCE_WHITELIST=TRUE or update 'enforce-whitelist' in server.properties to enforce the whitelist.
mc_1  | [init] Setting enable-rcon to 'true' in /data/server.properties
mc_1  | [init] Setting rcon.password to 'minecraft' in /data/server.properties
mc_1  | [init] Setting rcon.port to '25575' in /data/server.properties
mc_1  | [init] Setting motd to 'A Paper Minecraft Server powered by Docker' in /data/server.properties
mc_1  | [init] Checking for JSON files.
mc_1  | [init] Setting initial memory to 1G and max to 1G
mc_1  | [init] Starting the Minecraft server...
mc_1  | Downloading vanilla jar...
mc_1  | Patching vanilla jar...
mc_1  | Loading libraries, please wait...
mc_1  | 2022-07-04 01:23:39,654 main WARN Disabling terminal, you're running in an unsupported environment.
mc_1  | [01:23:40 INFO]: Starting minecraft server version 1.12.2
...
```


## java11 ❌

```
mc_1  | [init] Running as uid=1000 gid=1000 with /data as 'drwxrwxr-x 3 1000 1000 4096 Jul  4 01:25 /data'
mc_1  | [init] Resolved version given 1.16.5 into 1.16.5 and major version 1.16
mc_1  | [init] Resolving type given PAPER
mc_1  | [init] Removing old PaperMC versions ...
mc_1  | [init] Downloading PaperMC 1.16.5 (build 794) ...
mc_1  | [init] Copying plugins over...
mc_1  | [mc-image-helper] 01:26:04.238 INFO  : Copying /plugins/ViaVersion-4.3.1.jar -> /data/plugins/ViaVersion-4.3.1.jar
mc_1  | [mc-image-helper] 01:26:04.240 ERROR : Failed to sync and interpolate /plugins into /data/plugins : /data/plugins/ViaVersion-4.3.1.jar
```

## java11-openj9 ❌

```
mc_1  | [init] Running as uid=1000 gid=1000 with /data as 'drwxrwxr-x 3 1000 1000 4096 Jul  4 01:27 /data'
mc_1  | [init] Resolved version given 1.16.5 into 1.16.5 and major version 1.16
mc_1  | [init] Resolving type given PAPER
mc_1  | [init] Removing old PaperMC versions ...
mc_1  | [init] Downloading PaperMC 1.16.5 (build 794) ...
mc_1  | [init] Copying plugins over...
mc_1  | [mc-image-helper] 01:27:15.741 INFO  : Copying /plugins/ViaVersion-4.3.1.jar -> /data/plugins/ViaVersion-4.3.1.jar
mc_1  | [mc-image-helper] 01:27:15.743 ERROR : Failed to sync and interpolate /plugins into /data/plugins : /data/plugins/ViaVersion-4.3.1.jar
```

## java17 ❌

```
mc_1  | [init] Running as uid=1000 gid=1000 with /data as 'drwxrwxr-x 3 1000 1000 4096 Jul  4 01:27 /data'
mc_1  | [init] Resolved version given 1.16.5 into 1.16.5 and major version 1.16
mc_1  | [init] Resolving type given PAPER
mc_1  | [init] Removing old PaperMC versions ...
mc_1  | [init] Downloading PaperMC 1.16.5 (build 794) ...
mc_1  | [init] Copying plugins over...
mc_1  | [mc-image-helper] 01:27:39.991 INFO  : Copying /plugins/ViaVersion-4.3.1.jar -> /data/plugins/ViaVersion-4.3.1.jar
mc_1  | [mc-image-helper] 01:27:39.994 ERROR : Failed to sync and interpolate /plugins into /data/plugins : /data/plugins/ViaVersion-4.3.1.jar
```

## java17-alpine ✔️

Ignore the error because the ignore java version flag is not set. The server would start if this was set

```
mc_1  | [init] Changing ownership of /data to 1000 ...
mc_1  | [init] Running as uid=1000 gid=1000 with /data as 'drwxrwxr-x 3 1000 1000 4096 Jul  4 01:28 /data'
mc_1  | [init] Resolved version given 1.16.5 into 1.16.5 and major version 1.16
mc_1  | [init] Resolving type given PAPER
mc_1  | [init] Removing old PaperMC versions ...
mc_1  | [init] Downloading PaperMC 1.16.5 (build 794) ...
mc_1  | [init] Copying plugins over...
mc_1  | [mc-image-helper] 01:28:41.748 INFO  : Copying /plugins/ViaVersion-4.3.1.jar -> /data/plugins/ViaVersion-4.3.1.jar
mc_1  | [init] Creating server.properties in /data/server.properties
mc_1  | [init] Disabling whitelist functionality
mc_1  | [init] Setting white-list to 'false' in /data/server.properties
mc_1  | [init] WARNING: whitelist enabled but not enforced. Set ENFORCE_WHITELIST=TRUE or update 'enforce-whitelist' in server.properties to enforce the whitelist.
mc_1  | [init] Setting enable-rcon to 'true' in /data/server.properties
mc_1  | [init] Setting rcon.password to 'minecraft' in /data/server.properties
mc_1  | [init] Setting rcon.port to '25575' in /data/server.properties
mc_1  | [init] Setting motd to 'A Paper Minecraft Server powered by Docker' in /data/server.properties
mc_1  | [init] Checking for JSON files.
mc_1  | [init] Setting initial memory to 1G and max to 1G
mc_1  | [init] Starting the Minecraft server...
mc_1  | Downloading vanilla jar...
mc_1  | Patching vanilla jar...
mc_1  | Unsupported Java detected (61.0). Only up to Java 16 is supported.
mc_1  | 2022-07-04T01:28:53.000+0200    INFO    mc-server-runner        Done
```

## java17-openj9 ❌

```
mc_1  | [init] Running as uid=1000 gid=1000 with /data as 'drwxrwxr-x 3 1000 1000 4096 Jul  4 01:29 /data'
mc_1  | [init] Resolved version given 1.16.5 into 1.16.5 and major version 1.16
mc_1  | [init] Resolving type given PAPER
mc_1  | [init] Removing old PaperMC versions ...
mc_1  | [init] Downloading PaperMC 1.16.5 (build 794) ...
mc_1  | [init] Copying plugins over...
mc_1  | [mc-image-helper] 01:30:00.215 INFO  : Copying /plugins/ViaVersion-4.3.1.jar -> /data/plugins/ViaVersion-4.3.1.jar
mc_1  | [mc-image-helper] 01:30:00.217 ERROR : Failed to sync and interpolate /plugins into /data/plugins : /data/plugins/ViaVersion-4.3.1.jar
```
