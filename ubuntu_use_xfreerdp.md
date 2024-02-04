### install
```shell
sudo apt update && sudo apt install freerdp2-x11 -y
```
### connect to your window
```shell
sudo xfreerdp /v:windows_machine_ip /u:username /p:your_win_passwd
#example open a window rdp with height:width -> 1920x1050
xfreerdp /v:192.168.73.119 /u:M9 /p:123 /w:1920 /h:1050
```
### more details in here link
[a blog about ubuntu connect to window with rdp protol](https://phoenixnap.com/kb/ubuntu-rdp-to-windows)

[freerdp offical github](https://github.com/FreeRDP/FreeRDP)

#### example
```shell
# -*- encoding: utf-8 -*-
#!/bin/bash
xfreerdp /v:192.168.x.x /u:username /p:your_passwd /w:1920 /h:1045  /sound:sys:oss,dev:1,format:1 /clipboard /f

# voice /sound:sys:oss,dev:1,format:1
# clipboard /clipboard
# fullscreen /f
```
