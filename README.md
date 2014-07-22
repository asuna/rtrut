## 一、简介

1. `rTorrent` + `ruTorrent` 一键安装包使用 `Linux Shell` 语言编写，用于在 Linux 操作系统上一键安装 `rTorrent` 和 `ruTorrent`。
2. `rTorrent` + `ruTorrent` 一键安装包基于前文 [《rTorrent + ruTorrent 安装和配置》](http://wangyan.org/blog/rtorrent-and-rutorrent-tutorial.html) 的步骤进行编写，如果要安装`ruTorrent`，那么要求支持PHP的Web环境已经配置好(仅支持Nginx)，否则安装出错。

## 二、下载地址

通过Git下载

    	git clone git://github.com/asuna/rtrut.git
    	cd rtrut && ./install.sh

## 三、安装步骤

1. 选择是否需要安装ruTorrent，默认值`y`，如果选择`n`，则跳至最后一步。
2. 选择是否需要支持ipv6，默认值`n`，请确认安装环境是否支持ipv6。
3. 输入IP或者域名，默认会自动获取，如果不准确请手动输入。
4. 选择网站根目录，比如：/`home/wwwroot`或者`/home/wwwroot/default`
5. 输入Nginx配置文件绝对路径，LNMP一键安装包的默认值是：
    `/usr/local/nginx/conf/nginx.conf`
6. 按任意键开始安装，可以按+c退出。

## 四、来源    
>   Script:[https://github.com/wangyan/rtrut](https://github.com/wangyan/rtrut)    
>	ipv6 patch:[https://github.com/JohnFlowerful](https://github.com/JohnFlowerful)