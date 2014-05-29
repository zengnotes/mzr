Mzr
=========
基于Toropress衍生而来的图站源码.是Lihuashu.com的开发代号,
在阿里云上线后流量增速非常快,但鉴于国内的环境,运营一段时间后收到阿里云发出的照会,
此种类型的网站有政策风险,于是梨花树的图站版本被迫下线..

#第二版安装请先更新安装beego和xorm

    go get -u github.com/astaxie/beego
    go get -u github.com/lunny/xorm

##第一版安装请先更新torgo

    go get -u github.com/insionng/torgo

##安装
	先安装sqlite3驱动，譬如64位的win7：
	SQLITE3驱动编译环境是TDM版MINGW64(http://tdm-gcc.tdragon.net/)，
    安装好后请把TDM版MINGW64的bin目录路径加入到你的win7环境变量path里面。

	
	go get -u github.com/mattn/go-sqlite3

    下载toropress源码后解压并cd切换目录到 toropress目录下，然后执行go build app.go，编译好后，运行./app即可。
    默认用户:root,默认密码:rootpass
