Use Zabbix Monitor vCenter
---
- Import the Two Templates to Zabbix  
- Add vCenter to Zabbix and Use the "Template VMware Host Discovery"  
- Change the Macros of template "Template VMware Host Discovery"  
```
{$URL} => https://{HOST.IP}/sdk   
{$USERNAME} => *vCenter User With Read_Only At least   
{$PASSWORD} => *User Password   
```
Import the Dashboard json to Grafana(version 5.x)
---
- Change the Data Source which you Env Used  
- Change the Variables to your Env Used  

Now Show
---
