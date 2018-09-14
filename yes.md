# yes

yes命令在命令行中输出指定的字符串，直到yes进程被杀死。不带任何参数输入yes命令默认的字符串就是y。

## 语法
```bash
 yes [STRING]...
```

## 参数

字符串：指定要重复打印的字符串。

## 实例

删除文件时自动回答y
```bash
yes | rm -i *.txt 
```

快速生成大的文本文件
```bash
yes hello > hello.txt
```
