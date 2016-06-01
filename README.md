## 介绍

JQTools，为 Jason Qt Tools 的简称

这是一个基于Qt开发的开源小工具包。

包含了在开发程序（尤其是Qt程序）时，需要的各种小功能。

本工具使用 QML(界面) 和 C++(逻辑) 开发，源码均已开源在了GitHub上。

GitHub地址：https://github.com/188080501/JQTools

若不想下载源码编译，也可以点击这里直接下载可执行文件：
 
https://github.com/188080501/JQTools/releases/latest

若需要其他版本，请下载源码自行编译。 

方便的话，帮我点个星星，或者反馈一下使用意见，这是对我莫大的帮助。

若你已经有了更好的建议，或者想要一些新功能，可以直接邮件我，我的邮箱是：Jason@JasonServer.com

或者直接在GitHub上提交问题：
https://github.com/188080501/JQTools/issues

## 开发计划

类别|功能|计划完成日期
---|---|---
文本类|UTF16转换|已完成
文本类|RGB转16进制|已完成
文本类|大小写转换|已完成
文本类|密码随机器|已完成
文本类|URL转码|已完成
文本类|JSON格式化|2016-06
||
计算类|HASH计算器|已完成
计算类|Unix时间戳转换|已完成
计算类|屏幕二维码解析器|2016-06
||
制作类|图标生成器|已完成
制作类|图标字体转PNG|2016-06
||
工具类|代码行数统计|已完成
工具类|屏幕拾色器|2016-07
工具类|局域网文件传输|2016-09
工具类|局域网远程构建|2016-09
||
Qt相关|PNG警告消除|已完成
Qt相关|Q_PROPERTY代码生成器|2016-06
Qt相关|TS文件自动翻译器|2016-09

## 功能介绍

* PNG警告

	消除在Qt里，部分PNG图片在加载时控制台会报警告的问题，使用本工具可以将PNG图片进行转换，使用转换后的图片不会在报错。

* UTF16转换

	将字符串和UTF-16之间进行互转，例如将 "中文" 和 "\u4E2D\u6587" 互转。

* HASH计算器

	计算常用的摘要值，如SHA1、MD5。
	
* RGB转16进制

	可以从HEX颜色字符串（例如"#112233"）分别提取RGB的值或者分别根据RGB值组成HEX颜色字符串。
	
* 大小写转换

	文本转大写、文本转小写。

* Unix时间戳转换

	Unix时间戳与日期转换。
	
* 代码行数统计

	可以统计文件中代码行数（'\n'数量）。

* 图标生成器

	根据已有的PNG图片，生成可以用于发布App的特定分辨率图片，例如OSX的 icon_128x128@2x.png 这样分辨率的图片。

* 屏幕二维码解析器

	可以解析屏幕上的二维码，并显示结果字符串。

* 图标字体转PNG

	将ttf字体或者svg字体，转换为PNG。
	
* 密码随机器

	可以生成随机密码字符串，例如："Hau-eqS-5EC-kWD"
	
* URL转码

	将字符串和编码后的URL之间进行互转，例如将 "中文" 和 "%E4%B8%AD%E6%96%87" 互转。
	
* Q_PROPERTY代码生成器

	可以根据Q_PROPERTY的内容，生成代码。
	
* 屏幕拾色器

	可以拾取屏幕中，某个点的颜色。
	
* 局域网文件传输

	可以在局域网中传输文件。
	
* 局域网远程构建

	可以在局域网中远程控制其他电脑编译代码，并传回编译结果。
	
* TS文件自动翻译器

	可以使用百度翻译，自动翻译TS文件并保存翻译结果。