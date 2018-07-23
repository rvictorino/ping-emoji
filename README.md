# ping-emoji
Simplified and emojified ping command output
```shell-script
🏓(){ping "$@" | sed 's/: icmp_seq=[0-9]\+ ttl=[0-9]\+ time/ ⏱ /g; s/^[0-9]\+ bytes from /👋 /g;'}
```
