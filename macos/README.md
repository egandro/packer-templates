# RUNTIME REQUIREMENTS

* [unlocker](https://github.com/DrDonk/unlocker)
* [Vagrant VMware plugin](https://www.vagrantup.com/vmware)
* [VMware](https://www.vmware.com/) (e.g. Fusion, Workstation, Player)
* [Vagrant](https://www.vagrantup.com/)
* Apple hardware

# BUILDTIME REQUIREMENTS

* macOS 10.13 ISO + SHA512 checksum, such as generated by [generate-iso.macos.sh](https://github.com/mcandre/macos-isos)
* [VMware](https://www.vmware.com/) (e.g. Fusion, Workstation, Player)
* [packer](https://www.packer.io/) with [patches](https://github.com/mcandre/packer/tree/super-key) for Super key and holding A-Z keys
* 40+ GB of free space
* Apple hardware

## Recommended extras

* [Taurine](https://itunes.apple.com/us/app/taurine/id960276676?mt=12) / [Caffeine for Windows](http://www.zhornsoftware.co.uk/caffeine/) / [Caffeine for Ubuntu](https://launchpad.net/caffeine) to prevent host from hibernating during long packer builds

# CREDITS

* [timsutton/osx-vm-templates](https://github.com/timsutton/osx-vm-templates) provided several resources as examples for configuring macOS for Vagrant environments.