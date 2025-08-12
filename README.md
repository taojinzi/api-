# api-
php代码实现随机图片api接口 |自适应设备图片

下载源码，根目录解压
挑选合适的图片上传至pc和az文件夹
<img src="域名">(默认302调用）
接口支持URL、JSON、XML、302跳转以及直接显示图片的形式调用，其中URL是直接显示图片链接，302是访问API时会跳转到图片文件的链接。

示例:域名/az.php?mom=url（ index.php 自行改动）

演示站 https://api.webphub.com

玩法 
调用单个图片  
<img src="http://你的域名.com">
调用多个图片  
<img src="http ://你的域名?mom=1">
<img src="http ://你的域名?mom=2">
<img src="http ://你的域名?mom=3">
<img src="http ://你的域名?mom=4">
<img src="http ://你的域名?mom=5">

或者http:// api.webphub.com/1.php 
新建个php文件 内容代码是这个 同时调用5个图片
<img src="http ://你的域名?mom=1">
<img src="http ://你的域名?mom=2">
<img src="http ://你的域名?mom=3">
<img src="http ://你的域名?mom=4">
<img src="http ://你的域名?mom=5">  
1 2 3 4 5 随便写
