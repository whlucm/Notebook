#Python 网络爬虫与信息提取
###1.requests库
pip install requests 安装
####1.1Requests库的七个主要方法
requests.request()　　:构造一个请求，支撑一下方法的基础方法    
request.get()　　　　　:获取HTML网页的主要方法，对应于HTTP的GET    
request.head()　　　　:获取HTML网页头信息的方法，对应于HTTP的HEAD   
request.post()　　　　:向HTML网页提交一个POST请求的方法，对应于HTTP的POST    
request.put　　　　　　:向HTML网页提交一个PUT请求的方法，对应于HTTP的PUT   
requests.patch()　　　　:向HTML网页提交局部修改请求，对应于HTTP的PATCH     
requests.delete()　　　:向HTML网页提交删除请求，对应于HTTP的DELETE
#####1.2Response对象的属性
![Markdown](http://p1.bqimg.com/1949/1dcf1184387f4f3f.png)   

使用GET获取资源的流程
r.status_code检查返回的response对象状态       
![Markdown](http://p1.bqimg.com/1949/93bec916b9c24641.png)
####1.3用法
r=requests.get(url) <font color="blue">例如：r=requests.get ("http://www.baidu.com")</font>
####1.4异常处理
![Markdown](http://p1.bqimg.com/1949/4155714d8d7a5d87.png)