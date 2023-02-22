# Git 使用教程

- 关于cd命令：每次cd 均应该步步深入，不可一步到达。

例如：

```git
cd D:  %第一个步骤
cd Git %第二个步骤
cd glados_batfile %第三个步骤
```

- 关于git设置的用户名和邮箱：

```git
$ config --global user.name Chain

$ config --global user.email lzcchen@zju.edu.cn

同时也可以用 git config --list看
```

- 关于执行bat文件命令

```git
./Push_modify.bat
```

- 本人将git的本地仓库保存在了 /d/Git/glados_batfile/.git 中

故可能会显示glados_batfile(master)

****

### 建立Git和Github之间的交互

1.保存git ssh密钥的路径：/c/Users/Chain/.ssh/id_rsa

2.设置passphrase: no passphrase(都是按Enter回车键)

```git
Chain@LAPTOP-9IHTRMOU MINGW64 /d/Git/glados_batfile (master)
$ ssh-keygen -t rsa -C "lzcchen@zju.edu.cn"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Chain/.ssh/id_rsa):
Created directory '/c/Users/Chain/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Chain/.ssh/id_rsa
Your public key has been saved in /c/Users/Chain/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:KBwzDbR7sW9q0bFW64DNC+H61/EVd1z/czW/R09gogM lzcchen@zju.edu.cn
The key's randomart image is:
+---[RSA 3072]----+
|   .o            |
|     +          .|
|    = o        .o|
|   . =.+E . . +.*|
|    +.+*S= o o +*|
|     o=.B =   ..*|
|     . +o= + . o=|
|    . .oo o .  .o|
|     oo.        .|
+----[SHA256]-----+
```

****

参考文献：

[(1条消息) Git（2）-- Git安装后首次配置与第一次使用Git和Github管理自己的代码（超详细纯小白图文教程）_BugMiaowu2021的博客-CSDN博客](https://blog.csdn.net/m0_46278037/article/details/118815158)
