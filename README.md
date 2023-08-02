# effective-dollop
Login Enterprise OS Portability Project

build.sh
-----
download vhd/iso/extras
build zip

install.sh
-----
download zip
unzip
acl

test
---
check files
check permissions
check logs
test iptables/networking
test os resolution
test container resolution
test container certs
test certificates

workflow
-----
dev:
checkin
smoke test
- lint each tf
- lint each playbook