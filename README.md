# nginx for OpenShift


Nginx Image to be used in OpenShift based on CentOS.


based on tchughesiv/openshift-nginx

## Tags and Dockerfile links

* 1.13.12-1.el7_4.ngx [Dockerfile](https://github.com/Guy-Incognito/nginx-openshift/blob/1.13.12-1.el7_4.ngx/Dockerfile) Uses nginx-openshift version 1.13.12-1
* 1.15.2-1.el7_4.ngx [Dockerfile](https://github.com/Guy-Incognito/nginx-openshift/blob/1.15.2-1.el7_4.ng/Dockerfile) Uses nginx-openshift version 1.15.2-1
* 1.15.5-1.el7_4.ngx [Dockerfile](https://github.com/Guy-Incognito/nginx-openshift/blob/1.15.5-1.el7_4.ngx/Dockerfile) Uses nginx-openshift version 1.15.5-1

## How to build

```
docker build --build-arg NGINX_VERSION=**VERSION** . -t nginx 

```
