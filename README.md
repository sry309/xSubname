# xSubname
关联域名查找脚本，通过securitytrails.com反查NS记录、SOA记录以及MX记录，在继续查找其子域名。

首先进行DNS域传送漏洞检查，然后获取关联域名，再获取各个关联域名的子域名，最后批量解析查询到的子域名，获取IP地址、所在地、ISP、ASN网段、ASN描述信息、简单端口扫描、尝试获取HTTP状态码、httpserver及网页标题，并保存到csv文件方便进一步筛选目标。

![截图1](https://img2018.cnblogs.com/common/1718715/202001/1718715-20200113205050144-2146189701.png)  
![截图2](https://img2018.cnblogs.com/common/1718715/202001/1718715-20200113205021752-1709796515.png)  
![截图3](https://img2018.cnblogs.com/common/1718715/202001/1718715-20200113205141269-676737958.png)
