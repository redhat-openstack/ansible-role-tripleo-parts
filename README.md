Role Name
=========

ansible-role-tripleo-parts

part := reusable chunks of ansible that makes sure a core/basic service is available.

The following are aspects of parts:

1. Super simple.  If the part is doing something more than installing packages and starting a service, it's probably not a part

2. no dependencies

3. Must minimally handle running correctly on Centos as well as RHEL.


Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None, on purpose.  They are not allowed here.

License
-------

Apache 2

Author Information
------------------

RDO Community
