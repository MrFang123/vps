# 域名的创建

* [网站链接（需要外网）](https://www.dynu.com/zh-CN)

## 创建方式

注册完成后进入控制台

![avatar](/image/DomainControl.png)

![avatar](/image/DomainAdd.png)

![avatar](/image/DomainName.png)

![avatar](/image/DomainAddress.png)

```bash
# 网站api，需要在vps执行
# 当创建新的vps时执行此代码则自动将主机和域名绑定 
curl "https://api.dynu.com/nic/update?hostname=域名&password=密码" 
# 例如，申请的域名为www.xxx.com（不需要http://）网站的登陆密码为mima 
# curl "https://api.dynu.com/nic/update?hostname=www.xxx.com&password=mima" 
```