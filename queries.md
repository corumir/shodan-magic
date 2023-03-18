|Category|Query|Explanation|More|
|----|----|----|----|
|RDP|"\x03\x00\x00\x0b\x06\xd0\x00\x00\x124\x00"|Windows RDP. Usually protected by a 2nd login||
|ICS|"Server: gSOAP/2.8" "Content-Length: 583"|Charging stations for EV||
|ICS|"HID VertX" port:4070|networked access controller with a multi-door access control panel|https://www.hidglobal.com/products/v10000|
|VNC|"authentication disabled" "RFB 003.008"|VNC ... version 3.3?. Regardless, no authentication|https://www.exploit-db.com/exploits/36932|
|VNC|Port:"5900" Authentication disabled|Also VNC with no authentication||
|SMB|"Authentication: disabled" port:445|SMB with no authentication||
|Elastic Search|port:9200 "indices" "production"|critical indices are accessible to the internet|https://www.elastic.co/guide/en/elasticsearch/reference/current/important-settings.html|
|FTP|"230 login successful" port:"21"|FTP services without logins||
|Credentials|"admin+1234"|Default credentials listed in banner||
|Credentials| "default password"|Default credentials. Normally hacked||
|Crdentials|" Default  Name:admin  Password:1234 "|Default credentials. Normally hacked||
|Cisco|"Cisco_CCSP_CWMP_TCPCR"|The cookie usually gives away version and path information. use banner grabbing in order to find network hosts that are running versions of applications and operating systems with known exploits |https://www.cisco.com/c/en/us/products/cloud-systems-management/media-gateway-controller-node-manager/index.html|
