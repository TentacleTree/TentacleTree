### Environment Setting

#### 1. xfs prjquot for docker volume




修改

修改 grub 参数，就是后面追加上` rootflags=pquota`
```cfg
GRUB_CMDLINE_LINUX_DEFAULT="quiet rootflags=pquota"
GRUB_CMDLINE_LINUX="rootflags=pquota"
```

生成grub配置
```shell
grub-mkconfig -o /boot/grub/grub.cfg
```



### Development
#### NodeJS
https://github.com/nodesource/distributions/blob/master/README.md#debuninstall

#### golang install 
https://go.dev/doc/install

