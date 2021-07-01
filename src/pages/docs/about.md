---
title: About
seo:
  title: ''
  description: ''
  extra:
    - name: Overview
      value: ''
      keyName: overview
      relativeUrl: true
  type: stackbit_page_meta
template: docs
---
### Infrastructure 

The application is uncoupled, modularized and containerized, meaning all our applications are hosted in a virtual machine running docker, so no hard setups or complex installations just simply docker and docker-compose running on the machine. 

For allow ports and ssh we use UFW, native on ubuntu servers. 

 

### Domain 

Domains are handled by Namecheap, we use Alias Record in order to create the subdomains pointing to **raptortech.io** and an A record pointing to our public IP address **80.249.0.245**. As all our virtual machines are in the same WLAN they are all accessible for the outside world, if not using a vpn and accessing each private Ip address. 



### SSL 

Our ssl provider is ZeroSsl, which let us generate 3 1-year certificates and infinite 90-days certificates to our apps 
