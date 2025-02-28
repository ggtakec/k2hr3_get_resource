K2HR3 Get Resource(K2HR3 Utilities)
===================================
[![Systemd AntPickax CI](https://github.com/yahoojapan/k2hr3_get_resource/workflows/Systemd%20AntPickax%20CI/badge.svg)](https://github.com/yahoojapan/k2hr3_get_resource/actions)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/yahoojapan/k2hr3_get_resource/blob/master/COPYING)
[![GitHub forks](https://img.shields.io/github/forks/yahoojapan/k2hr3_get_resource.svg)](https://github.com/yahoojapan/k2hr3_get_resource/network)
[![GitHub stars](https://img.shields.io/github/stars/yahoojapan/k2hr3_get_resource.svg)](https://github.com/yahoojapan/k2hr3_get_resource/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/yahoojapan/k2hr3_get_resource.svg)](https://github.com/yahoojapan/k2hr3_get_resource/issues)
[![RPM packages](https://img.shields.io/badge/rpm-packagecloud.io-844fec.svg)](https://packagecloud.io/antpickax/stable)
[![debian packages](https://img.shields.io/badge/deb-packagecloud.io-844fec.svg)](https://packagecloud.io/antpickax/stable)
[![ALPINE packages](https://img.shields.io/badge/apk-packagecloud.io-844fec.svg)](https://packagecloud.io/antpickax/stable)

### **K2HR3** - **K2H**dkc based **R**esource and **R**oles and policy **R**ules

![K2HR3 system](https://k2hr3.antpick.ax/images/top_k2hr3.png)

#### K2HR3 System Overview
**K2HR3** (**K2H**dkc based **R**esource and **R**oles and policy **R**ules) is one of extended **RBAC** (**R**ole **B**ased **A**ccess **C**ontrol) system.  
K2HR3 works as RBAC in cooperation with **OpenStack** which is one of **IaaS**(Infrastructure as a Service), and also provides useful functions for using RBAC.  

K2HR3 is a system that defines and controls **HOW**(policy Rule), **WHO**(Role), **WHAT**(Resource), as RBAC.  
Users of K2HR3 can define **Role**(WHO) groups to access freely defined **Resource**(WHAT) and control access by **policy Rule**(HOW).  
By defining the information and assets required for any system as a **Resource**(WHAT), K2HR3 system can give the opportunity to provide access control in every situation.  

K2HR3 provides **+SERVICE** feature, it **strongly supports** user system, function and information linkage.

![K2HR3 system overview](https://k2hr3.antpick.ax/images/overview_abstract.png)

K2HR3 is built [k2hdkc](https://github.com/yahoojapan/k2hdkc), [k2hash](https://github.com/yahoojapan/k2hash), [chmpx](https://github.com/yahoojapan/chmpx) and [k2hash transaction plugin](https://github.com/yahoojapan/k2htp_dtor) components by [AntPickax](https://antpick.ax/).

### K2HR3 Get Resource(K2HR3 Utilities)
K2HR3 Get Resource is a Systemd Timer Service for retrieving RESOURCE data from [K2HR3](https://k2hr3.antpick.ax/) System, this is one of utility for it.

- Systemd timer service, which starts regularly.
- Runs on a virtual machine launched with UserDataScript by the K2HR3 system.
- Get K2HR3 resource related to the role for the virtual machine.
- Use the common directory /etc/antpickax.

### Documents
- [K2HR3 Document](https://k2hr3.antpick.ax/index.html)
- [K2HR3 Web Application Usage](https://k2hr3.antpick.ax/usage_app.html)
- [K2HR3 Command Line Interface Usage](https://k2hr3.antpick.ax/cli.html)
- [K2HR3 REST API Usage](https://k2hr3.antpick.ax/api.html)
- [K2HR3 OpenStack Notification Listener Usage](https://k2hr3.antpick.ax/detail_osnl.html)
- [K2HR3 Watcher Usage](https://k2hr3.antpick.ax/tools.html)
- [K2HR3 Get Resource Usage](https://k2hr3.antpick.ax/tools.html)
- [K2HR3 Utilities for Setup](https://k2hr3.antpick.ax/setup.html)
- [K2HR3 Demonstration](https://demo.k2hr3.antpick.ax/)

- [About k2hdkc](https://k2hdkc.antpick.ax/)
- [About k2hash](https://k2hash.antpick.ax/)
- [About chmpx](https://chmpx.antpick.ax/)
- [About k2hash transaction plugin](https://k2htpdtor.antpick.ax/)

- [About AntPickax](https://antpick.ax/)

### Repositories
- [K2HR3 main repository](https://github.com/yahoojapan/k2hr3)
- [K2HR3 Web Application repository](https://github.com/yahoojapan/k2hr3_app)
- [K2HR3 Command Line Interface repository](https://github.com/yahoojapan/k2hr3_cli)
- [K2HR3 REST API repository](https://github.com/yahoojapan/k2hr3_api)
- [K2HR3 OpenStack Notification Listener](https://github.com/yahoojapan/k2hr3_osnl)
- [K2HR3 Get Resource](https://github.com/yahoojapan/k2hr3_get_resource)
- [K2HR3 Utilities](https://github.com/yahoojapan/k2hr3_utils)
- [K2HR3 Container Registration Sidecar](https://github.com/yahoojapan/k2hr3_sidecar)

- [k2hdkc](https://github.com/yahoojapan/k2hdkc)
- [k2hash](https://github.com/yahoojapan/k2hash)
- [chmpx](https://github.com/yahoojapan/chmpx)
- [k2hash transaction plugin](https://github.com/yahoojapan/k2htp_dtor)

### Packages
- [RPM packages(packagecloud.io)](https://packagecloud.io/app/antpickax/stable/search?q=k2hr3-get-resource&filter=rpm&dist=&arch=)
- [Debian packages(packagecloud.io)](https://packagecloud.io/app/antpickax/stable/search?q=k2hr3-get-resource&filter=deb&dist=&arch=)
- [ALPINE packages(packagecloud.io)](https://packagecloud.io/app/antpickax/stable/search?q=k2hr3-get-resource&filter=all&dist=alpine&arch=)

### License
This software is released under the MIT License, see the license file.

### AntPickax
K2HR3 is one of [AntPickax](https://antpick.ax/) products.

Copyright(C) 2021 Yahoo Japan Corporation.
