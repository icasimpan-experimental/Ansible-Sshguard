# Ansible-Sshguard
Ansible Role to install and configure Sshguard



### Goal
The main goal of this project is to provide an Ansible role for easy installation and configure of Sshguard to protect your server from Bruteforce attacks



### Requirements
Ansible 2+  



### Usage
* Clone this repo to your Ansible roles location (cloning is best way to update the changes made in this repo to your config as well)
* Make changes in your Ansible playbook settings to run this role  
eg:

```ruby
roles:
#    - YoutImportantRole
    - Ansible-Sshguard
```



### Supported Devices
At the moment it is only tested with Ubuntu 16.04 LTS



### Whitelisting
* If you want to whitelist your IP, If you want to **Pentest** your systems or using external service for such testing then place the list IPs in the **defaults/main.yml** file in the *ips* variable.




### TO DO
* Make a Generic solution to support other distros then just Ubuntu.
* Add a test file to test the config via Travis to maintain integrity with all the distros that will be added.




### What it does
* Installs latest Sshguard in your distro
