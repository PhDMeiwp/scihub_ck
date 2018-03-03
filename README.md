# scihub_ck

一个简版的Sci-hub可用域名检查工具。

Scihub_ck is a tiny tool for checking the working domain of sci-hub. Sci-Hub is a website with over 64.5 million academic papers and articles available for direct download. In 2015 academic publisher Elsevier filed a legal complaint in New York City against Sci-Hub alleging copyright infringement, and the subsequent lawsuit led to a loss of the original sci-hub.org domain. Following the first domain loss, Sci-Hub has cycled through a number of domains, some of which have been blocked in certain countries.
For check the working domains timely, I developed the tiny tool based on Shell and Perl.

## Usage

使用方法：

`perl scihub_ck`


## Description

列表文件包括262个域名后缀供检查。运行产生的文件将保存在web文件夹内。程序运行完成后，保留大小为27kb的文件即为可用域名。

The list file contained 262 domains to check. The output file will be generated into the 'web' directory. The files with 27 kb are corresponding to the working domains.


## Working domains

> Update every 30 minutes. Daily maintenance at 00:30

Online version is available now: https://wadauk.github.io/scihub_ck/index.html


## Versions

### v1.0.0

local version

本地版发布


### v1.0.1

add online version

增加在线版


### v1.0.2

add pipeline shell script for local version

增加本地版流程脚本


### v1.0.3

speed up and shorten the update cycle for online version

提速并缩短在线版更新周期

### v1.0.4

move the codes from pi to cloud and speed up

代码迁移至阿里云并提速

