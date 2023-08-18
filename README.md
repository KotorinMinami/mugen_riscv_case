# mugen-riscv 测试例脚本修改补丁存放仓库

## 存放形式
以patch的形式存放，对应文件的相对路径与mugen对应脚本的相对路径一致，patch文件生成命令：
```
$ diff -up path/to/上游脚本 path/to/已修改脚本 > path/to/脚本.patch
```
