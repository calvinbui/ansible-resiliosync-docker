[![Build Status](https://travis-ci.com/calvinbui/ansible-resiliosync-docker.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-resiliosync-docker)
![GitHub release](https://img.shields.io/github/release/calvinbui/ansible-resiliosync-docker.svg)
![Ansible Quality Score](https://img.shields.io/ansible/quality/42480.svg)
![Ansible Role](https://img.shields.io/ansible/role/d/42480.svg)

# Ansible Resilio Sync

Resilio Sync in Docker

##  Requirements

N/A

## Role Variables

`resiliosync_name`: Name of container

`resiliosync_image`: Docker image to use

`resiliosync_ports`: List of ports to expose

`resiliosync_environment_variables`: Docker environmental variables. Find more at https://www.resiliosyncoffice.com/code/docker/

`resiliosync_volumes`: Directories/Docker volumes to mount

`resiliosync_docker_additional_options`: [Additional parameters](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html) to add to docker container

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
   - role: calvinbui.ansible_resiliosync_docker
```

## License

GPLv3

## Author Information

http://calvin.me
