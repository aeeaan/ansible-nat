correcthorse.nat
=========

An ansible role for cocnfiguring a basic NAT server. Only support firewalld for now.


Role Variables
--------------

| Variable				| Default				| Notes					|
| :---					| :---					| :---					|
| nat_bastion				| false					| Use NAT server as bastion host	|


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.nat }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
