# Making an ubuntu machine a Lengo-machine

Just a repo i store an ansible playbook for creating work-ready ubuntu-machine with my preferences.

## Howto

Install `git` and `ansible` and go ham

```bash
$ sudo apt install git ansible
$ git clone https://github.com/emillen/client-computer-ansible.git
$ cd client-computer-ansible
$ ansible-playbook -K local-setup.yaml
```
