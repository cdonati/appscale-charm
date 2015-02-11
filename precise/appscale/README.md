# Overview
AppScale is a platform that allows users to deploy and host their 
own Google App Engine applications. It executes automatically over 
Amazon EC2, Google Compute Engine, Digital Ocean, Rackspace, Eucalyptus, 
CloudStack, OpenStack, as well as Xen, VirtualBox, VMWare, and KVM. It has been
developed and is maintained by AppScale Systems, Inc., in Santa Barbara, CA.

It supports the Python, Java, PHP, and Go Google App Engine platforms.

To find out more visit http://appscale.com

# Installation
To deploy this charm you will need at a minimum: a cloud environment, working
Juju installation and a successful bootstrap. Once bootstrapped, deploy the
AppScale charm:

    juju deploy appscale
You can find the IP address of the running AppScale service with

    juju status
Once the service is ready, you can access the sample App Engine application at
`<ip address>:8080` and the AppScale dashboard at `<ip address>:1080`.

## Official Documentation
https://github.com/AppScale/appscale/wiki

## Latest Release ##
The latest stable release is AppScale 2.1.0, released in December, 2014.
Feature requests and pull requests gladly welcomed.

## Mailing List ##
Join the mailing list for announcements, help, and to discuss 
cloud research: http://groups.google.com/group/appscale_community

## IRC ##
Also, join us on #appscale on freenode if you have questions, suggestions, 
comments, or just want to say hi!
http://webchat.freenode.net/?channels=appscale&uio=d4

## Why Use AppScale? ##
Our goal with AppScale is to provide an open-source cloud platform that you 
can use to deploy your Google App Engine applications on clusters and clouds of your choice.    

## Screen Shots ##
![AppScale Dashboard Screenshot](http://www.appscale.com/wp-content/uploads/2014/06/appscale-screenshot.png)

## Sponsors ##
Google

IBM Research

National Science Foundation

National Institutes of Health

[![Analytics](https://ga-beacon.appspot.com/UA-39403730-2/AppScale/appscale)](https://github.com/appscale/appscale)
