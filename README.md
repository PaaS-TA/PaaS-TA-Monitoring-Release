# PaaS-TA-Monitoring-Release Guide

## 1. Github Repository 및 mariadb Package Download
```
 $ git clone https://github.com/PaaS-TA/PaaS-TA-Monitoring-Release.git
 
 cd PaaS-TA-Monitoring-Release
 
 wget -O src.zip http://45.248.73.44/index.php/s/yr9JK7efeYEXExZ/download
 
 unzip src.zip
 ```
 
 
## 2. PaaS-TA-Monitoring Release Upload
```
 sh create.sh
``` 


## 3. PaaS-TA-Monitoring Deploy
```
 cd deployments
 
 sh deploy-paasta-monitoring.sh
 ```