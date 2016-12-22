## 查询 用户openId等   |  /user/thirdparty/getOpenId


##### 接口说明
获取微信用户的openId

| | |
|:---:|:-------------|
| 调用地址 | /user/thirdparty/getOpenId |
| 授权类型 | 对外开放API |
| 请求方法 | GET |
---

##### 请求参数

---

| 参数 | 必选 | 说明 |
|:-------------:|:-------------|:-------------|
| code | Y | 微信传的code |




##### 返回结果

---


```

{
  "data": {
    "scope": "snsapi_base",
    "expires_in": "7200",
    "openid": "oWCm9wOkk82Bx-6ivuY_HhSMPeXI",
    "refresh_token": "2_mULKM5w1iQbGWqCtoiU2ATsJyeqE6AbsNEYaiBqcLn-zUsnhn9JtnUirkRBi9wA94I2CI3IbGUvlms30miLNW8vx0lEbmwJoQkX-qonws",
    "access_token": "5c4RwuAnKwBO2Zy0g84wAq3AAPD88HGUGJQbwjHuP-FdonS8hDhh5pZ1Jfw6iriybY3KWrmO9shMDQbCj8Qkpy3I3EVSa8rGzyFMjbIa2_Q"
  },
  "code": 200,
  "error": "",
  "elapsedMilliseconds": 0
}

```
