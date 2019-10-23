# Network Automation with Ansible - Crawl / Walk / Run

# Introduction

Ansible is one of the most popular configuration management and provisioning tools in use today. While is mainly synonomous with server management Ansible is being increasingly used for tasks on network infrastructure. The goal of this lab guide is to walk through some of the functionality of Ansible from a very much beginner starting point, working towards some of the more advanced functionality. The idea is to not just focus on the tooling, as this can vary but to look at Network Automation concepts including NETCONF/RESTCONF, Rest API's, controller based networking etc. The idea of this guide is to be delivered in tandem with trainer/presenter driven content, but has been created to be standalone where the student can do these exercises independently.

For people not familiar at all with this area, typical functionality of Ansible includes:

* Automate repetitive tasks to speed routine network changes and deployments
* Leverage the same automation tools for network tasks that operations and development use
* Benefit from community built example playbooks and roles to help accelerate development
* Communicate securely with network hardware over SSH or HTTPS

## Exercise 0 - Installing Ansible 

Ansible is supported on Windows, MacOS and Linux platforms. In this exercise we'll explain the simple installation process on each platform to prepare our working environment. In the guide we'll use a Linux for exercises 1,2 and 3 but the commands across platforms should remain consistent. For detailed installation guides please use the guide provided by ansible (INSERT LINK HERE) My preferred method for building your owd network automation environment is to create a linux VM. (WHY??

For speed though you may wish to install Anisble on your day to day machine which is why we have also included indstructions for MacOS and windows also.

### Linux installation (via APT e.g. CentOS, Ubunutu etc) 

![](https://github.com/sttrayno/Ansible-Lab-Guide/blob/master/images/E0S1-Linux.gif?raw=true)

The most common way to install Ansible on MacOS is through the apt-get install ansible command as shown. Again depending on user permissions you may have to use the sudo command

![](https://github.com/sttrayno/Ansible-Lab-Guide/blob/master/images/E0S2-Linux.gif?raw=true)

When the install completes, verify Ansible has been installed through running Ansible or Ansible -h


### MacOS Installation

![](https://github.com/sttrayno/Ansible-Lab-Guide/blob/master/images/E0S1.gif?raw=true)

The prefered way to install Ansible on MacOS is through the pip install command as shown. Again depending on user permissions you may have to use the sudo command

![](https://github.com/sttrayno/Ansible-Lab-Guide/blob/master/images/E0S2.gif?raw=true)

When the install completes, verify Ansible has been installed through running Ansible or Ansible -h

### Windows Installation - TBD

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
 
One of the fundamental concepts of Ansible are playbooks. Playbooks are one of the core features of Ansible and tell Ansible what to execute. They are like a to-do list for Ansible that contains a list of tasks. Playbooks are the files where Ansible code is written. Playbooks are written in YAML format. YAML stands for Yet Another Markup Language. See them as like a to-do list for Ansible that contains a list of tasks.

Playbooks contain the steps which the user wants to execute on a particular machine. Playbooks are run sequentially. Playbooks are the building blocks for all the use cases of Ansible.

In this exercise we are going to create our own Ansible playbook to push a configuration to our always-on sandbox. As this is a shared environment we're going to have

NOTE: Your instructor should assign you a number to use in your config for this lab, keep a note of it as we'll use it later on. if you're doing this self paced just use your birthday in date format. So for example if your birthday is the 12th of August - use 1208 or 0812 whatever your personal preference is.

## Exercise 2 (Walk) - 

## Exercise 3 (Run) - 


