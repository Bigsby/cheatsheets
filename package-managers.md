# Package Managers

### Placeholders
- `«p»` - package name
- `«pf»` - package file
- `«re»` - regular expression

## Frontends
|tool|update|upgradable|upgrade|install|remove|prune|search|info|installed|
|---|---|---|---|---|---|---|---|---|---|
|pkg|pkg update|pkg upgrading|pkg upgrade|pkg install «p»|pkg remove «p»|pkg autoremove|pkg search «re»|pkg info «p»|pkg info|
|apt|apt update|apt list --upgradable|apt upgrade|apt install «pe»|apt remove «pe»|apt autoremove|apt search «re»|apt show «p»|apt list --installed|
|yum|yum check-update|yum list --upgrades|yum upgrade|yum install «p»|yum remove «p»|yum autoremove|yum search «re»|yum info «p»|yum list --installed|
|dnf|dnf check-update|dnf list --upgrades|dnf upgrade|dnf install «p»|dnf remove «p»|dnf autoremove|dnf search «re»|dnf info «p»|dnf list --installed|

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
|dnf|Red Hat, CentOS, Fedora|
|rpm|Red Hat, CentOS, Fedora|

