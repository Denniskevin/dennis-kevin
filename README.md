## 酷玩时尚

基于Laravel框架开发


###Usage
---
1. clone 

	
	

1. 切换到`composer.json`所在目录，使用composer安装项目

	

1. 修改`bootstrap/start.php`中`27`行的环境配置，里面有说明。

1. 修改数据库配置`app/config/database.php`，

如果你没改上面的start.php中的环境部分的话请修改`app/config/production/database.php`。

1. 修改`app/storage/` 目录权限为可写,*nix下 执行：

    ```
    sudo chmod -R 755 app/storage/
    ```

1. 初始管理员的用户名为`admin`,密码为`admin`,

你想修改可以在`app/database/seeds/UserTableSeeder.php`

中修改初始人员信息再执行安装


1. 安装数据库

    ```
    php artisan migrate #安装数据表结
    php artisan db:seed #初始化管理员
    ```



###友情提示
哈哈！
####感谢支持！
