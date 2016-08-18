lxd-container-install-python-example-playbook
=============================================

An Ansible example playbook for installing Python on only Debian and Ubuntu LXD containers.

## Prerequisite

Setup LXD.

## Usage

### Set up virtualenv and install the latest ansible which has the LXD module

```
virtualenv venv2
source venv2/bin/activate
pip install git+https://github.com/ansible/ansible
```

### Run playbook


```
ansible-playbook create_containers.yml -D
```

## License
MIT
