# OpenShift Nginx PHP 7 phpservermon 3.11 Cartridge
Nginx 1.9 with PHP 7.0 phpservermon  on OpenShift.

* Nginx: 1.11.6
* PHP: 7.0.13
* Composer: 1.2.4
* phpservermon: 3.11

## Installation

### Web Console
<a href="https://openshift.redhat.com/app/console/application_type/custom?cartridges%5B%5D=http://cartreflect-claytondev.rhcloud.com/github/pinodex/openshift-cartridge-nginx-php7&amp;name=php"><img alt="Run+PHP+7+on+OpenShift" src="https://launch-shifter.rhcloud.com/launch/light/Run%20PHP%207%20on.svg" /></a>

Alternatively, you can use this [cartridge definition](http://cartreflect-claytondev.rhcloud.com/github/pinodex/openshift-cartridge-nginx-php7) on application creation page.


### Base : 
```
https://github.com/pinodex/openshift-cartridge-nginx-php7
```

### Create 
```
rhc app create phpservermon mysql-5.5 cron  http://cartreflect-claytondev.rhcloud.com/github/echochio-tw/openshift-nginx-php7-phpservermon
```
