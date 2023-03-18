### Yes, I"m being lazy by calling all PLC/ICS/SCADA just ICS. Same for Credentials equaling passwords,access,etc.

|Category|Query|Explanation|More|
|----|----|----|----|
|RDP|"\x03\x00\x00\x0b\x06\xd0\x00\x00\x124\x00"|Windows RDP. Usually protected by a 2nd login||
|ICS|"Server: gSOAP/2.8" "Content-Length: 583"|Charging stations for EV||
|ICS|"HID VertX" port:4070|networked access controller with a multi-door access control panel|https://www.hidglobal.com/products/v10000|
|ICS|title:"netbotz appliance"|Used to control building automation or network closets|https://www.apc.com/us/en/product-range/61832-netbotz-400/|
|ICS|port:5006,5007 product:mitsubishi|CPU # identifies the model of the PLC. |[https://www.tkkcorporation.com/mitsubishi/q-series-plc.htm](https://emea.mitsubishielectric.com/fa/products/cnt/plc/plcq/cpu/cpu/q03udvcpu.html#downloads)|
|ICS|Press Enter Setup Mode port:9999|Lantronix devices with admin interface open, NO PASSWORD required.|https://www.lantronix.com/products-class/serial-to-ethernet-device-servers/|
|ICS|"privileged command" GET|Damn fuel pump connected to the internet allowing access to its command line interface...||
|VNC|"authentication disabled" "RFB 003.008"|VNC ... version 3.3?. Regardless, no authentication|https://www.exploit-db.com/exploits/36932|
|VNC|Port:"5900" Authentication disabled|Also VNC with no authentication||
|SMB|"Authentication: disabled" port:445|SMB with no authentication||
|TOR|"X-Your-Address-Is:"|Can also use http.title:"This is a Tor Exit Router" or http.title:"Onion router" as well but this capture more of them in one search.||
|Database|port:9200 "indices" "production"|Elastic Search critical indices are accessible to the internet|https://www.elastic.co/guide/en/elasticsearch/reference/current/important-settings.html|
|Telnet|"root@" port:23 -login -password -name -Session|already logged in as root...||
|Database|port:5432 PostgreSQL|PostgreSQL database||
|Database|"Home - Mongo Express"|Open Mongo Express Panels||
|NetBios|"NetBIOS Response"|NetBIOS service running and accessible on the Internet. These services have the potential to be used in amplification attacks by criminals that wish to perform denial of service attacks.|https://www.chrislockard.net/posts/netbios-name-spoofing-and-smb/|
|FTP|"230 login successful" port:"21"|FTP services without logins||
|Credentials|"admin+1234"|Default credentials listed in banner||
|Credentials| "default password"|Default credentials. Normally hacked||
|Credentials|" Default  Name:admin  Password:1234 "|Default credentials. Normally hacked||
|Credentials|html:"def_wirelesspassword"|default credentials again.||
|Router|"Cisco_CCSP_CWMP_TCPCR"|The cookie usually gives away version and path information. use banner grabbing in order to find network hosts that are running versions of applications and operating systems with known exploits |https://www.cisco.com/c/en/us/products/cloud-systems-management/media-gateway-controller-node-manager/index.html|
|Router, AP|mikrotik streetlight|Let's cry together. These are street lights that are also access points ...|
|Router|"ActiontecBHR"|Actiontech routers|passwords for different modles are here: https://portforward.com/actiontec/passwords/|
|Error Codes|http.title:"401 Unauthorized" |The server generating a 401 response MUST send a WWW-Authenticate header field containing at least one challenge applicable to the target resource. I normally combine this with negation to remove unwanted hits, use ports or county codes. The point to this search is authenication was POSSIBLE but didn't happen because the wrong thing was sent.|https://kinsta.com/knowledgebase/401-error/
|Camera|"TVIP51500"|CCTV camera|https://www.usermanuals.au/abus/tvip51500/manual|
|Camera|"everfocus"|IP Camera|https://www.everfocus.com/|



Other Resources of use:
- https://github.com/equalitie/shodan_fingerprinter/blob/master/signatures.json
