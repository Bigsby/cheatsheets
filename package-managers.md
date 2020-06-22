# Package Managers

### Placeholders
- `«p»` - package name
- `«pf»` - package file
- `«re»` - regular expression
- `«ex»` - file system wild card expression

## Frontends
|tool|update|upgradable|upgrade|install|remove|prune|search|info|installed|
|---|---|---|---|---|---|---|---|---|---|
|pkg|update|updating|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|info|
|apt|update|list --upgradable|upgrade|install «pe»|remove «pe»|autoremove|search «re»|show «p»|list --installed|
|apt-get|update|-u upgrade --assume-no|upgrade|install «p»|remove «p«|autoremove|apt-cache search «re»|apt-cache show «p»||
|yum|check-update|list updates|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|list installed|
|dnf|check-update|list --upgrades|upgrade|install «p»|remove «p»|autoremove|search «ex»|info «p»|list --installed|
|pacman|-Sy|-Qu|-Syu|-S «p»|-R «p»|-Rsn $(pacman -Qdtq)|-Ss «re»|-Qi «p»|-Qe|
|zypper|ref|lu|up|in «p»|rm «p»|rm -u|se «ex»|if «p»|se -i|
|apk|update||upgrade|add «p«|del «p«||search »re»|info »p»|info|
|swupd|check-update||update|bundle-add «p»|bundle-remove «p»|bundle-remove --orphans|search »re»|bundle-info «p»|bundle-list|
|xbps|xbps-install -S||xbps-install -Su|xbps-install -S »p»|xbps-remove «p»|xbps-remove -o|xbps-query -Rs «ex»|xbps-query -R «p»|xbps-query -l|
## Package Managers
|tool|install|
|---|---|
|rpm|rpm -i «pf».rpm|
|dpkg|dpkg -i «pf».deb|

## Usages
|tools|OSs|
|---|---|
|pkg|FreeBSD, OpenBSD, NetBSD, GhostBSD|
|dpkg,apt,apt-get/-cache|Debian, Ubuntu|
|rpm,yum,dnf|Red Hat, Fedora, CentOS|
|pacman|Arch Linux, Manjaro|
|zypper|(open)SUSE|
|apk|Alpine Linux|
|swupd|Clear Linux|
|xbps-install/-remove/-query|Void Linux|


## Other gothcas

### pacman
#### PGP errors
```
pacman-key --init
pacman-key --populate
```

