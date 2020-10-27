### Debian 用户不在sudoers中解决

1. 先进入超级用户

   ```
   su
   ```

2. 更改sudoers权限

   ```
   chmod 777 /etc/sudoers
   ```

3. 编辑sudoers文件

   ```
   vi etc/sudoers
   ```

4. 在root  ALL=(ALL:ALL) ALL下面添加一行

   ```
   用户名  ALL=(ALL:ALL) ALL
   ```

   保存，退出

5. 改回权限

   ```
   chmod 440 /etc/sudoers
   ```
6.记得改回权限！！！
   

