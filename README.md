DOCKER
=========

Deploy docker services via ansible.

Installation
------------

`ansible-galaxy install gengxiankun.docker`

Requirements
------------

- CENTOS

Role Variables
--------------

parameter | description
------------ | -------------
DOCKER_INSECURE_REGISTRIES | 注册非HTTP的镜像源
DOCKER_GRAPH | 部署目录


Example Playbook
----------------

    - hosts: servers
      roles:
         - gengxiankun.docker

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
