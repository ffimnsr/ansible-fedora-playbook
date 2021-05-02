# Ansible Fedora Playbook

This repository contains my custom ansible playbook to bootstrap a fresh fedora installation.

To run:

1. Install `ansible`.

```bash
sudo dnf ansible
```

2. Clone this repository.

```
git clone git@github.com:ffimnsr/ansible-fedora-playbook.git
```

3. Run this playbook.
```bash
ansible-playbook --ask-become-pass post_install.yml
```

4. Verify if changes been made.
