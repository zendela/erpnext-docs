---
sidebar_position: 1
---


### Initialize project
Initialize a new frappe project called testing
```shell
bench init  --frappe-branch v13.2.0 testing
```

### Install erpnext
```shell
bench get-app erpnext git@github.com:zendela/z-healthcare.git --branch nhif_insurance_exceptions
```
### activate the virtual env
```shell
cd testing
source env/bin/activatenhif_insurance_exceptions
```
### create a new site 
```shell
bench new-site testing.local
```
### install erpnext
```shell
bench --site  testing.local install-app erpnext
```

### start dev server
```shell
bench start
```



