### 方法一

+ 进入office安装目录

  ```
  C:\Program Files (x86)\Microsoft Office\root\Office16
  ```

+ 以管理员身份运行cmd，输入下列命令后，会出现激活剩余时间```REMAINING```和激活类型配置```Activation Type Configuration```

  ```
  cscript ospp.vbs /dstatus
  ```

  

### 方法二

win + R输入信息

```
slmgr.vbs /dlv // 最为详细的激活信息，包括激活ID,安装ID,激活截止日期
slmgr.vbs /dli // 操作系统版本，部分产品密钥，许可证状态
slmgr.vbs /xpr //是否永久激活
```

