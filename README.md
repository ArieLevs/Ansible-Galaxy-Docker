# Ansible-Galaxy-Docker
Ansible Galaxy Docker installation role

This role will install Docker,  
Currently supported Debian (Raspberry Pi) and CentOS 7/8.

### Usage
add 
```yaml
- name: docker_install_role
  src: arielevs.docker
  version: 0.1.3
```
to `requirements.yaml` file.  
then use as:
```yaml
- hosts: all

  roles:
    - docker_install_role
```
