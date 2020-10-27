### Debian切换中文

1. ```
   sudo apt install locales
   ```

2. ```
   dpkg-reconfigure locales
   ```

3. 选择`zh_CN.UTF-8`（空格选择，回车确定）

4. 安装字体

   ```
   apt install xfonts-intl-chinese xfonts-wqy
   ```

5. 安装输入法

   ```
   apt install fcitx fcitx-googlepinyin
   ```

6. 重启，`ctrl+space`切换输入法

