# nginx for OpenShift


Nginx Image to be used in OpenShift based on CentOS.


based on tchughesiv/openshift-nginx

## Tags and Dockerfile links

Tags refer to the nginx version in use:

* 1.13.12-1.el7_4.ngx [Dockerfile](https://github.com/Guy-Incognito/nginx-openshift/blob/1.13.12-1.el7_4.ngx/Dockerfile)
* 1.15.2-1.el7_4.ngx [Dockerfile](https://github.com/Guy-Incognito/nginx-openshift/blob/1.15.2-1.el7_4.ng/Dockerfile)
* 1.15.5-1.el7_4.ngx [Dockerfile](https://github.com/Guy-Incognito/nginx-openshift/blob/1.15.5-1.el7_4.ngx/Dockerfile)
* 1.15.8-1.el7_4.ngx [Dockerfile](https://github.com/Guy-Incognito/nginx-openshift/blob/1.15.8-1.el7_4.ngx/Dockerfile)

## How to build

```
docker build --build-arg NGINX_VERSION=**VERSION** . -t nginx 

```
