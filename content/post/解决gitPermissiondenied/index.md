+++
title = '解决gitPermission denied'
date = 2024-06-09T19:20:19+08:00
draft = true
+++

# 解决 git@github.com: Permission denied (publickey).

```shell
 vim ~/.ssh/id_rsa.pub
 copy the ssh key
 Go to the github settings
 Select the option ssh keys
 Remove the old ssh keys not used anymore.
 Add a new ssh key.
```

如果没有`id_rsa.pub`

```shell
ssh-keygen -t rsa -C "xx@example.com"
```
