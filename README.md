# socks5-for-serv00
在 Serv00 和 CT8 机器上一步到位地安装和配置 SOCKS5 & nezha-agent。

## 如何使用？

### nohup模式
- 一键安装 **新手小白用这个！**
```bash
bash <(curl -s https://raw.githubusercontent.com/imm0jwr/tsss/refs/heads/main/install-socks5.sh)
```
----

----
## Github Actions保活
添加 Secrets.`ACCOUNTS_JSON` 变量
```json
[
  {"username": "xx1", "password": "7HEt(xeRxttdvgB^nCU6", "panel": "panel4.serv00.com", "ssh": "s4.serv00.com"},
  {"username": "xx2", "password": "4))@cRP%HtN8AryHlh^#", "panel": "panel7.serv00.com", "ssh": "s7.serv00.com"},
  {"username": "xx3", "password": "%Mg^dDMo6yIY$dZmxWNy", "panel": "panel.ct8.pl", "ssh": "s1.ct8.pl"}
]
```
