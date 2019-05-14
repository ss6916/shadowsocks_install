![Shadowsocks](https://github.com/teddysunbackup/shadowsocks_install/raw/master/shadowsocks.png)
# Auto install Shadowsocks Server

shadowsocks.sh
===============
- Auto Install Shadowsocks(Python) Server for CentOS/Debian/Ubuntu
- https://web.archive.org/web/20190514071129/https://teddysun.com/342.html

```
wget --no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/teddysunbackup/shadowsocks_install/master/shadowsocks.sh
chmod +x shadowsocks.sh
./shadowsocks.sh 2>&1 | tee shadowsocks.log
```

shadowsocks-libev.sh
===============
- Auto Install Shadowsocks(libev) Server for CentOS
- https://web.archive.org/web/20190514070953/https://teddysun.com/357.html

```
wget --no-check-certificate -O shadowsocks-libev.sh https://raw.githubusercontent.com/teddysunbackup/shadowsocks_install/master/shadowsocks-libev.sh
chmod +x shadowsocks-libev.sh
./shadowsocks-libev.sh 2>&1 | tee shadowsocks-libev.log
```

shadowsocks-libev-debian.sh
===============
- Auto Install Shadowsocks(libev) Server for Debian/Ubuntu
- https://web.archive.org/web/20190514070919/https://teddysun.com/358.html

```
wget --no-check-certificate -O shadowsocks-libev-debian.sh https://raw.githubusercontent.com/teddysunbackup/shadowsocks_install/master/shadowsocks-libev-debian.sh
chmod +x shadowsocks-libev-debian.sh
./shadowsocks-libev-debian.sh 2>&1 | tee shadowsocks-libev-debian.log
```

shadowsocks-go.sh
===============
- Auto Install Shadowsocks(Go) Server for CentOS/Debian/Ubuntu
- https://web.archive.org/web/20190514071207/https://teddysun.com/392.html

```
wget --no-check-certificate -O shadowsocks-go.sh https://raw.githubusercontent.com/teddysunbackup/shadowsocks_install/master/shadowsocks-go.sh
chmod +x shadowsocks-go.sh
./shadowsocks-go.sh 2>&1 | tee shadowsocks-go.log
```

shadowsocks-crond.sh
===============
- Check Shadowsocks(All version) Server is running or not, and start it if not running
- https://web.archive.org/web/20190309150738/https://teddysun.com/525.html

```
wget --no-check-certificate -O /opt/shadowsocks-crond.sh https://raw.githubusercontent.com/teddysunbackup/shadowsocks_install/master/shadowsocks-crond.sh
chmod 755 /opt/shadowsocks-crond.sh
```

shadowsocksR.sh
===============
- Auto Install ShadowsocksR Server for CentOS/Debian/Ubuntu
- https://web.archive.org/web/20190203064434/https://shadowsocks.be/9.html
- ShadowsocksR一键安装脚本
- 使用root用户登录，运行以下命令：

```
wget --no-check-certificate https://raw.githubusercontent.com/teddysunbackup/shadowsocks_install/master/shadowsocksR.sh
chmod +x shadowsocksR.sh
./shadowsocksR.sh 2>&1 | tee shadowsocksR.log
```
- 安装完成后，脚本提示如下：

```Congratulations, ShadowsocksR server install completed!
Your Server IP        :your_server_ip
Your Server Port      :your_server_port
Your Password         :your_password
Your Protocol         :your_protocol
Your obfs             :your_obfs
Your Encryption Method:your_encryption_method

Welcome to visit:https://shadowsocks.be/9.html
Enjoy it!
```

shadowsocks-all.sh
==================
- Auto Install Shadowsocks Server (all version) for CentOS/Debian/Ubuntu
- https://web.archive.org/web/20190514070636/https://teddysun.com/486.html
- Shadowsocks 一键安装脚本（四合一）
- 使用root用户登录，运行以下命令：

```
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysunbackup/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```

安装完成后，脚本提示如下

```Congratulations, your_shadowsocks_version install completed!
Your Server IP        :your_server_ip
Your Server Port      :your_server_port
Your Password         :your_password
Your Encryption Method:your_encryption_method

Your QR Code: (For Shadowsocks Windows, OSX, Android and iOS clients)
 ss://your_encryption_method:your_password@your_server_ip:your_server_port
Your QR Code has been saved as a PNG file path:
 your_path.png

Welcome to visit:https://teddysun.com/486.html
Enjoy it!
```
- 卸载方法
- 若已安装多个版本，则卸载时也需多次运行（每次卸载一种）

- 使用root用户登录，运行以下命令：

```
./shadowsocks-all.sh uninstall
```

haproxy.sh
===============
- Auto Install haproxy for Shadowsocks Server
- https://web.archive.org/web/20180903174817/https://shadowsocks.be/10.html
- 使用haproxy中转Shadowsocks流量一键安装脚本
- 使用root用户登录，运行以下命令：
```
wget --no-check-certificate https://raw.githubusercontent.com/teddysunbackup/shadowsocks_install/master/haproxy.sh
chmod +x haproxy.sh
./haproxy.sh
```

Copyright (C) 2014-2019 Teddysun
