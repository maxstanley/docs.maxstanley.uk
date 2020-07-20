# Setting NTP Servers

Find some NTP Servers for your region and add the to the NTP argument, in a space separated list.

```
# /etc/systemd/timesyncd.conf
[Time]
NTP=0.ntp.server 1.ntp.server
FallbackNTP=0.fallback.ntp 1.fallback.ntp
```

```
sudo timedatectl set-ntp true
timedatectl status
```
