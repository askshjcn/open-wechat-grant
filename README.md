# 微信第三方平台开发：授权流程

说明文章见：<http://www.zhangjiee.com/blog/wechat-open-grant>

运行环境：

+ Python3
+ Django 1.11.6
+ SQLite3
+ Redis

使用时注意：

+ 授权事件接收URL：`http://$domain_name/wechat/auth_callback/`
+ 授权页面：`http://$domain_name/auth/`
