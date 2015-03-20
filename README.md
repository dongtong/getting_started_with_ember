#Ember.js快速入门

##什么是Ember.js?

A framework for creating ambitious web applications

- 可以相对轻松地构建大型的web应用程序


- 最适合构建一些小的web应用程序

- 使用Ember.js的项目:

		www.discourse.org: 讨论主题的一个论坛
		https://squareup.com: 信用卡支付
		https://admanager.yahoo.com: 雅虎广告平台
		
- 如何学习使用Ember?

	1. 首先使用Ember构建一些小的应用
	2. 应用到小的Web App
	3. 在构建大一些，复杂一些的项目时，使用之前用到过的代码片段
	4. Ember的学习曲线比较大
	
- 特点

	1. 类似于Ruby on Rails框架的"convention over configuration",从许多JavaScript最佳实践中抽取出来
	2. 可以把它理解成一种"抽象"
	3. 一些小的代码片段可以完成比较复杂的功能
	
- Ember和MVC

	- Model: 描述数据类型，有哪些属性以及方法
	- View: 显示数据
	- Controller: 将数据发送到View
	- Router: 路由，通过一个路径找到Controller中对应的处理方法, Router是CoC的开始
	- Ember有时候可以认为是 = MVC + Router
	
- Ember和SPAs

	- 所有页面都被压缩到一个文件中
	- SPAs使用le许多HTML, CSS, JavaScript
	－ Ember使用缓存能很好的优化代码，第一次加载可能稍微慢一些，但是以后HTTP就从缓存中读取代码
