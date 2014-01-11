Ubuntu 64 bit Vagrant box 
=========================

Vagrant packaged box with:

* Ruby - v. 2.1.0 (default) and v.2.0.0-p353, RVM supported
* Node - v. 0.10.24
* Go - v. 1.2 (default) and 1.1
* MongoDb v .2.4.8 and
* Nginx with Passenger (passenger-4.0.33.gem)

You can download the box from

* http://bit.ly/precise64rngn, or
* http://bit.ly/precise64rnng

So the Vagrantfile config would look like

    config.vm.box_url = "http://bit.ly/precise64rngn"

Default (vagrant:vagrant) logins apply.
