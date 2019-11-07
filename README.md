# learning
# Cookie登录注册demo

## 启动应用
`node server.js 8001`

注册页：http://localhost:8001/sign_up

登录页：http://localhost:8001/sign_in

首页：http://localhost:8001

## Cookie特点：

1. 服务器通过Set-Cookie响应头设置Cookie；
2. 浏览器得到Cookie之后，每次请求都要带上Cookie；
3. 服务器读取Cookie就知道登录用户的信息。