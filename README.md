简介
====
BGCC（百度通用通信组件）是一个跨语言、跨平台、面向对象的高性能轻量级RPC框架。

    1.具有自定义的接口描述语言和代码生成引擎

    2.支持事务级别的服务端消息主动推送

    3.消息流监控

    4.变态的效率


源码目录结构
====

|  文件/目录名称        |               作用                   |

|adapter                | 存放生成bgcc.jar及libbgcc4j.so的源码 |

|bgcc                   | 存放生成libbgcc.so和libbgcc.a的源码  |
----------------------------------------------------------------
|bgcc_build_windows.bat | BGCC在Windows平台上的自动编译脚本    |
----------------------------------------------------------------
|bgcc.sln、bgcc.vcproj  | BGCC在Windows平台上的VS2003工程文件  |
----------------------------------------------------------------
|bidl2sl                | 用于存入生成工具bidl2sl的源码        |
----------------------------------------------------------------
|build.py               | BGCC使用Python语言的自动编译脚本     |
----------------------------------------------------------------
|Makefile               | BGCC在Linux平台下自动编译脚本        |
----------------------------------------------------------------
|sample                 | 代码使用示例                         |
----------------------------------------------------------------
|set_vs_var.bat         | VS2003环境变量设置脚本               |
----------------------------------------------------------------

代码示例
====
请参见源码sample目录。

安装
====
请参见bgcc manual文档。文档下载网址：http://bgcc.baidu.com


