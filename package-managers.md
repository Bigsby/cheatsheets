# Package Managers

### Placeholders
- `«p»` - package name
- `«pf»` - package file
- `«re»` - regular expression
- `«ex»` - file system wild card expression

## Frontends
|tool|update|upgradable|upgrade|install|remove|prune|search|info|installed|
|---|---|---|---|---|---|---|---|---|---|
|pkg|update|upgrading|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|info|
|apt|update|list --upgradable|upgrade|install «pe»|remove «pe»|autoremove|search «re»|show «p»|list --installed|
|yum|check-update||upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»||
|dnf|check-update|list --upgrades|upgrade|install «p»|remove «p»|autoremove|search «ex»|info «p»|list --installed|
|pacman|-Sy|-Qu|-Syu|-S «p»|-R «p»|-Rsn $(pacman -Qdtq)|-Ss «re»|-Qi «p»|-Qe|
|zypper|ref|lu|up|in «p»|rm «p»|rm -u|se «ex»|if «p»|se -i|
|apk|update|upgrade||add «p«|del «p«||search »re»|info »p»|info|
|swup|check-update||update|bundle-add «p»|bundle-remove «p»||search »re»|bundle-info «p»|bundle-list|
|xbps|xbps-install -S||xbps-install -Su|xbps-install -S »p»|xbps-remove «p»|xbps-remove -o|xbps-query -Rs «ex»|xbps-query [-R] «p»|xbps-query -l|
## Package Managers
|tool|install|
|---|---|
|rpm|rpm -i «pf».rpm|
|dpkg|dpkg -i «pf».deb|

## Usages
|tools|OSs|
|---|---|
|pkg|FreeBSD, OpenBSD|
|dpkg,apt|Debian, Ubuntu|
|rpm,dnf|Red Hat, Fedora|
|rpm,yum|CentOS|
|pacman|Arch Linux, Manjaro|
|zypper|(open)SUSE|
!apk|Alpine Linux|
|swupd|Clear Linux|
|xbps|Void Linux|
