# 工具介绍

这个是Nessus破解插件更新脚本，但是：

__非默认安装位置，需要配置update_config配置文件里的路径！__

# 工具的使用

官网下载Nessus：https://www.tenable.com/downloads/nessus

安装网上教程一大堆，自己百度，安装包还是官网下载比较好，插件嘛没办法只能用破解的。

其实基本都是下一步，只要注意两点，1是Choose how you want to deploy Nessus. Select a product to get started.这里选则最后一个Managed Scanner。2是，Managed by那里选Tenable.sc，就好了（这里没有截图，懒）。

插件可以官网下载试用7天的插件包。

工具的使用就是修改update_config的路径，然后运行"Nessus破解插件更新.bat"程序。

然后按照提示输入破解插件包路径，插件包是.tar.gz的文件。

![image-20220510094316644](images/image-20220510094316644.png)

再按照提示，把更新后的版本号复制粘贴输入上去回车。然后静静的等着就好了。

![image-20220510095010073](images/image-20220510095010073.png)

然后浏览器访问https://127.0.0.1:8834/ 或者 https://localhost:8834/ 登录Nessus，查看插件的版本是不是更新的版本，使用数量是不是无限制。

![1667444300183](images/1667444300183.png)

这里插一嘴。这个版本貌似和templates目录下的json文件有关系，和plugin_feed_info.inc文件好像没多大关系。

![1667444406314](images/1667444406314.png)

再新建任务看看插件是否真的在，在就说明更新成功了。

![1667444348160](images/1667444348160.png)
