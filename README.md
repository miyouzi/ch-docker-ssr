ShadowsocksR for Docker
===========

拷贝自https://github.com/shadowsocksr/shadowsocksr

原来的Dockerfile有点小问题，以下是Dockerfile的更改：

	将		mv /tmp/shadowsocks-manyuser/shadowsocks ~/shadowsocks \
	
	改至	mv /tmp/shadowsocksr-manyuser/shadowsocks ~/shadowsocks \
	
	ssserver设置：
	
		Port:2333
		
		method:helloworld666
		
		obfs:tls1.2_ticket_auth
		
		protocol:auth_aes128_md5
		
		
		
		
自用。可直接在daocloud.io套用。