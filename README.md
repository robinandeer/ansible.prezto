# Ansible role: Prezto

Ansible role to install zsh and [prezto][prezto].

## Requirements
python-pycurl and python-software-properties installed.

## Example Playbook

```yaml
- hosts: servers
  remote_user: vagrant
  sudo: yes

  roles:
    - devbox.oh-my-zsh

  vars:
    user: vagrant
```

## License
MIT

## Author Information
* Robin Andeer ([robinandeer][robinandeer])

## Based on devbox.oh-my-zsh:
* Alex Lourie ([alourie][alourie])


[alourie]: https://github.com/alourie
[prezto]: https://github.com/sorin-ionescu/prezto
[robinandeer]: https://github.com/robinandeer
