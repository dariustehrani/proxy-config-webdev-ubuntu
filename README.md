# proxy-config-webdev-ubuntu
A shell script to configure your Ubuntu 18.04 Development Machine behind a proxy.
It helps to.
* System-wide proxy settings.
* apt package manager proxy settings.
* git global proxy settings.
* Docker proxy settings.
* optionally configure zscaler private certificates.

# usage
Edit the first section in the proxy-config with your proxy details as well as no_proxy domains and IPs

````
export PROXYSETTING="http://YOURPROXY:PORT/"
export NOPROXYSETTING="localhost,127.0.0.1,::1,10.0.0.0/8,172.16.0.0/16,192.168.0.0/16"
````


