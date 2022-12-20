## 概述
前端开发 WEB Front-end Development
后端开发 WEB Back-end Development

### HTML
超文本标记语言
HyperText Markup Language
HTML 没有逻辑 不是编程语言

#### HTML说明
HTML标签：小写
属性名： 小写
属性值: 用双引号包裹

#### 基础结构
```html
<html>
    <head>
        <!-- 
			title->
				限制 30 ~ 40字
			内容显示->
				主页：网站名称 + 主要的关键字/关键字的描述
				详情页：详情名称 + 网站名称 + 简介
				列表页: 分类名称 + 关键字 + 网站名称
				文章页：标题 + 分类 + 网站名称
                用逗号做分割
			可参考京东->
		-->
        <!--
			keywords->
				100个字符 小写逗号隔开
				网站名称 + 分类信息
		-->
        <!--
			description->
				网页描述信息 80~120汉字
				一般就是综合title + keywords的简单描述
		-->
        <title></title>
        <meta name="keywords" content=""/>
        <meta name="description" content="" />
    </head>
    <body>
        
    </body>
</html>
```
#### title keywords descript优先级
	搜索引擎认知的优先级
	title > description > keywords
	现在的网站会弱化keywords
#### 单标签

<br />
<hr />
<img />
<input />

#### 双标签
<h1>h1~h6</h1>
<p></p>
<a></a>
<div></div>
<span></span>