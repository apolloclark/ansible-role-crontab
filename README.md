# Ansible Role: auditbeat

Ansible Role to install and configure Crontabs for Ubuntu.


## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`).
You can overload the variables by creating a dictionary called "crontab", ex:

    crontab:
      global:
    	- "@reboot root logger 'system restarted'"
## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - apolloclark.crontab

## License

MIT / BSD

## Author Information

This role was created in 2018 by [Apollo Clark](https://www.apolloclark.com/)
