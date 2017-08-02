# Java爬取煎蛋网妹子图
* 不使用爬虫框架，只需会用HttpClient和正则表达式即可爬取
* 可自定义开始页面以及爬取页数，以及存放地址
* 得到图片存放在D:/meizi文件夹下，每页单独一个文件夹，路径可在类中修改
* 练手项目，仅供娱乐，多线程，代理Ip等暂时不会T_T
+调用run方法抓取，如不指定页数则默认抓取10页
+	run()抓前10页
+	run(x)抓取前x页
+	run(x,y)抓取从x到y页，终止页码1500

# Git clone 以后，用maven导入
* eclipse导入maven项目方法：
* http://blog.csdn.net/w12345_ww/article/details/52094756