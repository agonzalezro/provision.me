provision.me
============

This repo is the ansible playbook that I am using to bootstrap my Linux boxes.

Quick start
-----------

1. Edit `user` & `group` vars on the `playbook.yml` file.
2. Add the IP `127.0.0.1` to `/etc/ansible/hosts`.
3. Run ansible: `ansible-playbook playbook.yml -c local`

After that you will have few programs installed as vim, chrome, etc... and my
dot configuration files applied.
