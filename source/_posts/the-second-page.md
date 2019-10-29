---
title: the second page
date: 2019-10-24 23:43:09
tags:
---


### 公共部分
##### 接口名称:user get
##### URL:/eeop/iam/user/get
##### HTTP请求方式:GET/POST

<!-- more -->

### 请求内容参数
参数名|必选|字段类型及范围|字段描述及说明
---|---|---|---
id|false|String|用户ID
### Content-Type
##### application/x-www-form-urlencoded;charset=UTF-8
### 请求格式示例
```
/eeop/iam/user/get?appKey=***&sign=***&id=***&token=***
```
### 请求格式说明
```
```
### 返回结果格式
```
Json
```
### 返回结果示例

成功：
```json
{ 
    'status': 0, 
    'msg': 'success',
    'user':{
        'id':'abc123',
        'name':'chjiang',
        'phone':'123456789',
        'email':'changhua.jiang@envisioncn.com'
    }
}
```
失败:
```json
{
    'status': 10006, 
    'msg': 'fail msg'
}
```
### 返回结果说明
status|0:正常，10000+：失败
---|---
msg|失败说明
user.id|用户ID
user.name|用户名
user.phone|用户手机
user.email|用户邮箱
### java实例
```java
IAMUserGetRequest request = new IAMUserGetRequest();
IAMUserGetResponse response = client.execute(request, token);
```