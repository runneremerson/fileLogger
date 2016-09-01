fileLogger
==========

fileLogger是一个基于[Go](http://golang.org/)开发的可自动分割文件进行备份的异步日志库

[![Go Walker](http://gowalker.org/api/v1/badge)](http://gowalker.org/github.com/runneremerson/fileLogger)

Features
--------
* 日志文件可按文件大小进行备份,可定制文件大小和数量
* 日志文件可按日期进行备份
* 两种使用模式:
    * 不同类型log分别写入不同的文件，使用Print(),Printf(),Println()三个方法
    * 不同类型log写入一个文件，但不同LEVEL的日志具有不同的颜色，使用T(),I(),W(),E()等方法，默认日志LEVEL为TRACE


Installation
------------

安装FileLogger使用"go get"命令
    
    go get github.com/runneremerson/fileLogger
    
只基于[Go](http://golang.org/)标准库，不依赖第三方库


Update
------

更新FileLogger使用"go get -u"命令

    go get -u github.com/runneremerson/fileLogger

Usage
-----

用法请参考[example](https://github.com/runneremerson/fileLogger/tree/master/example)

API
---

请参考[Go Walker](https://gowalker.org/github.com/runneremerson/fileLogger)



License
-------

FileLogger基于 [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
