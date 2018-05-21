Role Name
=========

Default Kibana installation

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
# Default vars for ansible-role-kibana
kibana_url: localhost

kibana_port: 5601

kibana_proxy_port: 80

Dependencies
------------

OULibraries.elasticsearch

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

[MIT](https://github.com/OULibraries/ansible-role-elk/blob/master/LICENSE)

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
