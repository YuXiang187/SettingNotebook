# ArchLinux零碎积累

### 1.解压命令

* tar.gz

  ```bash
  tar -xzvf file
  ```

* tar.xz

  ```bash
  tar -xvJf file
  ```

### 2.压缩命令

压缩文件夹：

```bash
zip -r zipname.zip file/
```

压缩文件：

```bash
zip zipname.zip file
```

### 3.强制杀死进程

1. 用`ps`命令查看进程

   ```bash
   ps -ef
   ```

   ```bash
   ps -ef | grep firefox # 指定程序名
   ```

2. 用`kill`命令杀死进程

   ```bash
   kill -s 9 1827
   ```

   其中`9`是给程序发送信号：强制、尽快终止进程

### 4.设置任务栏透明度

安装`InkScape`

```bash
sudo pacman -S inkscape
```

打开主题文件夹编辑svg即可
