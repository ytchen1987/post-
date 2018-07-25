# post-
post提交数据方式

HTTP 请求分为三个部分： 状态行，请求头，消息主体

<b>状态行：</b>

请求链接
请求方法
请求地址
请求状态

<b>请求头：</b>

cookie   (大小在4KB)


//服务器端设置
Cache-Control   //no-cache  对比缓存 （304状态）  no-store 强制缓存
Last-Modified /If-Modified-Since
Etag/If-None-Match
Content-type



<b>提交数据格式</b>

application/x-www-form-urlencoded <br />
application/json <br />
multipart/form-data  //使用于文件上传<br />
text/xml  <br />



//
JSON.stringify(xx)  //将对象json字符串化

JSON.parse(xx)  //将json字符串 转化成对象
