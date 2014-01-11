Ubuntu 64 bit Vagrant box 
=========================

This is my base Vagrant box for any WithDigital projects. 

Vagrant packaged box with:

* Ruby - v. 2.1.0 (default) and v.2.0.0-p353, RVM supported
* Node - v. 0.10.24
* Go - v. 1.2 (default) and 1.1
* MongoDb v .2.4.8 and
* Nginx with Passenger (passenger-4.0.33.gem)

You can download the box from (hosted with Dropbox and Copy)

* http://bit.ly/precise64rngn, or
* http://bit.ly/precise64rnng

So the Vagrantfile config would look like

    config.vm.box_url = "http://bit.ly/precise64rngn"

Default (vagrant:vagrant) logins apply.

## Prerequisite

[Vagrant](http://www.vagrantup.com) and supported virtualization software must be availble before Vagrantfile config file can be run. Vagrant ships out of the box with support (provider) for VirtualBox. 

### Links to downloads

1. Download and install [Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads) (free)
2. Download and install [Vagrant](http://www.vagrantup.com/downloads.html) (free)

## Installation

Clone the repo to your development directory and run

    vagrant up

The VM environment can be SSH'ed into with 'vagrant' as username and password

     ssh -p 2222 vagrant@127.0.0.1

