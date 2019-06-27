# 管理系统接口

版本号|修改人|修改时间|修改项
:---|:---:|:---|:---
1.0|任宝杰|2019-6-27|初版

## 用户
### 登录
接口用途:   
接口鉴权: 否  
测试地址: https://api.baojie.ink/login  
正式地址: https://api.baojie.ink/login  
请求方式: POST  
请求参数:
```json
{
	"phone":"18585131312",
	"password":"142536"
}
```
返回结果:
```json
{
    "code": 0,
    "msg": "成功"
}
```
### 注册
接口用途:   
接口鉴权: 否  
测试地址: https://api.baojie.ink/signUp  
正式地址: https://api.baojie.ink/signUp  
请求方式: POST  
请求参数:
```json
{
	"phone":"18585131312",
	"password":"142536"
}
```
返回结果:
```json
{
    "code": 0,
    "msg": "成功"
}
```
### 修改密码
接口用途:   
接口鉴权: 是  
测试地址: https://api.baojie.ink/signUp  
正式地址: https://api.baojie.ink/signUp  
请求方式: POST  
请求参数:
```json
{
	"phone":"18585131312",
	"password":"142536" //新密码
}
```
返回结果:
```json
{
    "code": 0,
    "msg": "成功"
}
```

# 小程序接口