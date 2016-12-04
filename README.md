##说明
此安装包可在阿里云所有linux系统上部署安装。
此安装包包含的软件及版本为：
nginx：1.0.15、1.2.5、1.4.4（删除老版本1.0.4）
apache：2.2.22、2.4.2
mysql：5.1.73、5.5.35、5.6.15
php：5.3.18、5.4.23、5.5.7,5.6.11
php扩展：memcache、Zend Engine/OPcache
ftp：（yum/apt-get安装）
phpwind：8.7 GBK
phpmyadmin：3.2.2.2

## version 1.3.0 测试记录

以下为此脚本在阿里云linux系统测试记录（抽样测试）:
centos 5.8/64位/4核4G/50数据盘       --->测试ok
centos 5.8/64位/1核512M/30G数据盘    --->测试ok

centos 6.3/64位/1核512M/无数据盘     --->测试ok
centos 6.3/64位/4核4G/50G数据盘      --->测试ok

redhat 5.7/64位/4核4G/50数据盘       --->测试ok
redhat 5.7/64位/1核512M/无数据盘     --->测试ok


ubuntu 12.04/64位/4核4G/50G数据盘    --->测试ok
ubuntu 12.04/64位/1核512M/无数据盘   --->测试ok


debian 6.0.6/64位/1核512M/无数据盘   --->测试ok
debian 6.0.6/64位/1核512M/30G数据盘  --->测试ok

##安装步骤：
xshell/xftp上传到sh目录
1. chmod –R 777 sh
2. cd sh
3. ./install.sh
4. 选择版本并确认
5. 安装完成后请打开account.log文件，查看默认的数据库密码.

## 反馈
如果有什么使用问题、bug，或者建议，可联系作者：qrj@jiagouyun.com
