# HTTP基本原理

1.URI:Uniform Resource Identifier=

URL:Uniform Resource Locator+URN:Universal Resource Name(只命名而不指定如何定位资源)

Example： https://github.com/favicon.ico 为URI/URL, https+访问路径（/根目录）+资源名称favicon.ico

2.超文本：即网页源代码HTML

3.http，https，ftp，sftp，smb，为协议类型

http: hyper text transfer protocal 超文本传输协议

https：hyper text transfer protocal over secure socket layers http的安全版，传输的内容经过ssl加密：保证数据传输安全，确认网站的真实性

爬取报“您的链接不是私密连接”https时，需要设置忽略证书的选项，否则会提示SSL链接错误
