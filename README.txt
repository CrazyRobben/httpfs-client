httpfs-client util
httpfs-client is a client tool of HttpFS server which provides a REST HTTP gateway to HDFS with full
filesystem read & write capabilities,httpfs-client read & write hdfs filesystem with the webhdfs REST HTTP API
	
example
please read com.catt.httpfs.client.httpclient.Demo and org.apache.hadoop.fs.http.client.Demo

Requirements:
  * JDK 1.6.*
  * Maven 3.*
  
How to build:
	Clone this Git repository. 
	
	Run 'mvn package'.

  	The resulting TARBALL will under the 'target/' directory.
  	
功能说明:
	1  包com.catt.httpfs.client.httpclient是采用commons-httpclient.jar,
	    基于http请求实现的，没有使用到hadoop相关的jar
	2  包org.apache.hadoop.fs.http.client根据httpfs项目的源代码，
	    根据需要修改了一下，使用了hadoop相关的jar
  
 Reference
	http://cloudera.github.com/httpfs/
 	
 Contact me
 	http://my.oschina.net/cloudcoder
 	欢迎各位多提宝贵意见，并贡献你的力量

