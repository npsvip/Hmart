# Hmart
简约自适应电子商城系统，针对虚拟商品在线发货，支持企业微信通知

# 前端
![1](https://github.com/npsvip/Hmart/assets/95081538/88affbe0-2645-45d4-b9b9-9bbceb048fc5)

<img width="1676" alt="2" src="https://github.com/npsvip/Hmart/assets/95081538/5af2df05-7cee-4dc4-8460-a3bb93fbef76">


# 后端
<img width="1678" alt="image" src="https://github.com/npsvip/Hmart/assets/95081538/4fe8889e-628a-42f2-a203-bdcd20a97bf1">

<img width="1677" alt="image" src="https://github.com/npsvip/Hmart/assets/95081538/60000c36-4c1b-45a3-99da-c81451d08061">


# H2 console
<img width="458" alt="image" src="https://github.com/npsvip/begger/assets/95081538/f03147ff-241b-415e-bf5b-2c561a6f902f">

<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/2ede27d6-1789-4cd4-a1bf-f5d2b5ddf623">

<img width="1675" alt="image" src="https://github.com/npsvip/Hmart/assets/95081538/ce6429ad-4fb9-48cd-8262-fc7fe82f0a21">

<img width="1678" alt="image" src="https://github.com/npsvip/Hmart/assets/95081538/c71cd934-3c76-477b-8d57-49ebedd609ef">

<img width="1676" alt="image" src="https://github.com/npsvip/Hmart/assets/95081538/b5df324e-f287-4142-8c08-b65b9ad58dd8">

<img width="1676" alt="image" src="https://github.com/npsvip/Hmart/assets/95081538/c9ae4a30-ce49-44af-91cf-89d3cbbc97b5">


# 运行命令
```
docker run -d --name beggar --restart=always -p 8080:8080 -e console=true -v /opt/beggar/log/:/opt/logs/beggar/ aeert/beggar:latest
```
日志目录&nbsp;&nbsp;&nbsp;&nbsp;/opt/logs/beggar/<br/>
H2 console&nbsp;&nbsp;&nbsp;true 打开<br/>
H2数据库&nbsp;&nbsp;&nbsp;&nbsp;/beggar.mv.db 

# 访问信息
前端地址&nbsp;&nbsp;&nbsp;&nbsp;http://localhost:8080<br/>
后端地址&nbsp;&nbsp;&nbsp;&nbsp;http://localhost:8080/admin/<br/>
后端账户密码&nbsp;&nbsp;随意输入，之后会保存H2数据库<br/>
H2 console地址&nbsp;&nbsp;&nbsp;&nbsp;http://localhost:8080/h2<br/>
H2 console&nbsp;&nbsp;JDBC URL: jdbc:h2:./beggar

# 支付平台
目前对接的是&nbsp;&nbsp;<a href="https://pay.npsvip.cn" target="_blank">蓝鲸支付</a>

# 版权信息
Begger遵循 MIT License 协议，提供免费使用，请勿用于商业及非法用途,Begger不承担个人行为的任何违法责任。
