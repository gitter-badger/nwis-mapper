# nwis-mapper

[![Join the chat at https://gitter.im/USGS-WiM/nwis-mapper](https://badges.gitter.im/USGS-WiM/nwis-mapper.svg)](https://gitter.im/USGS-WiM/nwis-mapper?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

> codebase for NWIS mapper

## Server setup

#### 1.  Deploy instance on AWS

##### current system specs

 - m3.large 
 - 8GB attached volume 
 - ubuntu server 14.04 LTS

#### 2.  Set up server

copy server setup script from github
```bash
wget https://raw.githubusercontent.com/USGS-OWI/nwis-mapper/master/server-config/server-setup.sh
```

run server setup script
```bash
sudo sh server-setup.sh
```

the nwis mapper application should now be running
