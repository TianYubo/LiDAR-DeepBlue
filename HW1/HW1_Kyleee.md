# 深蓝学院激光 SLAM 第一次作业

## 1. 了解 SLAM 系统

### 1) 列举三个你常用的 Linux 命令，并说明他们的功能

- cd: `cd [directory name]`切换当前工作目录。并且这个 directory name 既可以为相对目录，也可以是绝对目录。
- ls: 显示指定工作目录下所包含的内容。其中可以使用不同的参数 `ls [-alrtAFR] [name]`
- cp:` cp [options] source dest` 复制文件以及目录

### 2) 一句话简要介绍 Vim 的功能，如何在 Vim 中进行插入和删除，如何保存并退出 Vim？

- VIM 是一款可配置的文本编辑器，旨在非常有效地创建和更改任何类型的文本
- 按 `i` 键进入 INSERT 模式，就可以进行修改和插入了。删除既可以直接在命令模式下用 x 键删除，也可以在进入 INSERT 模式的时候用 Backspace 或者 delete 进行删除。
- 保存并退出文件： `:wq`

### 3) 列举两种常用的 Linux 压缩和解压缩命令

- `tar`
  - `tar -cf 111.tar.gz *.png` 将目录中所有`.png`的文件打包成 `111.tar`,并且将其用 gzip 进行压缩，生成一个 gzip 压缩过的包，命名为 `111.tar.gz`
  - `tar -xf 111.tar`: 解压出 `111.tar` 当中所有的文件
- `zip / unzip`
  -  `zip` 命令是压缩文件（.zip 格式）
  -  `unzip` 命令是解压文件

## 2. 了解 ROS

![](/home/kyletian/LiDAR/HW1/figures/Screenshot from 2023-02-12 22-41-25.png)

## 3. 代码：基础数学坐标转换

![](/home/kyletian/LiDAR/HW1/figures/Screenshot from 2023-02-18 20-31-17.png)

![](/home/kyletian/LiDAR/HW1/figures/Screenshot from 2023-02-18 20-31-26.png)