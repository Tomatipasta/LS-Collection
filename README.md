# Install ansible

[guide](https://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-apt-ubuntu)

[ideas] https://www.debian.org/doc/manuals/securing-debian-howto/securing-debian-howto.en.pdf

- You can take random ideas and write into README.md what is done

TODO

* Add your servers to inventory.ini under your own name
* Make your own playbook (example artur.yml)

RUN:

```
ansible-playbook artur.yml -e'ansible_user=sysadmin'
```
NB! ansible_user is needed because somehow delegate_to doesn't respect ini configuration user
