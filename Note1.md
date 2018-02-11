# 工作学习笔记

记录工作中的点滴，滴水汇聚成河

---

## QT

### qmake

#### 1.变量

  1.QT
  2.HEAD
  3.SOURCES
  4.LIBS
  5.ICON
  6.TEMPLATE
  7.OTHERFILES
  8.INCLUDEPATH
  9.DEPENDPATH
  10.PRE_TARGETDEPS
  11.RESOURCES
  12.OUT_PWD

### QT编译

[安装]
Nmake install

- 安装qt文档
1. nmake docs 
2. nmake install_doc

## BATCH-批处理

## NMAKE  

‘##’           --注释  
'\\'            --换行符  
'FORCE'        --既没有依赖的规则，其底下也没有可执行的命令。如果一个规则没有命令或者依赖，而且它的目标不是一个存在的文件名，在执行此规则时，目标总会被认为是最新的。也就是说，这个规则一旦被执行，make 就认为它所表示的目标已经被更新过。当将这样的目标(FORCE)作为一个规则的依赖时，由于依赖总被认为是被更新过的，所以作为依赖所在的规则定义的命令总会被执行. 
‘nmake -f’，‘--file’:--指定nmake所使用的输入文件  
--命令前要加Tab键  

‘$@’           --代表目标文件(target)  
'$^'           --代表所有依赖文件(components)  
‘$<’           --代表第一个依赖的文件(components中最左边的那个)  

[makefile讲解](https://wenku.baidu.com/view/2a6d7189c281e53a5802ffd4.html)  
[微软C/C++生成参考](https://msdn.microsoft.com/zh-cn/library/91621w01.aspx)  
## CL编译器
输出文件
'cl /Fi[file]' -- 命名预处理的文件  
'/Fo<file>'    -- 命名对象文件
'cl /Fp[file]' -- 命名.PCH文件
'cl /Yu[file]' -- 使用.PCH文件  
预处理器  
'cl /FI<file>' -- 命名强制包含文件  
  

## link  
'/NOLOGO'      -- 取消版权信息  
'/DYNAMICBASE' --使用地址空间布局随机化 (ASLR) 功能，指定是否生成可在加载时随机重新设定基址的可执行文件映像。
'/NOCOMPAT'     --将可执行文件标记为经验证与 Windows 数据执行保护功能兼容。
'/INCREMENTAL:NO' --控制增量链接
'/SUBSYSTEM'     --通知操作系统如何运行 .exe 文件。  
## lib：Library Manager 
## rc  

## VSCODE

- 快捷键
   |  描述  |  快捷键 |
   | - | :-:  | -:  |
   | 打开侧面预览  | Ctrl + Shift  +V  |
   | 打开控制台:     | Ctrl + Shift + C  |

- Markdown 语法
The cmd key in Windows is Ctrl

## LabWindows/CVI

- 编程

[下雪场景]
(http://www.eefocus.com/test-measurement/324920 )

## ARM

- TCP-IP协议栈：ETH-Lwip

https://www.cnblogs.com/firege/p/5805983.html

## 编程

0D:CR 回车键
0A:LF 换行
ASCII查表[百度百科](https://baike.baidu.com/item/ASCII/309296?fr=aladdin&fromid=19660475&fromtitle=ascii%E7%A0%81%E8%A1%A8)  

(./Picture/开机启动路径.png)