===========无法访问github网站，需要如下操作============
地址查询网站：https://github.com.ipaddress.com/

host 文件修改：
C:\Windows\System32\drivers\etc
地址查询网站：

github.com
140.82.113.4
140.82.113.4

github.global.ssl.fastly.net
199.232.69.194

assets-cdn.github.com
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

============host文件添加如下代码================

#映射github
140.82.113.4 github.com
140.82.112.3 github.com
199.232.69.194 github.global.ssl.fastly.net
185.199.108.153 assets-cdn.github.com
185.199.109.153 assets-cdn.github.com
185.199.110.153 assets-cdn.github.com
185.199.111.153 assets-cdn.github.com