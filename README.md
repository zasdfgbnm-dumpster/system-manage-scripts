我自己用的系统管理用的脚本
=========================

1.内核管理脚本
---------------

脚本名称：kernel

### 使用方法

更改内核配置： kernel config

重新编译内核： kernel rebuild

如果使用了第三方模块，需要修改kernel文件把编译第三方模块的代码加到rebuild_post中


2.chroot前挂载脚本
------------------

脚本名称：mount-chroot
