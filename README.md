Sets ups a docker-compose environment on a virtual machine running Ubuntu 20.04 or Debian 11 with docker and docker-compose installed and configured to run a revolt chat server.

- reserves a static IP
- provisions a vm with the minimum specs listed below and assigns the static IP from above

CPU: 2 cores
Memory: 4 GB
Storage: 20 GB
OS: Ubuntu 20.04 or Debian 11

- updates package repository on vm
- installs docker on the vm
- installs docker-compose on the vm
- transfers docker-compose yaml to vm
- runs docker-compose on vm in directory where docker-compose.yaml is located
