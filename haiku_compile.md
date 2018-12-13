# HaiKu 编译方法

## 环境

    brew install autoconf cdrtools gawk wget nasm less mpfr gmp libmpc bison mtools

## 获取源码

- buildtools
    
        git clone https://review.haiku-os.org/buildtools

- HaiKu

        git clone https://review.haiku-os.org/haiku

## 创建磁盘映像
使用 Mac 自带的 Disk Utility 新建磁盘映像，参数如下

![屏幕快照 2018-11-20 下午5.24.35](http://p4uro3cva.bkt.clouddn.com/屏幕快照 2018-11-20 下午5.24.35.png)

Name: haiku
Size: 至少 2.7 GB
Format:  Mac OS Extended (Case-sensitive, Journaled)
Encryption: 无
Partitions: 无
Image Format: 稀疏磁盘映像


将 buildtools/ 及 haiku/ 复制到 磁盘映像的根目录去


## 编译

### 工具构建
#### jam

    cd /Volumes/Haiku/buildtools/jam
    make
    sudo ./jam0 install
    [Enter your password]
    
使用
    
    jam -v

判断是否正常安装，正常结果如下

    Jam 2.5-haiku-20111222. OS=MACOSX. Copyright 1993-2002 Christopher Seiwald
   
#### gcc    
在 HaiKu 文件夹下

- 在独立文件夹下编译

        mkdir /Volumes/Haiku/haiku/generated; cd /Volumes/haiku/haiku/generated
        ../configure --build-cross-tools x86_64 ../../buildtools/

- 在 HaiKu 文件夹下编译

        ./configure --build-cross-tools x86_64 ../buildtools/
        
### 构建 HaiKu


    if [ `stat -c '%a' $sourceDir/data/system/boot/SetupEnvironment` -lt 644 ]; then
    if [ `stat -f '%a' $sourceDir/data/system/boot/SetupEnvironment` -lt 644 ]; then



- 适用于开发的系统(不包含应用程序)

        jam -q -j2 @image
        
    根据你的 CPU 情况配置 `-j2` 参数。
    
- 完整系统
        
        jam -q -j2 @nightly-raw
        
    根据你的 CPU 情况配置 `-j2` 参数。
        
        
编译时会下载一些文件
        
## 在虚拟机运行


## 参考资料

https://www.haiku-os.org/articles/2015-02-05_building_haiku_mac_os_x_1010_yosemite/

https://www.haiku-os.org/guides/building/get-source-git

https://www.haiku-os.org/guides/building/compiling-x86_64

https://www.haiku-os.org/guides/building/configure

https://github.com/pengphei/haiku-cn/wiki

