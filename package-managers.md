# Package Managers

### Placeholders
- `«p»` - package name
- `«pf»` - package file
- `«re»` - regular expression

## Frontends
|tool|update|upgradable|upgrade|install|remove|prune|search|info|installed|
|---|---|---|---|---|---|---|---|---|---|
|pkg|update|upgrading|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|info|
|apt|update|list --upgradable|upgrade|install «pe»|remove «pe»|autoremove|search «re»|show «p»|list --installed|
|yum|check-update|list --upgrades|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|list --installed|
|dnf|check-update|list --upgrades|upgrade|install «p»|remove «p»|autoremove|search «re»|info «p»|list --installed|
|pacman|-Sy|-Qu|-Syu|-S «p«|-R «p«|-Rsn $(pacman -Qdtq)|-Ss «re»|-Qi «p»|-Qe|

## Package Managers
|tool|install|
|---|---|
|rpm|rpm -i «pf».rpm|
|dpkg|dpkg -i «pf».deb|

## Usages
|tool|OSs|
|---|---|
|pkg|FreeBSD, OpenBSD|
|apt|Debian, Ubuntu|
|dpkg|Debian, Ubuntu|
|yum|Red Hat, CentOS, Fedora|
|pacman|Arch Linux, Manjaro|
|dnf|Red Hat, CentOS, Fedora|
|rpm|Red Hat, CentOS, Fedora|

