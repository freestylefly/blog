---
layout: post
title: Eclipse 配置 Servlet 模板
categories: eclipse
description: Eclips e配置 Servlet 模板
tags:
	- eclipse
	- Servlet
---

有时候新建servlet时候会生成很多我们不是想要的东西，每一次都去复制黏贴，手动删除我们不想要的东西，那么如何设置专属自己的模板呢？只需要输入短短几个字，然后ALT+/即可：

这里以Eclipse4.5.2版本为例：

1.打开Eclilpse，Window->Preferences

2.Java->Editor->Templates->New

配置如图：



Pattern内容如下：
```java
package ${enclosing_package};
import java.io.IOException;
import javax.servlet.ServletException;
import javax.servlet.http.HttpServlet;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;
 
public class ${primary_type_name} extends HttpServlet {
 
	public void doGet(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
		response.getWriter().write("hello haohao...");
	}
 
	public void doPost(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
		doGet(request, response);
	}
}
```
勾选上“Use code formatter”->Apply->OK
3.重启Eclipse

4.使用Alt+/来快速匹配出模板，创建出简单清晰的Servlet

原文：https://blog.csdn.net/czkct/article/details/78750478 

------
# 本文章已同步至我的GitHub仓库：<a href="https://github.com/freestylefly/javaStudy">Javastudy</a>,期待您的加入:blush:
<img src="http://pp8g2fyug.bkt.clouddn.com/github.jpg" width=""/>

# 本文章已同步至<a href="https://freestylefly.github.io/">苍何的个人博客</a>,可以直接在博客上留言哦:blush:
<img src="http://pp8g2fyug.bkt.clouddn.com/myblog..png" width=""/>

# 来我的微信公众号玩耍呗:blush:
<img src="http://pp8g2fyug.bkt.clouddn.com/weixingongzhonghao.jpg" width=""/>

# 扫码无套路关注我的<a href="https://blog.csdn.net/qq_43270074?orderby=UpdateTime">CSDN</a>博客:blush:
<img src="http://pp8g2fyug.bkt.clouddn.com/CSDN.png" width=""/>

