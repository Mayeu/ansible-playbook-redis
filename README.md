#Redis Playbook

(really) Simple playbook to install Redis. Will come with various configuration
tweaking later on :)

##Supported system

Currently only Debian Jessie amd64 is supported. Patch welcome to support other
OS.

##Test

I add some really really basic tests. It just try to install Redis in a vagrant
VM. Just run:

    $ vagrant up

and the VM will be provisioned by ansible and the test.yml.
