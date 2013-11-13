#Redis Playbook

(really) Simple playbook to install Redis. Will come with various configuration
tweaking later on :)

##Supported system

Currently only Debian Jessie amd64 is supported and tested. Patch welcome to
support other OS.

##Installation

Just clone (or submodule) this repository under the name `redis` in your
`roles` directory. This file, `test.yml` and `Vagrantfile` will be ignored by
ansible anyway.

##Test

There is some really basic tests with the playbook. It just try to install
Redis in a vagrant VM.  Just run:

    $ vagrant up

and the VM will be provisioned by ansible with the test.yml.
