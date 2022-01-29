此项目介绍：

此项目仅仅是根据Corteza-local项目(Corteza 9.5本版)en语言，翻译成简体中文的。

目录介绍：
/my-corteza
为部署corteza的主目录。具体可根据corteza官方资料部署。

/my-corteza/my-locale/src
此目录实际存放这各个语言文件。

/my-corteza/my-locale/src/zh-CN
此目录才是翻译成简体中文的文件。后期只会维护该目录翻译文件。

/my-corteza/my-locale/src/.env
此文件中是：
LOCALE_PATH=../my-locale/src
LOCALE_LANGUAGES=zh-CN,en
LOCALE_DEVELOPMENT_MODE=true
调用简体中文翻译的配置及开启开发模式的配置。具体以Corteza官方资料为准。

/my-corteza/my-locale/src/docker-compose.yaml
此文件是部署Corteza测试环境docker-compose文件。（目前配合.env文件，可以正常使用）以官方资料为准。

/my-corteza/my-locale/src/readme.txt
此文件，是本人部署Corteza时，遇到的坑、翻译时用到的工具及参考链接。

有疑问，可以微信或邮箱联系。
微信：1278493814
邮箱：1278493814@qq.com

Corteza简介：
Corteza 是一个 100% 免费、开源、低代码的平台，用于构建组织的关键应用程序、提高其生产力并保护其数据和所有相关人员的隐私。 它完全是在公共领域开发的。 官方内置了CRM系统。

参考链接：
Corteza官方链接：https://cortezaproject.org/

