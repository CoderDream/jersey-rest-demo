
jersey-rest-demo readme




----------



----------
# 测试1 #

http://localhost:8080/jersey-rest-demo/rest/hello

- 返回
Hello Jersey

jersey-rest-demo 增删改查

工程地址：http://localhost:8080/jersey-rest-demo/
源代码：
查找：

	1. 直接访问
地址：http://localhost:8080/jersey-rest-demo/rest/contacts/



	2. PostMan访问
地址：http://localhost:8080/jersey-rest-demo/rest/contacts/



新增：

	1. 通过页面添加：
新增：http://localhost:8080/jersey-rest-demo/pages/new_contact.jsp

查询：http://localhost:8080/jersey-rest-demo/rest/contacts



	2. 通过Chrome的插件PostMan


方法PUT
语法
http://localhost:8080/jersey-rest-demo/rest/contacts/<newId>
链接http://localhost:8080/jersey-rest-demo/rest/contacts/abcHeader参数Content-Type : application/json请求的json
{
    "id": "abc",
    "name": "123"
}





修改：

	1. 修改记录


方法PUT语法
http://localhost:8080/jersey-rest-demo/rest/contacts/<newId>
链接http://localhost:8080/jersey-rest-demo/rest/contacts/abcHeader参数Content-Type : application/json请求的json{
    "id": "abc",
    "name": "12345"
}




	2. 查看更新后的结果


方法
GET
语法
http://localhost:8080/jersey-rest-demo/rest/contacts/<newId>
链接
http://localhost:8080/jersey-rest-demo/rest/contacts/abc
Header参数
Accept : application/json
返回的json
{
    "id": "abc",
    "name": "12345"
}





删除：

	1. 删除记录


方法DELETE语法
http://localhost:8080/jersey-rest-demo/rest/contacts/<newId>
链接http://localhost:8080/jersey-rest-demo/rest/contacts/abcHeader参数Content-Type : application/json




	2. 查看更新后的结果


方法
GET
语法
http://localhost:8080/jersey-rest-demo/rest/contacts/<newId>
链接
http://localhost:8080/jersey-rest-demo/rest/contacts/abc
Header参数
Accept : application/json










