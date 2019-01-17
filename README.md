DOCKER
=========

Requirements
------------

- CENTOS 7+

Role Variables
--------------

parameter | description
------------ | -------------
SRV_PATH | 配置目录
DOCKER_INSECURE_REGISTRIES | 注册非HTTP的镜像源
DOCKER_GRAPH | 部署目录


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: docker }

License
-------

BSD
