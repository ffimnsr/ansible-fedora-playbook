# Ansible Fedora Playbook

This repository contains my custom ansible playbook to bootstrap a fresh fedora installation.

To use this, first you must install `ansible`.

```bash
sudo dnf update -y
sudo dnf install ansible -y
```

Then clone this repository in an workable directory.

```
git clone git@github.com:ffimnsr/ansible-fedora-playbook.git
```

Then run this playbook using the `ansible-playbook` command.

```bash
ansible-playbook -K post_install.yml
```

Verify if changes been made on the host machine.
