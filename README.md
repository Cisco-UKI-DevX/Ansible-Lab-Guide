# Network Automation with Ansible - Crawl / Walk / Run

# Introduction

Ansible is one of the most popular configuration management and provisioning tools in use today. While is mainly synonomous with server management Ansible is being increasingly used for tasks on network infrastructure. The goal of this lab guide is to walk through some of the functionality of Ansible from a very much beginner starting point, working towards some of the more advanced functionality. The idea is to not just focus on the tooling, as this can vary but to look at Network Automation concepts including NETCONF/RESTCONF, Rest API's, controller based networking etc

Functionality of ansible includes:

* Automate repetitive tasks to speed routine network changes and deployments
* Leverage the same automation tools for network tasks that operations and development use
* Benefit from community built example playbooks and roles to help accelerate development
* Communicate securely with network hardware over SSH or HTTPS

## Exercise 0 - Installing Ansible 

Ansible is supported on Windows, MacOS and Linux platforms. In this exercise we'll explain the simple installation process on each platform to prepare our working environment. In the guide we'll use Linux but the commannds across platforms should remain consistent. For detailed installation guides please use the guide provided by ansible (INSERT LINK HERE) My preferred method for building your owd network automation environment is to create a linux VM. (WHY??

For speed though you may wish to install anisble on your day to day machine which is why we have also included indstructions for MacOS and windows also.

### Linux installation (via APT e.g. CentOS, Ubunutu etc) 


### MacOS Installation

![](https://github.com/sttrayno/Ansible-Lab-Guide/blob/master/images/E0S1.gif?raw=true)

The prefered way to install Ansible on MacOS is through the pip command as shown. Note: depending on user permissions you may have to use the sudo command

![](https://github.com/sttrayno/Ansible-Lab-Guide/blob/master/images/E0S2.gif?raw=true)

When the install completes, verify Ansible has been installed through running Ansible or Ansible -h

### Windows Installation

### Prequisites

Before we get started with network automation we'll need a test environment, one of the easiest test environments you'll find is on the Cisco DevNet Sandbox which has multiple options. These are completely free and can in some cases be accessed within seconds.https://developer.cisco.com/docs/sandbox/#!overview/all-networking-sandboxes

Most popular sandboxes include:

* IOS-XE (CSR) - Always-On
* IOS-CR - Always-On
* Multi IOS test environment (VIRL based) - Reservation required
* Cisco SD-WAN environment - Always-On
* Cisco DNA-C environment - Always-On

Please note you are free to use this with your own hardware or test environment. However the commands in this lab guide have been tested for the sandboxes they correspond to. Also note that This sandbox resource is shared. This means that you can see other developers' and network engineers' changes and they can see yours. Please, do not erase or change configuration you have not created yourself.

## Exercise 1 (Crawl) - Simple device feature configuration with Ansible and building our first playbook


## Exercise 2 (Walk) - 

## Exercise 3 (Run) - 


