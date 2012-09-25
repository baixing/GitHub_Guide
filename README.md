关于权限
========

##官方说明
https://help.github.com/articles/what-are-the-different-access-permissions

##权限系统
* 和linux文件系统的权限几乎一样，
* member和team类比linux上的user和group
* 权限管理的基本单位是Team
* 一个Team内部每个人的权利是完全一样的
* 一个人可以属于若干个Team
* 一个人只要属于Organization中任意一个Team，即算做组织成员。

##三种权限
* push
* pull
* Admin

##Owner组：  
* 等于此Organization的超级管理员
* 拥有最大的所有的操作权限（包括删除整个Organization）
* 每个人的权利是平等的
* 付款和授权由Owner负责
* 管理员的很多操作都不会显示是哪个管理员干的，在Dashboard上都显示为  baixing do XXXX 10 minutes ago

##Admin组
* 官方推荐的做法，和Owner分开
* 开新Repo的人
* 有权删掉自己开的Repo

关于Private Repo
================
* Private的Repo即使被Fork了，Fork出来的也还是Private的
* 如果Fork某个Priavte Repo到自己名下，就算被取消了Repo的读权限，你的Fork依然可用，只是不能更新了。
* **管理员有权删掉Private Repo的任意一个Fork!**
* Private Repo的Fork是不能把状态改成Public的（管理员也不能）
* 综上所述： Private Repo还是很安全的！

* 关于命令行下https提示登陆的问题：推荐用OAuth解决，详见http://developer.github.com/v3/oauth/  


关于系统安全  
============
* 系统操作记录：  
* https://github.com/organizations/baixing/settings/security  
* 数据备份：  
* 不需要单独备份，每份Ckeckout出来的git都能用于恢复原始数据！  


一本关于GitHub的电子书
======================
http://www.worldhello.net/gotgithub/index.html
大部分东西都讲得挺清楚的，不过有些内容有点老。
这些文档也开源了~ 有空去提个Pull Request~
https://github.com/gotgit/gotgithub
