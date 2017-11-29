### privoxy intelligent_windows7

- ## config.txt
- ...
- listen-address 0.0.0.0:8118
- actionsfile WhiteList.action

- ## WhiteList.action
- # ss
- {+forward-override{forward-socks5 127.0.0.1:7070 .}}
- /
- # direct
- {+forward-override{forward .}}
- .baidu.com
- .chinaz.com
- .taobao.com
- ...



https://www.privoxy.org/user-manual/
