# ansible-osx
Ansible playbook to setup any new machine

## Getting Started

- Run `bin/bootstrap.sh` which will perform setup steps for ansible
- Then run `ansible-playbook -i "localhost," -c local main.yml --ask-become-pass`

The playbook fulfills my goal, so it is not designed to be robust, any failures you would need to triage by yourself.
