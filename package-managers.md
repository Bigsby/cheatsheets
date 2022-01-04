# Package Managers

### Placeholders
- `«p»` - package name
- `«pf»` - package file
- `«re»` - regular expression
- `«ex»` - file system wild card expression

## Frontends
|tool|update|upgradable|upgrade|install|remove|prune|search|info|installed|
|---|---|---|---|---|---|---|---|---|---|
|apk|update||upgrade|add «p«|del «p«||search »re»|info »p»|info|
|apt|update|list --upgradable|upgrade|install «pe»|remove «pe»|autoremove|search «re»|show «p»|list --installed|
|apt-get|update|-u upgrade --assume-no|upgrade|install «p»|remove «p«|autoremove|apt-cache search «re»|apt-cache show «p»||
|dnf|check-update|list --upgrades|upgrade|install «p»|remove «p»|autoremove|search «ex»|info «p»|list --installed|
|pacman|-Syy|-Qu|-Su|-S «p»|-R «p»|-Rsn $(pacman -Qdtq)|-Ss «re»|-Qi «p»|-Qe|
|pkg|update|updating|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|info|
|pkg_||pkg_add -un|pkg_add -u|pkg_add «p»|pkg_delete «p»|pkg_check|pkg_info -Q «re»|pkg_info «p»|pkg_info|
|pkgin|up||upgrade|in «p»|rm «p»|autoremove|se «re»|pkg-descr «p»|pkgin ls|
|swupd|check-update||update|bundle-add «p»|bundle-remove «p»|bundle-remove --orphans|search »re»|bundle-info «p»|bundle-list|
|xbps-|xbps-install -S||xbps-install -u|xbps-install -S »p»|xbps-remove «p»|xbps-remove -o|xbps-query -Rs «ex»|xbps-query -R «p»|xbps-query -l|
|yum|check-update|list updates|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|list installed|
|zypper|ref|lu|up|in «p»|rm «p»|rm -u|se «ex»|if «p»|se -i|

## Package Managers
|tool|install|
|---|---|
|rpm|rpm -i «pf».rpm|
|dpkg|dpkg -i «pf».deb|

## Usages
|tools|OSs|
|---|---|
|apk|Alpine Linux|
|dpkg,apt,apt-get/-cache|Debian, Ubuntu|
|pacman|Arch Linux, Manjaro|
|pkg|FreeBSD, GhostBSD|
|pkgin|NetBSD|
|pkg_|OpenBSD|
|rpm,yum,dnf|Red Hat, Fedora, CentOS|
|swupd|Clear Linux|
|xbps-install/-remove/-query|Void Linux|
|rpm,zypper|(open)SUSE|


## Other gotchas

### pacman
#### PGP errors
```
pacman-key --init
pacman-key --populate
```

