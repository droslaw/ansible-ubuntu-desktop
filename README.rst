Requirements
------------

1. Ansible

.. code-block:: bash
  sudo snap install curl
  curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
  python3 get-pip.py --user
  python3 -m pip install --user ansible


.. code-block:: bash

  sudo apt-get update
  sudo apt-get install software-properties-common
  sudo apt-add-repository ppa:ansible/ansible
  sudo apt-get update
  sudo apt-get install ansible


2. Vagrant plugin vagrant-disksize

.. code-block:: bash

  vagrant plugin install vagrant-disksize

May be required;

.. code-block:: bash

  sudo apt-get install libffi-dev
  gem install ffi


Run
---

.. code-block:: bash

  ansible-playbook -i localhost playbook.yml --ask-become-pass
