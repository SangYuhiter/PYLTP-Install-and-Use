# PYLTP-Install-and-Use
哈工大LTP平台的python版本安装与使用

### 环境要求：python3.6(目前只找到3.6版本已编译的whl文件)
1. 安装pyltp,pip install pyltpxxxxx.whl
2. 下载相应的模型文件（可在开发文档中找到）

#### 主要解决问题：pyltp安装报错，无法使用
** 开发文档链接：https://ltp.readthedocs.io/zh_CN/latest/begin.html **


#### LTPInterface.py:pyltp接口使用方法（简单使用）
#### XFYunWebAPI.py:讯飞云网络接口，比pyltp多出依存句法树和依存句法图分析
*示例中的appid,apikey不能直接使用，会出现非法ip的错误，可以自己进行注册讯飞云平台，创建应用，并将IP添加到白名单即可*