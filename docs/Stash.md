# Stash 
Docker container setting for NAS

## General
| Option | Status |
| --- | --- |
| Container Name | stashapp-stash |
| Enable resource limitation | Disabled |
| Enable auto-restart | Enabled |
| Set up web portal via Wed Station | Enabled |
| Container Port | 9999 |

## Port Setting
| Option | Status |
| --- | --- |


## Volume Settings
| Volume Path   | Docker Path    | Folder Access |
| ---           | ---            | ---           |
| /docker/Stash | /root          | Read/Write    |
| /Media/XXX    | /Media_Content | Read/Write    |

## Environment
| Variable | Value |
| --- | --- |
| PATH | /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin |
| STASH_CONFIG_FILE | /root/.stash/config.yml |

## Capabilities


## Links
