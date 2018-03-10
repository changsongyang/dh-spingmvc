
<br>
<img src="https://github.com/hdonghong/dh-spingmvc/blob/master/resouces/1.png" alt="" width="225"/>
<br>

![npm (tag)](https://img.shields.io/badge/author-hdonghong-blue.svg) ![Travis](https://img.shields.io/badge/java-1.8-brightgreen.svg)

# 简介
<p>一个简单版本的SpringMVC框架，阅读SpringMVC源码后尝试模仿实现的。</p>

# 目录
*	[1.功能]
*	[2.配置]
*	[3.campuscard]
*	[4.taskmanagement]
*	[5.maildemo]
*	[6.webStore]

# 环境
JDK 8

# 功能
	实现了SpringMVC常用的五个注解：
	@DhController：标注bean类为controller层，当没有使用@DhRequestMapping时起value值可作为请求映射路径默认值为标记类的简单名，首字母小写。
	@DhService：标注bean类为service层，默认值为标记类的简单名，首字母小写。
	@DhRequestMapping：映射请求地址
	@DhQualifier：注入bean实例，默认值为bean实例实现类的简单名，首字母小写。
	@DhRequestParam：数据绑定后台控制层获取参数，可为空，现支持类型有String，Integer，Float，Double。
<br>

# 配置
	<b>web.xml</b>
	<img src="https://github.com/hdonghong/dh-spingmvc/blob/master/resouces/2.png" alt="" height="360"/><br/>
	
	<b>dh-springmvc的配置文件</b>
	<img src="https://github.com/hdonghong/dh-spingmvc/blob/master/resouces/3.png" alt="" height="160"/><br/>


# 测试
	<img src="https://github.com/hdonghong/dh-spingmvc/blob/master/resouces/4.png" alt="" height="360"/><br/>

# 运行
	<b>前台</b>
	<img src="https://github.com/hdonghong/dh-spingmvc/blob/master/resouces/5.png" alt="" height="240"/><br/>
	
	<b>后台</b>
	<img src="https://github.com/hdonghong/dh-spingmvc/blob/master/resouces/6.png" alt="" height="360"/><br/>

# 博客
	待...

