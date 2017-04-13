# 第一步：在浏览器输入URL

URL:统一资源定位符，用于定位互联网上的资源

URl 常用的四种协议：

-http：（HyperText Transfer Protocol)超文本传输协议，是互联网上应用最为广泛的一种网路协议。

-ftp： （File Transfer Protocol）文本传输协议

-file：（File Transfer Protocol）文件传输协议

-fttps：（Hyper Text Transfer Protocol over Secure Socket Layer）http 的安全版，加密版

#第二步域名解析

域名解析是通过解析域名找到网址所在服务器的ip

域名解析的流程：1、浏览器缓存 – 浏览器会缓存DNS记录一段时间/2、系统缓存 - 从 Hosts 文件查找是否有该域名和对应 IP。/3、路由器缓存 – 一般路由器也会缓存域名信息。/4、ISP DNS 缓存 – 比如到电信的 DNS 上查找缓存。/5、如果都没有找到，则向根域名服务器查找域名对应 IP，根域名服务器把请求转发到下一级，直到找到 IP，定位到服务器

#第三步服务器处理

服务器接收用户的request.交给网址代码，或者接受请求反向代理到其他服务器。

#第四步：网站处理

MVC 模型(model)-视图(view)-控制器(controller）

#第五步：浏览器处理

解析返回的代码，HTML字符串被浏览器接受后被一句句读取解析

解析到link 标签后重新发送请求获取css

解析到 script标签后发送请求获取 js，并执行代码

解析到img 标签后发送请求获取图片资源

#第六步绘制网页

浏览器根据 HTML 和 CSS 计算得到渲染树，绘制到屏幕上

js 会被执行
