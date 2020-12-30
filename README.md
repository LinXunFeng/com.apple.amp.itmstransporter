## 使用



> `username` 为你当前电脑登录的用户名

1. 打包下载整个仓库，解压后把 `com.apple.amp.itmstransporter` 目录放到 `/User/username/Library/Caches/` 目录下，如果已经有该目录，则直接覆盖。
2. 将 `com.apple.amp.itmstransporter` 目录下 `/obr/2.1.0/` 目录下的 `repository.xml` 文件中的所有 `lxf` 修改为当前电脑登录的用户名。
3. 重开 `Transporter` 上传 `ipa` 文件即可。



## 高速下载

当前仓库的  `com.apple.amp.itmstransporter.zip` 同步更新至 https://www.lanzous.com/b0aqkmhpg



## 记录

更新 `com.apple.amp.itmstransporter` 的命令

```shell
/Applications/Xcode.app/Contents/SharedFrameworks/ContentDeliveryServices.framework/itms/bin/iTMSTransporter
```

1. 将`/User/username/Library/Caches/` 目录下的`com.apple.amp.itmstransporter` 删除掉
2. 执行命令
3. 使用  `Transporter` 上传 `ipa` 
4. 取出纯净内容