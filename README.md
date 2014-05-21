ComHttp
=======

python ComHttp
[+]Examples:  
	[-]Http Get  
		httpClient = ComHttp.HttpClient('http://20140507.ip138.com/ic.asp')  
		print httpClient.GetString()  

	[-]Http Post  
		httpClient = ComHttp.HttpClient('http://20140507.ip138.com/ic.asp')  
		httpClient.Method = "POST"  
		httpClient.PostData = "name=value"  
		print httpClient.GetString()  
