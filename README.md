# mp3c
Compress mp3 files to reduce their size. By default, the target frame rate will be 11025hz.

Usage:
- Compress all mp3 files in the current directory
```shell
$ mp3c.py *
```

- Compress sample.mp3 file
```shell
$ mp3c.py sample1.mp3 sample2.mp3
```

Requirements to run the script:

- Install [ffmpeg](https://ffmpeg.org/)
```shell
$ brew install ffmpeg --with-libvorbis --with-ffplay --with-theora
```
- Install [pydub](https://github.com/jiaaro/pydub)
```shell
$ pip install pydub
```

windows 处理
先安装ffmpeg， 可以参照博客 https://blog.csdn.net/u010825190/article/details/125042088

1. 官网下载
官网

![image](https://user-images.githubusercontent.com/7889062/193176407-e91d0c97-f117-48fb-bf46-31c76e297342.png)
![image](https://user-images.githubusercontent.com/7889062/193176431-697c84a5-b6d5-4f45-b877-13aad5ac10b2.png)


2. 安装
2.1. 解压
下载完成，解压到磁盘
![image](https://user-images.githubusercontent.com/7889062/193176466-79ee6318-f119-48dc-b7c9-fcca142415af.png)


2.2. 环境变量
新增环境变量FFMPEG_HOME，指向解压包目录
![image](https://user-images.githubusercontent.com/7889062/193176515-d522acbf-7b55-44ed-ba4c-10ef60853ca2.png)

然后在Path中指向bin目录
![image](https://user-images.githubusercontent.com/7889062/193176565-91d55017-440e-4c2b-b592-a59ca1dcf17f.png)


2.3. 验证是否安装成功
打开命令行窗口，输入ffmpeg -version出现以下界面说明安装成功
![image](https://user-images.githubusercontent.com/7889062/193176535-fa1cc1db-0712-40fb-b907-e114db885a12.png)

