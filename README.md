# ping-emoji
Emojified but very unhandy ping command output
```shell-script
🏓(){ping "$@" | sed 's/: icmp_seq=[0-9]\+ ttl=[0-9]\+ time/ ⏱ /g; s/^[0-9]\+ bytes from /👋 /g;'}
```
## Usage
```console
~$🏓 127.0.0.1                                                   
PING 127.0.0.1 (127.0.0.1) 56(84) bytes of data.
👋 127.0.0.1 ⏱ =0.068 ms
👋 127.0.0.1 ⏱ =0.061 ms
👋 127.0.0.1 ⏱ =0.061 ms
```
