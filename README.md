# Openshift-Project
Using UPI installation methods to install Openshift cluster
- DNS: zones in slave hekper are updated automatically if we used a cronjob
- http: must remove the 443 secure port as it will only be used by haproxy
- NFS & NTP: service ip must be declared on the dhcp config file
