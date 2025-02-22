# Changelog

## In Development
* Update IP address to be `192.168.56.56` to support WSL and Windows latest VirtualBox client.

## v3.8.1-20231213
* StackStorm 3.8.1 released

## v3.8.0-20230127
* Build Vagrant boxes with GitHub (#63)

## v3.8.0-20221126
* StackStorm 3.8.0 released

## v3.7.0-20220506
* StackStorm 3.7.0 released

## v3.6.0-20211122
* StackStorm 3.6.0 released

## v3.6.0-20211120
* StackStorm 3.6.0 released
* Switch OS to Ubuntu Bionic `18.04.6` from `18.04.5`

## v3.5.0-20210628
* StackStorm 3.5.0 released
* Switch OS to Ubuntu Bionic `18.04` LTS (#61)
* Switch the VirtualBox guest additions installation from .deb packages to native .iso (#61)

## v3.4.1-20210314
* StackStorm 3.4.1 released

## v3.4.0-20210304
* StackStorm 3.4.0 released
* Remove references to EWC/Enterprise StackStorm #53
* Remove check for the (now removed) `st2resultstracker` process from tests #55
* Add `--u16-add-insecure-py3-ppa` to enable Ubuntu 16.04 LTS support

## v3.3.0-20201021
* StackStorm 3.3.0 released
* Upgrade Ubuntu to `16.04.07` (#50)
* Switch the VirtualBox guest additions installation from .iso to .deb packages (#49)
* Remove Postgres from cleanup script (no longer needed since Mistral isn't installed) (#52)

## v3.2.0-20200429
* StackStorm 3.2.0 released

## v3.1.0-20190701
* StackStorm 3.1.0 released

## v3.0.1-20190529
* StackStorm 3.0.1 released

## v3.0.0-20190426
* StackStorm 3.0.0 released

## v2.10.4-20190315
* StackStorm 2.10.4 released

## v2.10.3-20190308
* Upgrade Ubuntu to `16.04.06` (#46)

## v2.10.3-20190307
* StackStorm 2.10.3 released

## v2.10.2-20190223
* StackStorm 2.10.2 released

## v2.10.1-20181220
* StackStorm 2.10.1 released

## v2.9.2-20181219
* StackStorm 2.9.2 released

## v2.10.0-20181215
* StackStorm 2.10.0 released

## v2.9.0-20180925
* Use correct version of linux-headers
* Upgrade from Ubuntu 16.04.4 to 16.04.5

## v2.9.0-20180921
* StackStorm 2.9.0 released

## v2.8.1-20180717
* StackStorm 2.8.1 released

## v2.8.0-20180710
* StackStorm 2.8.0 released

## v2.7.2-20180614
* Use /30 mask for private network (access via IP `10.10.10.10`). (#41)

## v2.7.2-20180523
* Add Vagrant port-forwarding rule to access st2web via `https://127.0.0.1:9000/` as a fallback (#36)

## v2.7.2-20180516
* StackStorm 2.7.2 released

## v2.7.1-20180514
* StackStorm 2.7.1 released
* Fix Vagrant Cloud deploy step, caused by wrong 'file not exist' error (#31)
* Expose StackStorm Vagrant access via IP `10.10.10.10` (#29)
* Extract from `CIRCLE_TAG` and pin `ST2_VERSION` & `BOX_VERSION` on release (#33)

## v2.7.1-20180511
* Add continuous integration (#19)
* Deploy tagged builds to GitHub releases (#25)
* Add `ST2_VERSION` and `BOX_VERSION` ENV vars for version pinning (#26)
* Create custom [`vagrant-cloud-standalone`](https://github.com/armab/packer-post-processor-vagrant-cloud-standalone) Packer post processor, `make deploy` to Vagrant Cloud (#27)

## v2.7.1-20180507
* Initial release with minimally working StackStorm Vagrant box, created from Packer build pipeline
* Add first system Vagrant-focused integration tests, tie them with the build (#5)
* Add custom MOTD/welcome message after logging in to console (#15)
* Add StackStorm infrastructure integration tests, ship with new `st2-integration-tests` executable available to user (#20)
* Install Virtualbox guest additions (#22)
