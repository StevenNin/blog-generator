---
title: Command Line 
date: 2019-06-02 17:01:16
categories:
- 笔记
tags:
- 命令行

---
 想混迹于代码世界，怎能不会一些简单的命令行
##  ls命令行 （list）
### ls ：查看当前路径下的显示文件

```
$ ls
1.txt  blog/  testVue/  two/
  ```
  ### ls -a ：查看当前路径下的所有文件，包括隐藏文件（list -all）
```
$ ls -a
./  ../  1.txt  blog/  testVue/  two/
<--此时新增的"./"和"../"就是隐藏的当前路径和父级路径-->
  ```
   ### ls -l ：查看当前路径下的文件的信息（list -longl）
```
$ ls -l
total 4
-rw-r--r-- 1 STEVEN 197121 0 6月   1 12:55 1.txt
drwxr-xr-x 1 STEVEN 197121 0 6月   1 15:12 blog/
drwxr-xr-x 1 STEVEN 197121 0 9月  26  2018 testVue/
drwxr-xr-x 1 STEVEN 197121 0 6月   2 00:41 two/
<--新增的文本就是关于文件的时间和权限信息-->
  ``` 
  ### ls -al ：查看当前路径下的所有文件（包括隐藏文件）的信息（list -all）
```
$ ls -al
total 16
drwxr-xr-x 1 STEVEN 197121 0 6月   1 19:20 ./
drwxr-xr-x 1 STEVEN 197121 0 6月   1 20:52 ../
-rw-r--r-- 1 STEVEN 197121 0 6月   1 12:55 1.txt
drwxr-xr-x 1 STEVEN 197121 0 6月   1 15:12 blog/
drwxr-xr-x 1 STEVEN 197121 0 9月  26  2018 testVue/
drwxr-xr-x 1 STEVEN 197121 0 6月   2 00:41 two/
<--就是 "-a" 和"-l"命令行的结合用法-->
  ```
##  cat命令行
### cat: 用于连接文件并打印到标准输出设备上
```
$ cat ./blog
cat: ./blog: Is a directory
  ```
  ##  mv命令行 (move)
  ### mv: 用来为文件或目录改名、或将文件或目录移入其它位置
```
$mv xxx aaa
<--将xxx文件名修改为aaa-->

$mv xxx/ aaa
<--将xxx目录放入aaa目录中，如果aaa目录不存在，则该命令将xxx改名为aaa-->
  ```
  ## touch命令行
  ### touch : 新建文件或更新文件时间
  ```
$ touch  vue.txt
<--在当前路径新建名为vue的txt文件-->
  ```
  #### 当然这是一些简单的随笔，我们是记不住所有的命令的
  #### 记忆模糊的就需要网上冲浪一下
   #### 推荐一个在线命令行解释的网站 [Explainshell](https://explainshell.com/)

![image.png](//static.xiedaimala.com/xdml/image/ef906d9a-e453-4255-b7e0-6d60d9ed3a3b/2019-6-2-16-58-48.png)
