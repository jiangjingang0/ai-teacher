项目部署：

1、将项目代码clone到本地，添加python解释器，推荐pyrhon3.10

2、本项目基于Django开发，下载Django包，终端执行pip install Django

3、下载项目需要依赖的包，如：openai、django-cors-headers等，按照项目import的爆红逐个下载

4、可申请自己的openai api key，在项目app01/.env里面替换为自己的

5、项目启动成功后，浏览器输入127.0.0.1/test/

openai api key 申请：

先申请一个openai 的账号，申请教程可百度，申请时需要科学上网。申请成功后访问这个网址https://platform.openai.com/account/api-keys ，点击create new secret key获取openai api key（记得保存到其他地方，这里点击之后将无法查看）
