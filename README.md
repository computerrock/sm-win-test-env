
# Vagrant environments for Windows / IE #

List of environments:

- XP with IE6
- XP with IE8
- Vista with IE7
- Windows 7 with IE8
- Windows 7 with IE9
- Windows 7 with IE10
- Windows 7 with IE11
- Windows 8 with IE10
- Windows 8.1 with IE11

## How to use ##

### Setup ###

1. Install [Vagrant](https://www.vagrantup.com/).
2. Download needed modern.ie box file for vagrant and put it in 'boxes' folder: [link](http://blog.syntaxc4.net/post/2014/09/03/windows-boxes-for-vagrant-courtesy-of-modern-ie.aspx)

### Vagrant environment manipulation ###

**Boot** virtual machine by going to environment folder (eg. ie8-win7) and running `vagrant up`.

**Suspending** the virtual machine by calling `vagrant suspend` will save the current running state of the machine and stop it.

**Halting** the virtual machine by calling `vagrant halt` will gracefully shut down the guest operating system and power down the guest machine.

**Destroying** the virtual machine by calling `vagrant destroy` will remove all traces of the guest machine from your system. It'll stop the guest machine, power it down, and remove all of the guest hard disks.

