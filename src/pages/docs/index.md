---
title: Welcome to RaptorOS
seo:
  type: stackbit_page_meta
  title: Welcome to RaptorOs
  description: This is the documentation page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Welcome to Libris
      keyName: property
    - name: 'og:description'
      value: This is the documentation page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Welcome to Libris
    - name: 'twitter:description'
      value: This is the documentation page
template: docs
---
The best way to describe RaptorOs is to think in a ecossystem, when you have our pycom device on a machine we are collecting data from the machine in which we can control it, but also we are saving some of mqqt data coming through on our web Server in our database.

***

***

## Infrastructure 

The application is uncoupled, modularized and containerized, meaning all our applications are hosted in a virtual machine running docker, so no hard setups or complex installations just simply docker and docker-compose running on the machine. 

For allow ports and ssh we use UFW, native on ubuntu servers. 

 

## Domain 

Domains are handled by Namecheap, we use Alias Record in order to create the subdomains pointing to **raptortech.io** and an A record pointing to our public IP address **80.249.0.245**. As all our virtual machines are in the same WLAN they are all accessible for the outside world, if not using a vpn and accessing each private Ip address. 

## SSL 

Our ssl provider is ZeroSsl, which let us generate 3 1-year certificates and infinite 90-days certificates to our apps 
