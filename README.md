# git host backup

## TL;DR

```sh
git clone https://github.com/multicast/ghb.git /opt/ghb
cp /opt/ghb/rsync.conf /etc/ghb.rsync
echo BACKUPDIR=/var/backups/ghb > /etc/ghb.conf
echo GITREMOTE=ssh://myhost/backups/$(hostname).git >> /etc/ghb.conf
```
