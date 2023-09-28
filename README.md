## 简易版本的文件上传

### 环境要求

1. python3任意版本
2. 无三方依赖

### 功能介绍

1. 文件下载
2. 文件上传

### 快速上手

1. 服务启动

   默认监听地址为0.0.0.0:8080
   ```shell
   python3 main.py
   ```
   指定监听地址
   ```shell
   python3 main.py 127.0.0.1 8080
   ```
   

2. 文件下载

    ```shell
    curl -O http://ip:port/filename
    ```

3. 文件上传

    ```shell
   curl -F file=@filename http://ip:port
    ```