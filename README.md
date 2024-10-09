Juniper Aggregate Route Configuration
=========

This role will configure basic aggregate routes for JUNOS devices.

Requirements
------------
ncclient


Role Variables
--------------
aggregate_routes:
* route: ip route, string

Dependencies
------------


Example Playbook
----------------

    - hosts: vmx1
      roles:
         - { role: junos_aggregate_routes }

License
-------

BSD

Author Information
------------------

Marc Colburn
# junos_aggregate_routes
