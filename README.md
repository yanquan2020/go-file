# Go File
## 描述
文件分享工具，可用于局域网内分享文件，直接跑满本地带宽。

## 特点
1. 无需配置环境，仅单个可执行文件，直接双击即可开始使用。
2. 自动打开浏览器，分享文件快人一步。
3. 提供二维码，可供移动端扫描下载文件，告别手动输入文件。

## 使用方法
直接双击即可使用，默认端口为 `3000`，默认的 token（用于删除文件时验证身份）为 `token`。

如果需要修改端口，加参数即可：`./lan-share.exe -port 80 -token private`。

## 演示
![desktop](https://user-images.githubusercontent.com/39998050/107188251-50aed700-6a22-11eb-9ee9-e8242f1850b8.png)
![mobile](https://user-images.githubusercontent.com/39998050/107188296-61f7e380-6a22-11eb-9324-a394abd49b25.png)

## 其他
[Node.js 版本在此](https://github.com/songquanpeng/lan-share)