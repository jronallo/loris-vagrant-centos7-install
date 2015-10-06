# Install Loris in Vagrant CentOS 7

In order to test what would be required to install Loris on a RHEL 7 server, I tested it out in a CentOS 7 Vagrant box. This includes a demo OpenSeadragon page.

The most interesting file will be loris-vagrant-install.sh which is a Bash script with all the steps necessary install under CentOS 7. Hopefully this helps anyone that has to deploy Loris under RHEL 7.

## Installation

1. You must have Vagrant installed.
2. Clone this repository.
3. `cd loris-vagrant-centos7-install`
4. `vagrant up`
5. visit http://localhost:8080
