Requirements
------------

1. Ansible

$ sudo apt-get update
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible

2. Vagrant plugin vagrant-disksize

$ vagrant plugin install vagrant-disksize

$ sudo apt-get install libffi-dev
$ gem install ffi


Run
---

`ansible-playbook -i localhost playbook.yml --ask-become-pass`
