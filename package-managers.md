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
|yum|check-update|list --upgrades|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|list --installed|
|dnf|check-update|list --upgrades|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|list --installed|
|pacman|-Sy|-Qu|-Syu|-S «p»|-R «p»|-Rsn $(pacman -Qdtq)|-Ss «re»|-Qi «p»|-Qe|
|zypper|ref|lu|up|in «p»|rm «p»|rm -u|se «ex»|if «p»|se -i|

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
|rpm,yum,dnf|Red Hat, CentOS, Fedora|
|pacman|Arch Linux, Manjaro|
|zypper|(open)SUSE|

