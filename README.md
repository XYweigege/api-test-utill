# wc 库可以使用命令快捷的请求数据

1.kevinapi

选择是否从缓存读取 Y 读取 N 取消 如果没有使用过建议 N

2.选择请求方式 GET POST 等.....

3.选择请求头 application/x-www-form-urlencoded application/json 等

4.输入请求资源路径 也就是 url

5.请输入 token 没有请忽略

6.输入参数如果是 get 可以忽略

7.选择返回格式(默认 json) text blob buffer

8.是否缓存 Y 缓存 N 取消 缓存起来可以下次直接使用

成功返回 success

失败 error

# 快捷发送请求

kevinapi get

输入 url 即可

kevinapi post

输入 url

输入参数

Commands:

get 快捷发起 get 请求

post 快捷发起 post 请求

ws 可以测试 ws webSocket 请求；

del 删除缓存
