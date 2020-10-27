### Android安装问题

> 出现黑屏一直进不到页面

1. 开机后选择第二个选项![在这里插入图片描述](https://gitee.com/co-code/imgs_bed/raw/master/imgs_bed/20190419000651431.png)

2. 所有信息刷完之后，回车，并输入

   ```
   mount -o remount,rw /mnt
   ```

3. 再输入

   ```
   vi /mnt/grub/menu.lst
   ```

4. 在如图位置加上代码![在这里插入图片描述](https://gitee.com/co-code/imgs_bed/raw/master/imgs_bed/20190422212706339.png)

5. 保存退出，重启



在如图同一行代码后面也可以修改分辨率

![在这里插入图片描述](https://gitee.com/co-code/imgs_bed/raw/master/imgs_bed/20190422212950417.png)

