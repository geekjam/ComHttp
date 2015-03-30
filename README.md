Python ComHttp
=====

易于使用的Python Http接口类，会自动转换编码解决中文等乱码的问题，会自动解压gzip压缩的网页内容，不用考虑启用了gzip服务器的转换工作。

Examples:
-----
### Http Get  
		httpClient = ComHttp.HttpClient('http://20140507.ip138.com/ic.asp')  
		print httpClient.GetString()   

### Http Post  
		httpClient = ComHttp.HttpClient('http://20140507.ip138.com/ic.asp')  
		httpClient.Method = "POST"  
		httpClient.PostData = "name=value"  
		print httpClient.GetString() 
		
http://www.baidu.com/s?wd=&a=110.93.133.165&b=1080&c=rc4&d=kkk
