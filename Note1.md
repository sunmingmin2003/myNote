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
‘make -f’，‘--file’:--指定nmake所使用的输入文件  
'make -n'  --  
'cl -g'    --  
'rm -f','--force' -- 强制删除
--命令前要加Tab键  

‘$@’           --代表目标文件(target)   
'$^'           --代表所有依赖文件(components)  
‘$<’           --代表第一个依赖的文件(components中最左边的那个)  

[makefile讲解](https://wenku.baidu.com/view/2a6d7189c281e53a5802ffd4.html)

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

## GIT GITHUB

### git 拉取和获取pull,和fetch区别  

获取最新版本,有两种拉取 和 获取 pull 和 fetch
git pull: 从远程拉取最新版本到本地,自动合并merge,git pull origin master

git fetch:从远程获取最新版本到本地,不会自动合并merge,  
git fetch origin master  
git log -p master ../origin/master,      
git merge orgin/master  
实际使用中  使用git fetch 更安全,在merge之前可以看清楚更新情况,再决定是否合并  
